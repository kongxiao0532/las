# las
LAS (Live Adaptive Streaming), an adaptive bitrate streaming technique that enables high quality and low-latency live streaming of media content over HTTP, WebRTC, and so on. Rather than MPEG-DASH or HLS, breaking the content into a sequence of small file fragments and transmitting in fragment-level, LAS transmits the media content in frame-level to provide low-latency. Besides, based on stream, LAS only needs to send new requests when the bitrate-level (quality-level) has changed, thus, it needs less requests than fragment-based adaptive bitrate streaming technique. LAS has been widely supported by cloud vendors, such as Alibaba-Cloud, Baidu, Tencent Cloud, CDNetCenter, Kingsoft Cloud etc. Besides, it also has been deployed by Kuaishou, and used by more than one 100, 000, 000 users every day.