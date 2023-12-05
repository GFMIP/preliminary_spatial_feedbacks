# Preliminary Spatial Feedbacks used to help develop the GFMIP protocol

## About

This repository contains the spatial feedbacks from Figure 2 of the [GFMIP protocol paper](https://essopenarchive.org/users/554553/articles/627762-the-green-s-function-model-intercomparison-project-gfmip-protocol) (referred to there as normalized derivatives of global-mean net top-of-atmosphere radiative flux, N). These feedbacks are only preliminary results used to help design the GFMIP protocol, and should be used with this in mind. 

Each model has its own NetCDF file in the data directory. For models with feedbacks estimated using both warming and cooling perturbations, there are three variables (warming, cooling, and both); otherwise only the feedbacks from warming are given. Values are normalized by grid-cell in such a way that feedback values are intensive, rather than extensive (i.e., the value in a grid cell shows what the ocean-mean feedback would be if all other cells had the same feedback as that grid cell). For more info, see the Appendix in the paper.

## Data

| Model | Patch Layout | Warming | Cooling | Both | Source |
| ----------- |  ----------- | ----------- | ----------- | ----------- | ----------- |
| CAM5 | Zhou et al. | +2K | -2K | ±2K | C. Zhou |
| CanESM5 | Zhou et al. | +4K | -4K | ±4K | J. Cole |
| HadAM3 | Zhou et al./equal area hybrid | +2K | -2K | ±2K | J. Bloch-Johnson & J. Gregory |
| CAM4 | Dong et al. | +1.5K (+3K in high latitudes; see [Dong et al. 2019](https://journals.ametsoc.org/view/journals/clim/32/17/jcli-d-18-0843.1.xml)) | NA | NA | Y. Dong |
| GFDL-AM4 | Dong et al. | +4K | -4K | ±4K | B. Zhang and M. Zhao |
| ECHAM6 | Equal area | +4K | -4K | ±4K | M. Alessi & M. Rugenstein |
| HadAM3 | Dong et al. shifted/equal area hybrid | +2K | -2K | ±2K | J. Bloch-Johnson & J. Gregory |


## How to cite

If you use this data, please cite the [GFMIP protocol preprint](https://essopenarchive.org/users/554553/articles/627762-the-green-s-function-model-intercomparison-project-gfmip-protocol), and the following papers if you use the specific models listed:

- CAM5: [Zhou et al. 2017](https://agupubs.onlinelibrary.wiley.com/doi/10.1002/2017MS001096)
- CAM4: [Dong et al. 2019](https://journals.ametsoc.org/view/journals/clim/32/17/jcli-d-18-0843.1.xml)
- GFDL-AM4: [Zhang et al. 2023](https://journals.ametsoc.org/view/journals/clim/36/4/JCLI-D-22-0024.1.xml)
- ECHAM6: [Alessi and Rugenstein 2023](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2023GL105795)

## Questions?

If you have any questions about this data, please contact the GFMIP organizers at gfmip.organizers@gmail.com. Thanks!