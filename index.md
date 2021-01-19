## Speckle reduction Hybrid Median-mean method
### Fast and powerful denoising strategy for reducing the speckle noise. 

We present a single-shot computational method based on the use of a hybrid median-mean approach for reducing the spckle noise. The implementation allow for reconstructed amplitude and phase images trought the combination of the mean for several median filter of different neighborhoods around each pixel on the input image (e.g., different kernel sizes). Because, for each median filter, images with varying positions of speckle are generated, the average of the median-filtered images, taken between two consecutive kernel sizes, results in a final image with low speckle contrast in which the reduction in the spatial resolution introduced by the median filter has been addressed (e.g., no blurring). The proposed method has been evaluated in different experimental images in digital holography and digital holographic microscopy. 

<p align="center">
<img src="images/die.png" alt="hi" class="inline"/>
</p>


### Python script
The Hybrid median-mean is available as XXXXX for python. The function have five parameters: 
- sample: Corresponds to the noise image 
- max_kernel_size: the maximun dimension of the kernel, this number must be odd 
- figures: allow to show the original image and the denoising image after applied the hybrid median-mean aproache; could be True or False 
- plots: allow to selec a squuare region to measire the speckle contrast and show the plot speckle contras vs number of iterations; could be True or False
- save_images: using this parameter to save the final denoising image; could be true or false

 Below an example of how to operate with the hibrid median-mean script for python
 
```markdown
# import library
import HMM_UofM

# call de function HHM_UofM.HMM
HMM_UofM.HMM(sample, max_kernel_size, figures='True', plots_true='True', save_images='True')
```

### Matlab script 
```markdown

```

### Citation
* If using blind three raws holograms algorithm for publication, please kindly cite the following:

 R. Castaneda, Garcia-Sucerquia and A. Doblas, “Speckle Noise Reduction in Digital Holography via a Hybrid Median-Mean Approach,” Appl. Opt. XX, XX, p.p XXX–XXX (2021)[Article](https://).

### Support or Contact

| Researcher  | email | Google Scholar | ResearchGate |
| ------------- | ------------- |-------------| -------------|
| Raul Castaneda | *rcstdq@memphis.edu* | [RaulGoogle](https://scholar.google.com/citations?user=RBtkL1oAAAAJ&hl=en) | [RaulResearch](https://www.researchgate.net/profile/Raul_Castaneda_Quintero)
| Ana Doblas| *adoblas@memphis.edu* | [AnaGoogle](https://scholar.google.es/citations?user=PvvDEMYAAAAJ&hl=en) | [AnaResearch](https://www.researchgate.net/profile/Ana_Doblas2) |

The main research of Speckle reduction Hybrid Median-mean project is Ana Doblas 
