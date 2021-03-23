# exportMobileNet_SSDSeries
Export MobileNet_SSD series from Google [Object Detection ZOO](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1_detection_zoo.md)  
## Setup Station(Google Object Detection API)
Download the tensorflow/models repository
## Only download operation
* MobileNetV1+SSDLite
* MobileNetV2+SSDLite
## Export operation  
【Note】:The following three models(training results) on the official website cannot be used directly, you need to export `frozen_inference_graph.pb` yourself 
* MobileNetV3_Small+SSDLite
* MobileNetV3_Large+SSDLite
* MobileDet_CPU+SSDLite 
## Exported file structure  
    expoted_MobileNet*_SSDLite
```
.
├── checkpoint
├── frozen_inference_graph.pb
├── model.ckpt.data-00000-of-00001
├── model.ckpt.index
├── model.ckpt.meta
├── pipeline.config
└── saved_model
    ├── saved_model.pb
    └── variables
 ```

