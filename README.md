# SenseVoice-Small 语音识别  SenseVoice-Small 多语种语音识别模型（ONNX）。HiTi 仅内置最基础模型，此仓库提供按需下载的高阶模型。  ## 下载（每个变体单独一个资产）  | 变体 | 体积 | 直接下载 | | --- | --- | --- |
| int4 | 144.2 MB | [sensevoice-small-int4.zip](upload sensevoice-small-int4.zip -> hiti-model-sensevoice (144.2 MB)   ok https://github.com/xixi3548942758-design/hiti-model-sensevoice/releases/download/v1.0/sensevoice-small-int4.zip https://github.com/xixi3548942758-design/hiti-model-sensevoice/releases/download/v1.0/sensevoice-small-int4.zip) |
| int8 | 230.2 MB | [sensevoice-small-int8.zip](upload sensevoice-small-int8.zip -> hiti-model-sensevoice (230.2 MB)   ok https://github.com/xixi3548942758-design/hiti-model-sensevoice/releases/download/v1.0/sensevoice-small-int8.zip https://github.com/xixi3548942758-design/hiti-model-sensevoice/releases/download/v1.0/sensevoice-small-int8.zip) |

## 目录结构

解压后与 HiTi `AI_model` 下同名目录一致，直接放入即可：

```
SenseVoice_Small/
  sensevoice-small-int4.onnx 或 sensevoice-small-int8.onnx
  am.mvn  meta.json  tokens.json
```

模型来源：PaddlePaddle / SenseVoice / BEATs 官方发布，仅做 ONNX 量化转换，遵循各自原始许可证。