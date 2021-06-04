# Experience on Painterly Harmonization

Tianyu Jiang

jianti@iu.edu



This project is an re-implementation of the paper "Deep Painterly Harmonization"<sup><a href="#ref1">1</a></sup>  in Tensorflow, which aims to make the new added pattern fit perfectly with the original oil painting. 

I use a pre-trained VGG-16 Network as the feature extractor, which is used widely in style transfer field. There'll be two passes. The first pass initially transfers the style and generates an intermediate image, and the second pass continues to improve the output quality.



## Results

![output](materials\Jan_van_Eyck_33\output.png)

![output](materials\Vincent_van_Gogh_282\output.png)

![output](materials\Claude_Monet_57\output.png)

![output](materials\Paul_Cezanne_16\output.png)

![output](materials\Vasiliy_Kandinskiy_24\output.png)

## References

1. <span name = "ref1">Luan F, Paris S, Shechtman E, et al. Deep painterly harmonization[C]//Computer graphics forum. 2018, 37(4): 95-106.</span>

