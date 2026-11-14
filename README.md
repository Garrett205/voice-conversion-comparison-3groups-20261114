# 三组歌声转换对照试听

[在线试听](https://garrett205.github.io/voice-conversion-comparison-3groups-20261114/)

2026-11-14。M01（男→男）、M19（男→女）、M37（女→男），每组包含源歌声、目标参考，以及 FreeSVC、OpenVoice v2、Seed-VC、带 MIDI、本文无 MIDI 五种输出，共 21 条音频。

Seed-VC 为官方 44.1kHz 歌声权重的自定义流式适配：当前块 320ms、左历史最多 1280ms、右预览 260ms、3 步采样、CFG 0.7、fp16，未额外移调；拼接采用移植的 SOLA 对齐搜索与交叉渐变。它不是官方原生实时模型的结果。FreeSVC、OpenVoice v2 按整句离线运行；两种本文方案采用自动音区对齐。

选择依据：从已有候选池按编号取上述三个方向的首组，不按输出分数筛选。本次仅发布已有音频，未重新推理、剪裁、转码或调整音量。来源为 OpenSinger、GTSinger-Chinese、M4Singer 的现有实验片段；各录音及模型的权利归原权利人，本仓库不重新授予音频许可。

文件清单、时长和 SHA256 见 samples.json。本页用于试听核对，不构成人工 MOS / SMOS 统计。
