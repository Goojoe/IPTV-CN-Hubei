# 湖北电信iptv

软路由性能实在太差,无法支撑公网观看,所以大家还是自己内网openwrt路由器观看吧.....

## 使用方法

下载`iptv-hubei.m3u`文件

替换`(routeip)`为你的路由器ip

替换`(port)`为路由器udpxy端口

例子

```
http://10.0.0.1:4012/rtp/
```

### Windows

[VLC](https://www.videolan.org/vlc/)

[Potplayer](https://potplayer.tv/)

[MPV](https://sourceforge.net/projects/mpv-player-windows/files/)

### Android

[MXPlayer](https://play.google.com/store/apps/details?id=com.mxtech.videoplayer.ad&hl=zh&gl=US&pli=1)

[VLC](https://get.videolan.org/vlc-android/last/)

## 文件解释

- iptv-hubei.m3u:抓到的全部源,替换自己的 openwrt路由器ip,udpxy端口即可观看

- source.txt:未提取的iptv源

- rtp.txt:iptv内网观看
- rtsp.txt:单播地址,不清楚怎么用
- regex.txt:抓包提取用的,忽略

`rtp.txt`,`rtsp.txt`转`.m3u`可以前往此网站:http://epg.51zmt.top:8000

