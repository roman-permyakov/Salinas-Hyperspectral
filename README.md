###### Hyperspectral Imagery. Salinas

# **Land Cover Classification of Hyperspectral Satellite Imagery** <img src="https://images.squarespace-cdn.com/content/v1/52729d11e4b0b9200a7023ea/1524338737642-7486A223WJUMFDSX6PWQ/Artboard+1+copy+42.png" height="50"><br>Using Convolutional Neural Networks

##  <p align="justify"> [Classify Lands in HSI over Salinas Valley, California](https://yandex.ru/maps/103361/salinas/?ll=-121.604262%2C36.677279&z=10.88)</p> 
 
###  Introduction
<p align="justify">Hyperspectral Imaging is an important technique in remote sensing, which collects the electromagnetic spectrum
ranging from the visible to the near-infrared wavelength. Hyperspectral imaging sensors often provide hundreds of narrow spectral bands
from the same area on the surface of the Earth. In hyperspectral images (HSI), each pixel can be regarded as a high-dimensional vector
whose entries correspond to the spectral reflectance in a specific wavelength

Convolutional Neural Networks (CNN) is a type of deep learning method that uses convolutional multiplication based on artificial neural networks.
Recently, CNN has been widely used in land cover classification, showing remarkable performance. Typical CNNs are composed of convolutional
layers, pooling layers, and fully connected layers.

The Salinas HSI was collected by the 224-band AVIRIS sensor over Salinas Valley, California. It is characterized by high spatial
resolution (3.7-meter pixels). The area covered comprises 512 lines by 217 samples. This image was available only as at-sensor
radiance data. It includes vegetables, bare soils, and vineyard fields.</p>

### Content
Download data from here: 
> * http://www.ehu.eus/ccwintco/uploads/a/a3/Salinas_corrected.mat 
> * http://www.ehu.eus/ccwintco/uploads/f/fa/Salinas_gt.mat

Inspired by [@syamkakarla98](https://github.com/syamkakarla98)
