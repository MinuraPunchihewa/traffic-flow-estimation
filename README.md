# Traffic-Flow-Estimation

This project aims at estimating traffic flow from CCTV footage. We have trained the YOLOv4 algorithm for the five vehicle classes given below,

* car
* bus
* truck
* van
* bike


We obtained the images through the traffic cameras API, New Zealand Transport Agency (NZTA). The image dataset with the relevant annotation files used to train YOLOv4 is available in the "traffic-detection-dataset" directory. We have trained YOLOv4 with nearly 6,100 vehicle object instances as illustrated in the following table,

| Vehicle Class  | Total Instances |
| ------------- | ------------- |
| Car| 3,627  |
| Bus| 141  |
| Van | 779 |
| Truck | 1,273 |
| Bike | 280 |

Our experimets were carried out for the footage we received from NZTA for a busy multi-lane road in Christchurch CBD. 

![Alt text](traffic.gif)
