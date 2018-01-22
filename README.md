
## Steps:

  - Pull the repo - https://github.com/tensorflow/models
  - Navigate to models/research and run export PYTHONPATH=$PYTHONPATH:`pwd`:`pwd`/slim
  - Run protoc object_detection/protos/*.proto --python_out=.
  - Resources:
    - Model zoo - https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md
    - configs - https://github.com/tensorflow/models/tree/master/research/object_detection/samples/configs
