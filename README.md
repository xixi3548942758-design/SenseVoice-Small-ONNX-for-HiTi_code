# SenseVoice-Small 语音识别 · ONNX

上游模型权重的 ONNX 转换分发，供 HiTi_code 的「设置 → 本地模型」页按需下载。**非官方渠道**，与上游项目及 HiTi_code 项目均无隶属关系。

- 上游：<https://github.com/FunAudioLLM/SenseVoice>
- 模型卡：<https://huggingface.co/FunAudioLLM/SenseVoiceSmall>
- 许可证：FunASR Model Open Source License Agreement v1.1，全文见 LICENSE-FUNASR-MODEL.txt；权利归属与修改说明见 NOTICE.md

## 下载

每个变体单独一个资产，只下要用的那一档：

| 变体 | 体积 | 直接下载 |
| --- | --- | --- |
| int4 | 144.2 MB | [sensevoice-small-int4.zip](https://github.com/xixi3548942758-design/SenseVoice-Small-ONNX-for-HiTi_code/releases/download/v1.0/sensevoice-small-int4.zip) |
| int8 | 230.2 MB | [sensevoice-small-int8.zip](https://github.com/xixi3548942758-design/SenseVoice-Small-ONNX-for-HiTi_code/releases/download/v1.0/sensevoice-small-int8.zip) |

## 目录结构

解压后目录名与 HiTi 的 AI_model 目录下同名目录一致，直接放进去即可：

```
SenseVoice_Small/
  sensevoice-small-int4.onnx 或 sensevoice-small-int8.onnx
  am.mvn  meta.json  tokens.json
```

## 使用与再分发

- 同一模型的不同量化档（int4 / int8）只选一个放进目录，不要同时放。
- 再分发时必须保留 LICENSE 与 NOTICE.md，保留模型名称，并注明上游出处。
