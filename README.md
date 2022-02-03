# Pytorch RIDNet Implementation (unofficial code)

## [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Anwar_Real_Image_Denoising_With_Feature_Attention_ICCV_2019_paper.pdf)
## Real Image Denoising with Feature Attention (ICCV, 2019)


***Abstract***


*Deep convolutional neural networks perform better
on images containing spatially invariant noise (synthetic
noise); however, their performance is limited on real-noisy
photographs and requires multiple stage network modeling. To advance the practicability of denoising algorithms,
this paper proposes a novel single-stage blind real image
denoising network (RIDNet) by employing a modular architecture. We use a residual on the residual structure to
ease the flow of low-frequency information and apply feature attention to exploit the channel dependencies. Furthermore, the evaluation in terms of quantitative metrics and visual quality on three synthetic and four real noisy datasets
against 19 state-of-the-art algorithms demonstrate the superiority of our RIDNet.*



![image](https://user-images.githubusercontent.com/33386742/152332696-244dd263-b210-45ab-b551-5f6e6d7d8df7.png) 

<br/>


## Train
```
> python train.py --epochs 100 --batch_size 16
```

## Reference
* [Official code](https://github.com/saeed-anwar/RIDNet)
