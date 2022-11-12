# 湖北iptv

## 使用方法

1. 从下列播放器打开下面的链接

```
https://raw.iqiq.io/Goojoe/IPTV-CN-Hubei/master/iptv-hubei.m3u8
```

2. 下载`iptv-hubei.m3u`文件

### Windows

[VLC](https://www.videolan.org/vlc/)

[Potplayer](https://potplayer.tv/)

[MPV](https://sourceforge.net/projects/mpv-player-windows/files/)

### Android

[MXPlayer](https://play.google.com/store/apps/details?id=com.mxtech.videoplayer.ad&hl=zh&gl=US&pli=1)

[VLC](https://get.videolan.org/vlc-android/last/)

## 文件解释

- iptv-hubei.m3u:抓到的全部源,由openwrt使用udpxy映射到公网,上传带宽30Mbps=3.75mb/s

- source.txt:未提取的iptv源

- rtp.txt:iptv内网观看
- rtsp.txt:单播地址,不清楚怎么用
- regex.txt:抓包提取用的,忽略

`rtp.txt`,`rtsp.txt`转`.m3u`可以前往此网站:http://epg.51zmt.top:8000

