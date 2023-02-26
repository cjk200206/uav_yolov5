* track: ` python track.py --yolo_weights yolov5/weights/colab1400.pt --show-vid --source 1.1.8.mp4 --save-vid --img-size 1280 `
* detect: ` python detect.py --source ../1.1.8.mp4 --weights weights/colab1400.pt --img-size 1280 --view-img
`
* train: `python train.py  --batch 6 --epoch 200 --data ../uav_person/uav_person.yaml  --cfg models/uav5s.yaml --weights weights/uav5s.pt`