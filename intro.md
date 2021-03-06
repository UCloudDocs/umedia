# 产品简介



## 概述

媒体工厂服务UMedia(UCloud Media
Factory)能够为用户提供丰富的多媒体处理功能，比如视频转码、水印、截图、切片以及鉴黄等。帮助用户提高视频处理效率，适用于传统音视频网站、UGC用户原创视频平台、PGC视频平台、在线教育等多种场景。

## 功能介绍

### 转码

转码指将输入的视频文件按照指定的码率、分辨率等参数进行转换，并输出指定格式的文件。

支持URL输入，可同时提交多条URL，支持转码参数自定义。

### 水印

支持在输出的视频上覆盖水印静态文字或图像。水印图片支持URL输入。

### 截图

支持时间点截图、时间间隔截图和GIF截图三种方式。

时间点截图是指输入的一个或多个视频文件都在用户指定的一个时间点进行截图作业。

时间间隔截图是指输入的一个或多个视频文件都以指定的时间间隔进行多次截图，第0秒为第一张截图。

GIF截图是指提交的一条或多条URL以指定的图片采集间隔进行图片截取，并以指定播放速度封装为GIF动态图。

### 切片

切片指将输入的视频文件进行切片处理，并输出m3u8格式文件。

### 模版

转码和水印都支持以模版方式进行作业。转码模版分为预置模版和自定义模版。

UMedia按照常见的播放设备及带宽条件为用户准备了3种格式的预置模版供用户参考及选用。用户也可以通过创建自定义模版进行转码参数的自定义，满足用户的个性化转码需求。

水印模版分为文字水印和图片水印。可在提交转码任务时与转码模版进行自由组合。

## 格式支持

### 输入文件格式

文件格式：3gpp, asf/wmv, avi, flv/f4v, mkv, mov/mp4/m4a, mp3, mp2, mpeg/mpg,
ts/ogg, mts, wmv/wma, rm/rmvb, webm等。

视频编码标准：H.265, H.264, H.263/H.263+, MPEG-1/2/4, VP8/9, Quicktime,
RealVideo等。

音频编码标准：MP1, MP2, MP3, AAC, AC-3, WMA, PCM, ADPCM, AMR, RealAudio,
Vorbis等。

### 输出文件格式

转码输出：mp4, flv, mpegts

切片输出：m3u8

mp4为通用视频格式（Android/iOS/PC Web兼容）；

flv为Flash视频格式；

mpegts用于数字电视广播系统，如 DVB、ATSC、IPTV 等等。

视频编码标准：H.264/AVC、H.265/HEVC

## 产品优势

### 极速转码

强大的分布式转码集群，极速的转码体验，保障转码效率和质量。支持主流视频格式转码，支持多码流多格式输出。

### 灵活定制

支持客户自定义转码参数，支持文字、图片水印按需组合，满足客户的个性化需求。

### 存储分发相结合

与对象存储UFile、云分发UCDN配合使用，存储空间无上限，分发加速性能优异，为您解决多媒体数据的存储分发问题。

