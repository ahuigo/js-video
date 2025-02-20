# player
> 协议参考：post/video/im-live-protocol.md

## 视频编码
    # 不同编码的MP4文件
    MP4 : H.265视频 + Opus音频 → 高效压缩方案
    MP4 : VP9视频   + AAC音频 → YouTube部分视频
    # H.264的其他容器
    H.264视频 + AAC音频 → AVI/MKV/FLV 等容器

## 播放器demo
1. mp4.html 只支持mp4
2. video.html 支持m3u8, both HLS and MPEG-DASH 
    基于 https://github.com/videojs/http-streaming#installation
2. hls.html 只支持m3u8
3. h.264.html 视频播放
3. 其它播放器demo大全:
    https://github.com/ahuigo/js-video-demos
4. flv 播放器(不常用了)
    https://bilibili.github.io/flv.js/demo/

## HLS(m3u8)实现
- demo: https://hlsjs.video-dev.org/demo/
