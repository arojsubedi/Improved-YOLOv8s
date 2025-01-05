# Improved YOLOv8s Object Detection Algorithm

Detailed explanation: 
https://arxiv.org/abs/2412.14211

BibTex Citation: 
```
@misc{subedi2024improvinggeneralizationperformanceyolov8,
      title={Improving Generalization Performance of YOLOv8 for Camera Trap Object Detection}, 
      author={Aroj Subedi},
      year={2024},
      eprint={2412.14211},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2412.14211}, 
}
```

The baseline YOLOv8s model has been improved with the integration of Global Attention Mechanism (GAM), Modified Neck, and Wise Intersection over Union (WIoUv3).


1. WIoUv3 integration is present in the following files: ultralytics/nn/utils/loss.py, ultralytics/nn/utils/metrics.py, ultralytics/nn/utils/tal.py

2. Global Attention Mechanism (GAM) module is present in the : ultralytics/nn/modules/attention.py

3. Additional changes to incorporate files are present in: ultralytics/nn/modules/__init__.py

4. Additional changes to facilitate operations are present in: ultralytics/nn/tasks.py

5. YAML source file: ultralytics/cfg/models/v8/yolov8-GAM-Attention.yaml


Please reach out to me at arojsubedi@gmail.com if you need any help with this repository.
