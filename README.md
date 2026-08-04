# Triton-Ascend 课程视频转录

昇腾社区 Triton 系列课程视频的语音转录文本。使用 whisper-cpp (large-v3) 转录，经 Obsidian 知识库术语修正。

## 课程列表

| # | 课程 | 视频链接 | 转录 | 字幕 |
|:--:|------|------|:--:|:--:|
| 01 | 面向昇腾Triton算子开发（初级） | [🔗](https://www.hiascend.com/developer/courses/detail/1998217338603737090) | ✅ | ✅ |
| 02 | 【先锋计划】Triton-Ascend算子开发介绍 | [🔗](https://www.hiascend.com/developer/courses/detail/2071845112954408961) | ✅ | ✅ |
| 03 | 面向昇腾Triton算子开发（进阶） | [🔗](https://www.hiascend.com/developer/courses/detail/2044691037452255234) | ✅ | ✅ |
| 04 | 【码力全开特辑】全流程掌握Triton算子开发 | [🔗](https://www.hiascend.com/developer/courses/detail/2056932020583751682) | ✅ | ✅ |
| 05 | 【码力全开特辑】代码架构及功能扩展全解析 | [🔗](https://www.hiascend.com/developer/courses/detail/2059206542540251137) | ✅ | ✅ |
| 06 | 【码力全开特辑】调试和性能优化 | [🔗](https://www.hiascend.com/developer/courses/detail/2057646310697541634) | ✅ | ✅ |
| 07 | Triton昇腾亲和扩展编程实践 | [🔗](https://www.hiascend.com/developer/courses/detail/2061700710588108802) | ✅ | ✅ |
| 08 | Triton-TLE面向昇腾的扩展与优化 | [🔗](https://www.hiascend.com/developer/courses/detail/2065276409307607041) | ✅ | ✅ |

## 文件说明

| 目录/文件 | 内容 |
|------|------|
| `transcripts/` | 8 个视频的转录文本 (.txt) + 字幕 (.srt) |
| `courses_data.json` | 课程元数据 (ID, m3u8 URL) |
| `ALL_VIDEOS.txt` | 原始下载链接 |

## 转录工具

- 框架：universal-video-extractor (whisper-cpp + ffmpeg)
- 模型：ggml-large-v3-turbo.bin
- 术语修正：基于 Obsidian 知识库（毕昇、CANN、昇腾、MLIR、AICore 等）

## 来源

所有视频来自 [昇腾社区 Triton 课程](https://www.hiascend.com/developer/courses/)
