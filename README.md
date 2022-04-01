# yolo-help-yolo
use model trained with yolov5 to label data for training yolov5

### generate label file with command
```bash
python detect.py --weights weights/best.pt  --source val --save-txt
```
will generate label files in dir `labels`
