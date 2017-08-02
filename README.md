## Brief Introduction :
<img src="https://github.com/feifeibear/SWCaffe/blob/master/swdnnlogo.png" width = "300" height = "200" alt="swdnnlogo" align=center />
This is convolutional layer routines customized for chinese homemade Sunway TaihuLight supercomputer.
The latest swDNN code has been move to our SWCaffe repo

test interfaces : https://github.com/feifeibear/SWCaffe/tree/master/swdnn_test   
source code : https://github.com/feifeibear/SWCaffe/tree/master/src/swlayers

This repo still contains orignal source code for the paper published on IPDPS 2017
please ref : Fang J, Fu H, Zhao W, et al. swDNN: A Library for Accelerating Deep Learning Applications on Sunway TaihuLight[C]//Parallel and Distributed Processing Symposium (IPDPS), 2017 IEEE International. IEEE, 2017: 615-624.

### swCNNv11~14
which contain unitest code for forward propagation with four different loop transformations.

### swCNNv21
which contains a conplete conv layer implementaion with gradient updating for forward and backward propagation.

please forgive us for our bad indentation, because we wrote the code on TaihuLight Server with a raw vim congfiguration.

### contact
Jiarui Fang
fang_jiarui@163.com
Wenlai Zhao
cryinlaugh@126.com
