# BEV-Segment
BEV detection project segments drivable area, lane edge and middle line in the BEV image generated from 4 carla fisheye cameras. Here are some results of the BEV segmentation. The green area is the drivable area, the red is the lane edge, and the yellow is middle line.

<div style="display:inline-block">
  <img src="doc/ret1.PNG" alt="image1", width="200">
  <img src="doc/ret2.PNG" alt="image2", width="200">
  <img src="doc/ret3.PNG" alt="image3", width="200">
</div>

# Get Started
1. install dependency, refer to [README-origin.md](README-origin.md)
2. run the inference.
```shell
activate conda virtual environment
python3 predict.py
```


