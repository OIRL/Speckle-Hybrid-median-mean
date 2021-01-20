## Hybrid Median-mean method to reduce speckle noise
### Fast and powerful denoising strategy for reducing the speckle noise. 

We present a single-shot computational method based on the use of a hybrid median-mean approach for reducing the speckle noise. The proposed method can be applied to both amplitude and phase reconstructed images. This method is based on the combination of multiple median-filtered images with different kernel sizes. Because, for each median-filtered image the speckle position changes, the average of these median-filtered images results in a final image with low speckle contrast and no resolution decrease (e.g., no blurring effect introduced by the median filter). The proposed method has been evaluated experimentally in digital holography and digital holographic microscopy. 

<p align="center">
<img src="Images/die.png" alt="hi" class="inline" width="528" height="300"/>
</p>


### Python script
The **hybrid median-mean method** is available as script for Python. The function have five parameters: 
- **image**: Corresponds to the noise image 
- **max_kernel_size**: The maximun dimension of the kernel, this number must be odd 
- **figures**: Allow to show the original/noise image (named as *image*) and the denoising image after applied the hybrid median-mean approach; Figures has two options: *True* for displaying both images or *False* for not displaying  
- **plots**: Allow to select a square region to measure/quantify the speckle contrast and plot the speckle contrast vs number of iterations; Plots has two options *True* or *False*
- **save_image**: Allow to save the final denoising image; Save_images has two options *True* or *False*

 Below an example of how to operate with the hibrid median-mean script for python
 
```markdown
# import library
import HMM_UofM

# call the function HHM_UofM.HMM
HMM_UofM.HMM(image, max_kernel_size, figures='True', plots ='True', save_image='True')
```


### Citation
* If using blind three raws holograms algorithm for publication, please kindly cite the following:

 R. Castaneda, Garcia-Sucerquia and A. Doblas, “Speckle Noise Reduction in Digital Holography via a Hybrid Median-Mean Approach,” Appl. Opt. XX, XX, p.p XXX–XXX (2021)[Article](https://).

### Support or Contact

| Researcher  | email | Google Scholar | ResearchGate |
| ------------- | ------------- |-------------| -------------|
| Raul Castaneda | *rcstdq@memphis.edu* | [RaulGoogle](https://scholar.google.com/citations?user=RBtkL1oAAAAJ&hl=en) | [RaulResearch](https://www.researchgate.net/profile/Raul_Castaneda_Quintero)
| Ana Doblas| *adoblas@memphis.edu* | [AnaGoogle](https://scholar.google.es/citations?user=PvvDEMYAAAAJ&hl=en) | [AnaResearch](https://www.researchgate.net/profile/Ana_Doblas2) |

The main researcher of Speckle reduction Hybrid Median-mean project is Ana Doblas 
