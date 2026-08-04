# Triton-Ascend 课程视频转录

昇腾社区 Triton 系列课程视频的语音转录文本。

## 来源

视频来自 [昇腾社区 Triton 课程](https://www.hiascend.com/developer/courses/)，使用 whisper-cpp (large-v3) 转录。

## 文件说明

| 目录 | 内容 |
|------|------|
| `transcripts/` | 8 个视频的转录文本 (.txt) + 字幕 (.srt) |
| `courses_data.json` | 课程元数据 (ID, m3u8 URL) |
| `ALL_VIDEOS.txt` | 下载链接清单 |

## 课程列表

| # | 课程 | 大小 | 状态 |
|:--:|------|------|:--:|
| 01 | Triton初级 | 10.6KB | ✅ |
| 02 | Triton先锋计划 | 23.1KB | ✅ |
| 03 | Triton进阶 | 13.7KB | ✅ |
| 04 | Triton码力全开_基础 | 57.5KB | ✅ |
| 05 | Triton码力全开_代码架构 | 42.0KB | ✅ |
| 06 | Triton码力全开_调试 | 51.4KB | ✅ |
| 07 | Triton亲和扩展 | 43.7KB | ✅ |
| 08 | Triton_TLE | 32.9KB | ✅ |

## 转录工具

- 框架: universal-video-extractor (whisper-cpp + ffmpeg)
- 模型: ggml-large-v3-turbo.bin
- 位置: /Users/liuwei/hermes-workspace/hiascend_triton_courses/videos/ (原始 mp4)
- 转录脚本: /Users/liuwei/hermes-workspace/hiascend_triton_courses/download.sh
