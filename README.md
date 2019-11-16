# FusionDN

This is the code of the following paper (tensorflow):<br>
*FusionDN: A Unified Densely Connected Network for Image Fusion*


## Framework:<br>
 Overall procedure:<br>
<div align=center><img src="https://github.com/hanna-xu/FusionDN/blob/master/imgs/procedure.jpg" width="440" height="290"/></div><br>

Intuitive description of data flow and the process of EWC:<br>
<div align=center><img src="https://github.com/hanna-xu/FusionDN/blob/master/imgs/MultiTask.jpg" width="510" height="200"/></div><br>

## Fused results:<br>
<div align=center><img src="https://github.com/hanna-xu/FusionDN/blob/master/imgs/res1.jpg" width="900" height="490"/></div>
<div align=center><img src="https://github.com/hanna-xu/FusionDN/blob/master/imgs/res2.jpg" width="900" height="400"/></div>

## To train:<br>
CUDA_VISIBLE_DEVICES=0,1 python main.py (2 GPUs are needed)<br><br>

## To test:<br>
CUDA_VISIBLE_DEVICES=0 python test_main.py<br><br>

## Tips:<br>
Large files for training can be downloaded from [*here*](https://pan.baidu.com/s/1S1MKc3XdoICoSg6H33CPZw), including the following files: <br>
### For training:<br>
* Training dataset<br>
* vgg16<br>

### For testing:<br>
* Trained model
