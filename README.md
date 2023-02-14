# MOT_yolov8

### Setup
```
pip install -r requirements.txt
```


### Run code
```
python track.py --yolo-weights yolov8n.pt --tracking-method strongsort \
--source video_path.mp4 \
--reid-weights osnet_x0_25_market1501.pt \
--save-txt \
--save-vid
```

Output Video Save at "runs\tracks" dir
