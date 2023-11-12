# yolov5_dual_weighting
Inspired by "A Dual Weighting Label Assignment Scheme for Object Detection" published by Shuai Li et al. in CVPR 2022 (doi: https://doi.org/10.48550/arXiv.2203.09730) and official yolov5 detector (https://github.com/ultralytics/yolov5) , I tried to combine the official yolov5 project with the training strategy of dual weighting label assignment for exploring the detector performance of using the strategy.

## Statement
See ```./utils/loss.py``` or ```./utils/loss_dw.py``` for the details of the strategy implementation. I have not completed the COCO benchmark testing owing to busyness, but in my project, the performance seems good. In future, I will conduct it and upload some results. And welcome to test it for accurate performance.

## Acknowledgements
https://github.com/ultralytics/yolov5 (offcial yolov5 project, please see it for full official project)
https://github.com/strongwolf/DW (code of "A Dual Weighting Label Assignment Scheme for Object Detection", see it for the details)
https://doi.org/10.48550/arXiv.2203.09730 (read more about "A Dual Weighting Label Assignment Scheme for Object Detection")

## Further
Any problems about this, welcome to communicate with me.
Email: chenjisen123@foxmail.com

