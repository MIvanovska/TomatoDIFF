# TomatoDIFF
Official implementation of the paper "TomatoDIFF: On–plant Tomato Segmentation with Denoising Diffusion Models" [^1].
TomatoDIFF is a diffusion-based model developed for semantic segmentation of on-plant tomatoes. 

![TomatoDIFF](TomatoDIFF.png)

For more information please refer to the paper available [here]().

## 1. Install the dependencies
The model is implemented using PyTorch. The full list of used libraries can be found in requirements.txt.
```
pip install -r requirements.txt
```

## 5. Citing TomatoDIFF
If you find this code useful or you want to refer to the paper, please cite using the following BibTeX:
```
@INPROCEEDINGS{ivanovska2023TomatoDIFF,
  author={Ivanovska, Marija and Perš, Janez and Štruc, Vitomir},
  booktitle={2023 18th International Conference on Machine Vision and Applications (MVA)}, 
  title={TomatoDIFF: On–plant Tomato Segmentation with Denoising Diffusion Models}, 
  year={2023}}
```

## Acknowledgements
This code is based on [k-diffusion](https://github.com/crowsonkb/k-diffusion).

## References
[^1]: M. Ivanovska, J. Perš, V. Štruc, TomatoDIFF: On–plant Tomato Segmentation with Denoising Diffusion Models, International Conference on Machine Vision Applications (MVA), 2023
