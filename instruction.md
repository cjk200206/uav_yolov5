* track: ` python track.py --yolo_weights exp13-20230215T155309Z-001/exp13/weights/best.pt --show-vid --source 1.1.8.mp4 --save-vid --img-size 1280 `
* train: ` python detect.py --source D:\Detection_Models\yolo_v5_detection\yolov5_strongSORT_v3.0\Yolov5_StrongSORT_OSNet-3.0\1.1.1.mov --weights D:\Dete
ction_Models\yolo_v5_detection\yolov5_strongSORT_v3.0\Yolov5_StrongSORT_OSNet-3.0\exp13-20230215T155309Z-001\exp13\weights\best.pt --img-size 1280 --view-img
`
* python train.py  --batch 6 --epoch 200 --data ../uav_person/uav_person.yaml  --cfg models/uav5s.yaml --weights weights/best.pt
* train: `python train.py  --batch 6 --epoch 200 --data ../uav_person/uav_person.yaml  --cfg models/uav5s.yaml --weights weights/uav5s.pt`