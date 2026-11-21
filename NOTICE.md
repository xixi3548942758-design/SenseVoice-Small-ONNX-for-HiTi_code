# NOTICE / 第三方声明

本仓库提供的是 SenseVoice-Small 语音识别 的上游模型权重的 ONNX 转换分发，供 HiTi_code 的「设置 → 本地模型」按需下载。

## 上游来源

- 项目：https://github.com/FunAudioLLM/SenseVoice
- 模型卡：https://huggingface.co/FunAudioLLM/SenseVoiceSmall
- 许可证：FunASR Model Open Source License Agreement v1.1，全文见 LICENSE-FUNASR-MODEL.txt

## 本仓库所做的修改

- 将上游权重导出为 ONNX 计算图，并做 int4 / int8 量化（不同变体分属不同资产）
- 随包附带上游原有的词表与配置等元数据
- 未对权重重新训练或微调，未改变模型结构与用途

## 权利归属

上游模型权重的著作权归原作者及原权利人所有。本仓库仅做格式转换与分发，不主张对上游权重的任何权利；如权利人要求，将立即下架。

本仓库与上游项目、与 HiTi_code 项目均无隶属或官方授权关系，不是官方发布渠道。