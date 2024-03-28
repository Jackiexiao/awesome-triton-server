# awesome-triton-server
Awesome Triton Server Examples &amp; Tools &amp; UI

## Client
- [triton-service-go](https://github.com/sunhailin-Leo/triton-service-go)

## UI
- [triton-inference-server-web-ui](https://github.com/duydvu/triton-inference-server-web-ui): Manage and monitor your Triton Inference Server with a web browser. 

## Serve with Other Language
- [echo-grpc-triton](https://github.com/Curt-Park/echo-grpc-triton) : Inference API server with echo and gRPC to triton server (golang)
- [django_ai_server_template](https://github.com/Bobo-y/django_ai_server_template)

## Examples
- [Wenet ASR](https://github.com/wenet-e2e/wenet/tree/main/runtime/gpu)
- [Wetts TTS](https://github.com/wenet-e2e/wetts/tree/main/runtime/gpu_triton)
- [Deploying Text Detection Model with Triton Inference Server](https://github.com/protonx-mles-03/minh-triton-server)
- [yolov5-triton](https://github.com/MACNICA-CLAVIS-NV/yolov5-triton)
- [Triton_Inference_Server_Streaming_Demo](https://github.com/AI796/Triton_Inference_Server_Streaming_Demo)

## Easier Triton
- [tritony - Tiny configuration for Triton Inference Server](https://github.com/rtzr/tritony) Easier Start Point of Triton Server
- [triton_cli](https://github.com/triton-inference-server/triton_cli): Triton CLI is an open source command line interface that enables users to create, deploy, and profile models served by the Triton Inference Server.
- [pyotritonclient](https://github.com/oeway/pyotritonclient): A warpper of python tritonclient

## Custom Images
- CPU
  - base
    - jackiexiao/tritonserver:24.03-onnx-py-cpu
  - onnx-share-session
    - jackiexiao/tritonserver:24.03-onnx-py-cpu-share-session
- GPU
  - onnx-share-session
    - jackiexiao/tritonserver:24.03-py3-onnx-share-session
