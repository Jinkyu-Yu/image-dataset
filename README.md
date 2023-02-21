# Image-dataset
Image dataset for semiconductor images.
We collected 164 defective images from literature.
We divided the 164 defective images into 148 training dataset and 16 validation dataset.
We also added 16 corresponding defect-free images generated by the exemplar-based inpainting method [1].
We obtained a total of $148\times2\times8=2,368$ defective images by applying data augmentation strategies such as complement, rotations($\pi/2$, $\pi$, $3\pi/2$), and flipping.


Reference

[1] A. CRIMINISI, P. PEREZ, AND K. TOYAMA, Region filling and object removal by exemplar-based image
inpainting, IEEE Transactions on Image Processing, 13 (2004), pp. 1200–1212.
