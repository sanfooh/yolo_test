# yolo_test
this is a test

start train
./darknet detector train work/cfg/obj.data work/cfg/YOLO-obj.cfg work/darknet19_448.conv.23
continue train
./darknet detector train work/cfg/obj.data work/cfg/YOLO-obj.cfg work/yolo-obj_700.weights
test image
./darknet detector test work/cfg/obj.data work/cfg/YOLO-obj.cfg work/yolo-obj_700.weights test/testimage.jpg

