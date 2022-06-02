# tensorflow-lite-yolo-v3

Convert the weights of YOLO v3 object detector into tensorflow lite format. It can be served for tensorflow serving as well.

Optional Flags

convert_weights_pb.py:

--class_names
    Path to the class names file
--weights_file
    Path to the desired weights file    
--data_format
    `NCHW` (gpu only) or `NHWC`
--tiny
    Use yolov3-tiny
--spp
    Use yolov3-spp
--output_graph
    Location to write the output .pb graph


