# Poisson-Image-Editting
My Python/Numpy implementation of the [Poisson Image Editting](https://dl.acm.org/doi/10.1145/1201775.882269) for my CV class.

### Given a source image, a mask of the source image, and a target image.

<table>
  <tr>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/my_data/kim.png" width="200" title="Kim face">
    </th>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/my_data/kim_mask.png" width="200" title="Kim mask">
    </th>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/my_data/trump.jpg" width="200" title="Trump face">
    </th>
  </tr>
</table>

### A simple composition will result an image with obvious boundary. Poisson Image Editting gives a smoothed, far better image.


<table>
  <tr>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/kim_trump_wo_poisson.png" width="200" title="Without poisson">
    </th>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/kim_trump_w_poisson.png" width="200" title="With poisson">
    </th>
  </tr>
</table>

## Another examples:

### An eye on a hand

<table>
  <tr>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/hand_eye_wo_poisson.png" width="200" title="Without poisson">
    </th>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/hand_eye_w_poisson.png" width="200" title="With poisson">
    </th>
  </tr>
</table>


### A mouth on a hand

<table>
  <tr>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/hand_mouth_wo_poisson.png" width="200" title="Without poisson">
    </th>
    <th>
      <img src="https://github.com/phucdoitoan/Poisson-Image-Editting/blob/master/hand_mouth_w_poisson.png" width="200" title="With poisson">
    </th>
  </tr>
</table>
