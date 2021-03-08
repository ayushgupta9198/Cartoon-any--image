# Cartoon-any-image


In this code you will able to convert any image into cartoonist view , its just begining to this results , will cover more with AI-Art

Also in this you can also find read me file to make it run with ease.

Download the converted models:

```
sh pretrained_model/download_pth.sh
```

- For testing:

```
python test.py --input_dir YourImgDir --style Hosoda --gpu 0
```

## Torch

Working with the original models in Torch is also fine. I just convert the weights (bias) in their models from CudaTensor to FloatTensor so that `cudnn` is not required for loading models.

- Download the converted models:

```
sh pretrained_model/download_t7.sh
```

- For testing:

```
th test.lua -input_dir YourImgDir -style Hosoda -gpu 0
```





let me know if I can help you with anything
