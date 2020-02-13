# K-means-img-sorting
Images sorting with K-means
Cluster images, please dont forget to change the directory where the files are uploaded and the where the resized images are saved.
## Images
Sunflower
<p float="left">
  <img src="Images/Sunflower/01814_01_sunrichorangesum.jpg" width="100">
  <img src="Images/Sunflower/20150725-IMG_1442-Edit-2.jpg" width="100">
  <img src="Images/Sunflower/FL3262-1_1024x1024.jpg" width="100">
  <img src="Images/Sunflower/HELI-2989-A_h.jpg" width="100">
  <img src="Images/Sunflower/images%20(1).jpg" width="100">
  <img src="Images/Sunflower/images%20(2).jpg" width="100">
  <img src="Images/Sunflower/images.jpg" width="100">
  <img src="Images/Sunflower/Sunflower-Black-Mammoth-Flower-Annual-Mckenzie-Seeds_1400x.jpg" width="100">
  <img src="Images/Sunflower/Sunflower-Sunspot-Flower-Annual-Mckenzie-Seeds_1400x.jpg" width="100">
  <img src="Images/Sunflower/teddybear_sunflower_500.jpg" width="100">
</p>

Daisy
<p float="left">
  <img src="Images/Daisy/17a5d17b2f30c1ad24b6fd182dc89c59.jpg" width="100">
  <img src="Images/Daisy/4864.jpg" width="100">
  <img src="Images/Daisy/daisy-flower-1532449822.jpg" width="100">
  <img src="Images/Daisy/download%20(1).jpg" width="100">
  <img src="Images/Daisy/download%20(2).jpg" width="100">
  <img src="Images/Daisy/download.jpg" width="100">
  <img src="Images/Daisy/GettyImages-1004261968-5b8d9cb946e0fb0025f5f51b.jpg" width="100">
  <img src="Images/Daisy/Leucanthemum_vulgare_'Filigran'_Flower_2200px.jpg" width="100">
  <img src="Images/Daisy/photo-1508784411316-02b8cd4d3a3a.jpg" width="100">
  <img src="Images/Daisy/photo-1511800542034-c083297cdf56.jpg" width="100">
</p>

Roses
<p float="left">
  <img src="Images/Roses/7e0a3d_3ea91341d6814d1781b0a29b14ba85cc_mv2.jpg" width="100">
  <img src="Images/Roses/12-red-roses-korean-style-2607195390065_600x.jpg" width="100">
  <img src="Images/Roses/81oU3AvHlDL._SL1500_.jpg" width="100">
  <img src="Images/Roses/817dHAFMjFL._SL1500_.jpg" width="100">
  <img src="Images/Roses/51269296-three-dark-red-roses-isolated-on-white.jpg" width="100">
  <img src="Images/Roses/globalrose-flower-bouquets-50-red-roses-vd-64_1000.jpg" width="100">
  <img src="Images/Roses/images%20(1).jpg" width="100">
  <img src="Images/Roses/images.jpg" width="100">
  <img src="Images/Roses/imageService.jpg" width="100">
  <img src="Images/Roses/photo-1537454959372-885b35677ef5.jpg" width="100">
</p>

## Result
1) Three centroids are chosen since there are three different type of flowers.

2) The initial values for the 3 centroids are randomly chosen from the 30 images of flowers.

3) The model is run for 100 times with each time the values for the 3 centroids chosen randomly.

4) At each run, the iteration is carried out 10 times to find the optimum sum square diffrence between the images and centroids.

5) The number of iteratiosn required to reach optimality is tracked using variable "*itrlist*".

6) The sum difference of the optimimum distance of all images to its centroids is tracked using variabe "*errlist*".

The table below show the values of the key criterias that were tracked and calculated.

| Criteria | itrlist | errlist|
| --- | --- | --- |
| Min | 1 | 111126 |
| Max | 9 | 124831 |
| Average | 2.69 | 116300.95 |
| Standard Deviation | 1.37 | 3103.11 |

The optimum classification for the images are shown in the figures below:

Class 1

<img src="Images/Result/Class1.png" width="500">

Class 2

<img src="Images/Result/Class2.png" width="500">

Class 3

<img src="Images/Result/Class3.png" width="500">

