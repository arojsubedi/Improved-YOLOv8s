# Improved YOLOv8s Object Detection Algorithm
The baseline YOLOv8s model has been improved with the integration of Global Attention Mechanism (GAM), Modified Neck, and Wise Intersection over Union (WIoUv3).


1. WIoUv3 integration is present in the following files: ultralytics/nn/utils/loss.py, ultralytics/nn/utils/metrics.py, ultralytics/nn/utils/tal.py

2. Global Attention Mechanism (GAM) module is present in the : ultralytics/nn/modules/attention.py

3. Additional changes to incorporate files are present in: ultralytics/nn/modules/__init__.py

4. Additional changes to facilitate operations are present in: ultralytics/nn/tasks.py

5. YAML source file: ultralytics/cfg/models/v8/yolov8-GAM-Attention.yaml


Please reach out to me at arojsubedi@gmail.com if you need any help with this repository.
