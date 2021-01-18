## Speckle reduction Hybrid Median-mean method
### Fast and powerful denoising strategy for reducing the speckle noise. 

We present a single-shot computational method based on the use of a hybrid median-mean approach for reducing the spckle noise. The implementation allow for reconstructed amplitude and phase images trought the combination of the mean for several median filter of different neighborhoods around each pixel on the input image (e.g., different kernel sizes). Because, for each median filter, images with varying positions of speckle are generated, the average of the median-filtered images, taken between two consecutive kernel sizes, results in a final image with low speckle contrast in which the reduction in the spatial resolution introduced by the median filter has been addressed (e.g., no blurring). The proposed method has been evaluated in different experimental images in digital holography and digital holographic microscopy. 
### Markdown

### Citation
* If using blind three raws holograms algorithm for publication, please kindly cite the following:

 R. Castaneda, Garcia-Sucerquia and A. Doblas, “Speckle Noise Reduction in Digital Holography via a Hybrid Median-Mean Approach,” Appl. Opt. XX, XX, p.p XXX–XXX (2021)[Article](https://).

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/OIRL/Speckle-Hybrid-median-mean/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
