# 20200710 Webinar用 TRTIS サンプル
Model Zooで公開されているonnxファイルから作成してTensorRT用エンジンを用いて、TRTISを動かす為のサンプル設定

# 動作確認環境
+ TRTIS
  + OS: Ubuntu18.04.3 LTS
  + GPU: Tesla V100 (16GB)
  + GPU driver: 418.87.01
  + TRTIS container: nvcr.io/nvidia/tritonserver:20.03.1-py3
  
+ TensorRTエンジン作成環境
  + OS: Ubuntu18.04.3 LTS
  + GPU: Tesla V100 (16GB)
  + GPU driver: 418.87.01
  + TensorRT container: nvcr.io/nvidia/tensorrt:20.03-py3

# ディレクトリ構成
+ `model_repository`: TRTIS起動時にモデルリポジトリのrootディレクトリとして指定するディレクトリ
+ `model_repository/ResNet50-FP32`: Resnet50 FP32推論用設定格納ディレクトリ
+ `model_repository/ResNet50-FP16`: Resnet50 FP16推論用設定格納ディレクトリ
+ `model_repository/ResNet50-FP32/1`: Resnet50 FP32推論エンジン格納ディレクトリ
+ `model_repository/ResNet50-FP16/1`: Resnet50 FP16推論エンジン格納ディレクトリ


