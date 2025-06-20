# Neural-Object-Detection-4D-STEM

<img src="assets/model.svg" width="600"/>

Repository for automated analysis of 4D-STEM datasets using YOLOv8n. 
This workflow enables an end-to-end processing of large-scale 4D-STEM datasets for phase, orientation, and strain analysis.


<img src="assets/phase.svg" width="600"/>

Phase mapping of complex phase-transformed Ti-50Nb alloy.

<img src="assets/SiGe.svg" width="500"/>

Strain mapping of Si/SiGe multilayers.

## Installation
Please create a new environment
<br>
<br>
Python >= 3.7
<br>
<br>
Install tempo4d
```
pip install tempo4d
```
<br>
<br>
⚠️ Note: By default, `ultralytics` installs the CPU-only version of PyTorch.

If you have a CUDA-capable GPU, we strongly recommend installing a matching version of PyTorch manually after installing `tempo4d`.

See: https://pytorch.org/get-started/locally/
## Demo
![](https://github.com/ArdaGen/Neural-Object-Detection-4D-STEM/blob/main/assets/Media3.gif)

## Cite
```
@misc{genc2025neuralobjectdetection4d,
      title={Neural Object Detection for 4D STEM: High-Throughput Sub-Pixel Electron Diffraction Pattern Recognition}, 
      author={Arda Genc and Ravit Silverstein},
      year={2025},
      eprint={2506.04477},
      archivePrefix={arXiv},
      primaryClass={cond-mat.mtrl-sci},
      url={https://arxiv.org/abs/2506.04477}, 
}

```
