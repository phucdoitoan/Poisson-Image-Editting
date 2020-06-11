# Poisson-Image-Editting
My Python/Numpy implementation of the [Poisson Image Editting](https://dl.acm.org/doi/10.1145/1201775.882269) for my CV class.

Taking a source image,

![Kim face](https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/my_data/kim.png)

a mask of the source image,

![kim mask](https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/my_data/kim_mask.png)

and a target image.

![Trump face](https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/my_data/trump.jpg)

A simple composition will result an image with obvious boundary.

![Simple composition](https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/kim_trump_wo_poisson.png)

Poisson Image Editting gives a smoothed, far better image.

![Poisson composition](https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/kim_trump_w_poisson.png)
