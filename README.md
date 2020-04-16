# keras_onnx_tx2

Convert keras .h5 file to onnx and deploy it on Nvidia Jetson Tx2

Convert .h5 to .onnx

#python yolov3_to_onnx.py --model yolo-tiny-416 

Convert .onnx to .trt

#python onnx_to_trt.py --model yolo-tiny-416


Inference with .trt model


#python inference.py


Convert .h5 to .weights


#python h5_to_weights.py
