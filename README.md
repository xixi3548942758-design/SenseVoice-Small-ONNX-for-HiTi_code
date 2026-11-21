# SenseVoice-Small 语音识别

SenseVoice-Small 多语种语音识别模型（ONNX，int4 / int8 两档量化）。

HiTi 只在内置包里带最基础的那一个模型，其余全部按需下载。本仓库提供「设置 → 本地模型」页里可选的高阶模型，**每个变体单独一个资产，只下你要的那一档**。

## 下载

| 变体 | 体积 | 直接下载 |
| --- | --- | --- |
| int4 | 144.2 MB | [sensevoice-small-int4.zip](https://github.com/xixi3548942758-design/hiti-model-sensevoice/releases/download/v1.0/sensevoice-small-int4.zip) |
| int8 | 230.2 MB | [sensevoice-small-int8.zip](https://github.com/xixi3548942758-design/hiti-model-sensevoice/releases/download/v1.0/sensevoice-small-int8.zip) |

## 目录结构

解压后目录名与 HiTi `AI_model` 下同名目录一致，直接放进去即可：

```
SenseVoice_Small/
  sensevoice-small-int4.onnx 或 sensevoice-small-int8.onnx
  am.mvn  meta.json  tokens.json
```

## 说明

- 同一模型的不同量化档（int4 / int8）只选一个放进目录，不要同时放。
- 原模型由 PaddlePaddle / SenseVoice / BEATs 官方发布，本仓库仅为 ONNX 量化转换后的分发，遵循各自原始许可证。
