# 1001
WebRTC源码级深度解析 | 更新完结
### 微:NoBug1024 


课程介绍：

〖课程目录〗:

├──第12章WebRTC服务质量（Qos）iclass=new_ta
| ├──[12.10]–12-10-判断包位置的关键算法.mp4 42.89M
| ├──[12.11]–12-11-WebRTC中NACK的处理流程.mp4 60.33M
| ├──[12.12]–12-12-判断是否丢包的逻辑.mp4 72.49M
| ├──[12.13]–12-13-找到真正的丢包.mp4 61.66M
| ├──[12.14]–12-14-VP8关键帧的判断.mp4 84.31M
| ├──[12.15]–12-15-NACK格式.mp4 39.38M
| ├──[12.1]–12-1-WebRTC服务质量概述.mp4 7.89M
| ├──[12.2]–12-2-WebRTC服务质量综述.mp4 74.01M
| ├──[12.3]–12-3-RTP协议.mp4 46.59M
| ├──[12.4]–12-4-RTP扩展头.mp4 64.84M
| ├──[12.5]–12-5-RTCP协议一.mp4 117.24M
| ├──[12.6]–12-6-RTCP协议二-SDES作用和报文件格式.mp4 49.24M
| ├──[12.7]–12-7-RTCP协议三-其它类型的RTCP报文.mp4 62.95M
| ├──[12.8]–12-8-RTCP协议四-CompoundRTCP.mp4 54.29M
| └──[12.9]–12-9-丢包重传NACK与RTX.mp4 43.01M
├──第10章视频引擎（视频编解码）
| ├──[10.10]–10-10-创建WebRtcVideoSendStream的时机.mp4 37.99M
| ├──[10.11]–10-11-创建内部VideoSendStream.mp4 35.60M
| ├──[10.12]–10-12-VP8编码器的创建及编码.mp4 62.19M
| ├──[10.13]–10-13-应用视频解码器参数.mp4 80.10M
| ├──[10.14]–10-14-编解码器CodecID的设置.mp4 37.85M
| ├──[10.15]–10-15-SessionDescription.mp4 90.05M
| ├──[10.16]–10-16-创建WebRtcVideoReceiveStream.mp4 39.55M
| ├──[10.17]–10-17-创建解码器及初始化.mp4 59.76M
| ├──[10.18]–10-18-视频解码.mp4 49.39M
| ├──[10.1]–10-1视频引擎章节概述.mp4 19.87M
| ├──[10.2]–10-2视频数据采集的时间.mp4 57.72M
| ├──[10.3]–10-3视频分发器VideoBroadcaster.mp4 79.81M
| ├──[10.4]–10-4视频数据是如何进入视频分发器的.mp4 67.06M
| ├──[10.5]–10-5视频引擎及其作用.mp4 82.38M
| ├──[10.6]–10-6-视频编码器的创建与视频编码流程.mp4 59.16M
| ├──[10.7]–10-7-VideoStreamEncoder的创建.mp4 56.39M
| ├──[10.8]–10-8-获取编解码器参数.mp4 79.91M
| └──[10.9]–10-9-应用视频编码参数.mp4 90.40M
├──第11章深入理解WebRTC网络传输
| ├──[11.10]–11-10-创建PortAllocatorSession.mp4 50.47M
| ├──[11.11]–11-11-创建AllocationSequence.mp4 59.86M
| ├──[11.12]–11-12-收集Candidate.mp4 70.44M
| ├──[11.13]–11-13-获取本地Canidadate.mp4 51.35M
| ├──[11.14]–11-14-STUN协议.mp4 76.93M
| ├──[11.15]–11-15-发送StunBindingRequest消息.mp4 62.86M
| ├──[11.16]–11-16-收集Srflx类型的Candidate.mp4 42.57M
| ├──[11.17]–11-17-TURN协议基本原理.mp4 46.81M
| ├──[11.18]–11-18-TurnClient与TurnServer的连接过程.mp4 61.21M
| ├──[11.19]–11-19-Turn协议数据传输机制.mp4 60.13M
| ├──[11.1]–11-1-深入理解WebRTC网络传输-概述.mp4 9.37M
| ├──[11.20]–11-20-收集Turn类型Candidate(一）.mp4 42.86M
| ├──[11.21]–11-21-收集Turn类型Candidate(二).mp4 37.98M
| ├──[11.22]–11-22-收集TCP类型的Candidate.mp4 28.26M
| ├──[11.23]–11-23-将获得的Candidate上抛给应用层.mp4 42.67M
| ├──[11.24]–11-24-WebRTC网络连接的建立.mp4 34.32M
| ├──[11.25]–11-25-Connection排序.mp4 66.19M
| ├──[11.27]–11-27-Connection的裁剪.mp4 43.86M
| ├──[11.28]–11-28-ICE提名.mp4 27.88M
| ├──[11.29]–11-29-ICE-FULL与ICE-LITE.mp4 26.14M
| ├──[11.2]–11-2-网络设备管理.mp4 73.44M
| ├──[11.30]–11-30-连通性检测.mp4 73.55M
| ├──[11.31]–11-31-网络传输对象的创建与数据传输.mp4 61.95M
| ├──[11.3]–11-3-读取网卡信息的重要API.mp4 96.92M
| ├──[11.4]–11-4-源码分析-CreateNetworks.mp4 121.56M
| ├──[11.5]–11-5-获了本地默认IP地址和端口.mp4 73.89M
| ├──[11.6]–11-6-获取本地默认IP地址.mp4 115.62M
| ├──[11.7]–11-7-ICE.mp4 78.41M
| ├──[11.8]–11-8-Candiate.mp4 47.89M
| └──[11.9]–11-9-创建PortAllocator.mp4 85.88M
├──第12章WebRTC服务质量（Qos）iclass=new_ta
| ├──[12.10]–12-10-判断包位置的关键算法.mp4 42.89M
| ├──[12.11]–12-11-WebRTC中NACK的处理流程.mp4 60.33M
| ├──[12.12]–12-12-判断是否丢包的逻辑.mp4 72.49M
| ├──[12.13]–12-13-找到真正的丢包.mp4 61.66M
| ├──[12.14]–12-14-VP8关键帧的判断.mp4 84.31M
| ├──[12.15]–12-15-NACK格式.mp4 39.38M
| ├──[12.1]–12-1-WebRTC服务质量概述.mp4 7.89M
| ├──[12.2]–12-2-WebRTC服务质量综述.mp4 74.01M
| ├──[12.3]–12-3-RTP协议.mp4 46.59M
| ├──[12.4]–12-4-RTP扩展头.mp4 64.84M
| ├──[12.5]–12-5-RTCP协议一.mp4 117.24M
| ├──[12.6]–12-6-RTCP协议二-SDES作用和报文件格式.mp4 49.24M
| ├──[12.7]–12-7-RTCP协议三-其它类型的RTCP报文.mp4 62.95M
| ├──[12.8]–12-8-RTCP协议四-CompoundRTCP.mp4 54.29M
| └──[12.9]–12-9-丢包重传NACK与RTX.mp4 43.01M
├──第13章NetEQiclass=new_tagi
| ├──[13.1]–13-1-NetEq在WebRTC中的位置.mp4 24.06M
| ├──[13.2]–13-2-抖动消除的基本原理.mp4 44.12M
| ├──[13.3]–13-3-NetEq整体架构.mp4 53.94M
| ├──[13.4]–13-4-NetEq中的几种缓冲区.mp4 96.24M
| └──[13.5]–13-5-新版NetEq中的MCU和DSP.mp4 49.65M
├──第14章Simulcast与SVCiclass=new_tagi
| ├──[14.1]–14-1-什么是Simulcast.mp4 38.35M
| ├──[14.2]–14-2-开启Simulcast的三种方法.mp4 101.52M
| ├──[14.3]–14-3-Simulcast在WebRTC中的实现.mp4 46.85M
| ├──[14.4]–14-4-什么是SVC.mp4 53.70M
| ├──[14.5]–14-5-WebRTC开启SVC的方式.mp4 67.63M
| └──[14.6]–14-6-VP9RTP包结构.mp4 74.95M
├──第15章课程总结iclass=new_tagi
| └──[15.1]–15-1-WebRTC深入剖析总结.mp4 82.11M
├──第1章 课程介绍与学习指南
| └──1-2 WebRTC源码剖析课程导学.mp4 147.46M
├──第2章 WebRTC的整体架构
| ├──2-1 WebRTC整体架构-如何对WebRTC源码进行分析(加片头).mp4 26.23M
| ├──2-2 音视频直播的由来.mp4 28.88M
| ├──2-3 直播技术的方向.mp4 83.83M
| ├──2-4 实时互动直播的难点.mp4 69.63M
| ├──2-5 几个重要指标和评测方法.mp4 69.12M
| ├──2-6 为什么要使用WebRTC.mp4 66.11M
| └──2-7 WebRTC整体架构.mp4 73.69M
├──第3章 WebRTC源码分析环境的搭建
| ├──3-1 -WebRTC开发环境搭建概述 (加片头).mp4 24.04M
| ├──3-2 -获取WebRTC源码.mp4 146.62M
| ├──3-3 -编译WebRTC的必备工具.mp4 81.79M
| ├──3-4 -编译WebRTC源码.mp4 110.57M
| └──3-5 -WebRTC中的重要Demo.mp4 55.65M
├──第4章 开启WebRTC源码分析之路
| ├──4-1 分析WebRTC必经之路章节概述 (1).mp4 16.72M
| ├──4-10 源码分析-client界面.mp4 245.96M
| ├──4-11 信令逻辑.mp4 53.56M
| ├──4-12 源码分析-信令的实现.mp4 270.36M
| ├──4-13 WebRTC-Native开发过程.mp4 275.57M
| ├──4-14 源码分析-媒体协商.mp4 118.77M
| ├──4-15 源码分析-视频渲染.mp4 138.53M
| ├──4-2 一对一实时通信架构.mp4 46.57M
| ├──4-3 peerconnection_client的构成.mp4 48.83M
| ├──4-4 几个重要的信令.mp4 18.17M
| ├──4-5 WebRTC中的媒体协商.mp4 41.83M
| ├──4-6 完美协商.mp4 45.26M
| ├──4-7 Windows窗口与消息.mp4 46.64M
| ├──4-8 实战-实现一个最简单的Windows应用程序.mp4 110.66M
| └──4-9 peerconnection-client界面实现.mp4 53.93M
├──第5章 抓住WebRTC的脉络 （深入理解WebRTC的线程模型）
| ├──5-1 WebRTC线程模型概述.mp4 28.90M
| ├──5-10 WebRTC接口宏.mp4 69.17M
| ├──5-11 WebRTC接口的设计原理.mp4 62.52M
| ├──5-12 WebRTC接口调用过程.mp4 286.52M
| ├──5-13 Post方法进行线程切换.mp4 50.83M
| ├──5-2 线程基础知识.mp4 45.83M
| ├──5-3 常见的线程模型.mp4 27.90M
| ├──5-4 WebRTC中的线程.mp4 171.90M
| ├──5-5 WebRTC中的线程管理.mp4 129.94M
| ├──5-6 WebRTC三大线程.mp4 190.28M
| ├──5-7 -WebRTC线程的启动与运行.mp4 174.03M
| ├──5-8 WebRTC事件处理基础知识.mp4 87.24M
| └──5-9 WebRTC线程事件处理.mp4 272.75M
├──第6章 开始“聊天”之前先认识一下 （WebRTC媒体协商）
| ├──6-1 -WebRTC媒体协商–综述.mp4 19.73M
| ├──6-10 源码分析-SetLocalDescription之二.mp4 220.11M
| ├──6-11 -收集Candidate的过程.mp4 218.87M
| ├──6-12 -生成SDP文本信息.mp4 247.29M
| ├──6-13 -解析SDP文本信息.mp4 180.57M
| ├──6-14 -源码分析-CreateAnswer.mp4 252.89M
| ├──6-15 -源码分析-SetRemoteDescription.mp4 229.85M
| ├──6-2 -SDP协议.mp4 62.83M
| ├──6-3 -WebRTC中的SDP类结构.mp4 125.34M
| ├──6-4 -如何生成SDP.mp4 81.11M
| ├──6-5 -编解码器信息的收集.mp4 86.34M
| ├──6-6 -编解码器信息的收集之二.mp4 376.50M
| ├──6-7 -源码分析-CreateOffer之一.mp4 100.91M
| ├──6-8 -CreateOffer源码分析之二.mp4 263.67M
| └──6-9 -源码分析-SetLocalDescription之一.mp4 244.11M
├──第7章音频数据采集
| ├──[7.10]–7-10ADM初始化之InitMicrophone.mp4 48.34M
| ├──[7.11]–7-11AudioState.mp4 43.35M
| ├──[7.12]–7-12Engine_PeerConnection_Call等对.mp4 79.67M
| ├──[7.13]–7-13打开播放设备.mp4 68.21M
| ├──[7.14]–7-14InitPlay基础知识.mp4 70.61M
| ├──[7.15]–7-15InitPlayout源码分析.mp4 102.36M
| ├──[7.16]–7-16播放声音的基础API.mp4 53.85M
| ├──[7.17]–7-17播放声音的具体流程.mp4 33.56M
| ├──[7.18]–7-18源码分析-StartPlayout.mp4 106.02M
| ├──[7.19]–7-19再论音频DMO.mp4 137.40M
| ├──[7.1]–7-1音频数据采集与播放概述.mp4 9.61M
| ├──[7.20]–7-20源码分析-InitRecording.mp4 121.97M
| ├──[7.21]–7-21StartRecording处理逻辑.mp4 38.37M
| ├──[7.22]–7-22源码分析-StartRecording.mp4 57.59M
| ├──[7.2]–7-2ADM的创建.mp4 63.63M
| ├──[7.3]–7-3CoreAudio基本开概念.mp4 74.63M
| ├──[7.4]–7-4CoreAudio-API.mp4 111.14M
| ├──[7.5]–7-5AudioDeviceWindowsCore的构造函数.mp4 194.48M
| ├──[7.6]–7-6ADM初始化.mp4 47.83M
| ├──[7.7]–7-7源码分析-ADM初始化之枚举音频设备.mp4 123.61M
| ├──[7.8]–7-8ADM初始化之InitSpeaker.mp4 70.97M
| └──[7.9]–7-9ADM初始化之设置通道数.mp4 71.40M
├──第8章视频数据采集
| ├──[8.10]–8-10源码分析-构造并初始化VideoCapture.mp4 95.24M
| ├──[8.11]–8-11获取CaptureFilter.mp4 49.55M
| ├──[8.12]–8-12获取CaptureFilter的输出Pin.mp4 101.67M
| ├──[8.13]–8-13构造SinkFilter.mp4 79.18M
| ├──[8.14]–8-14源码分析-SinkFilter的构造.mp4 56.29M
| ├──[8.15]–8-15获取SinkFilter的输入Pin.mp4 58.56M
| ├──[8.16]–8-16Filter之间的连接.mp4 84.70M
| ├──[8.17]–8-17SetCameraOutput.mp4 86.65M
| ├──[8.18]–8-18源码分析-连接Filter（一）.mp4 105.99M
| ├──[8.19]–8-19源码分析-连接Filter（二）.mp4 59.82M
| ├──[8.1]–8-1视频采集概述.mp4 9.14M
| ├──[8.20]–8-20输出采集后的视频数据.mp4 78.02M
| ├──[8.2]–8-2DirectShow基础知识.mp4 59.13M
| ├──[8.3]–8-3WebRTC视频采集整体架构.mp4 34.00M
| ├──[8.4]–8-4视频处理流程的建立.mp4 83.21M
| ├──[8.5]–8-5源码分析-视频处理流程的建立.mp4 69.07M
| ├──[8.6]–8-6构造设备信息对象.mp4 93.12M
| ├──[8.7]–8-7获音视频设备信息基础知识.mp4 38.58M
| ├──[8.8]–8-8源码分析-获取视频设备信息.mp4 37.28M
| └──[8.9]–8-9创建并初始化VideoCapture.mp4 56.09M
├──第9章音频引擎（音频编解码）
| ├──[9.10]–9-10音频编码.mp4 74.17M
| ├──[9.11]–9-11音频解码器的创建.mp4 152.87M
| ├──[9.12]–9-12音频解码.mp4 51.80M
| ├──[9.1]–9-1音频引擎章节概述.mp4 14.42M
| ├──[9.2]–9-2音频引擎架构.mp4 70.67M
| ├──[9.3]–9-3创建音频引擎.mp4 74.92M
| ├──[9.4]–9-4音频初始化之编解码器的收集.mp4 87.78M
| ├──[9.5]–9-5音频初始化之AudioState对象的创建.mp4 72.70M
| ├──[9.6]–9-6音频引擎初始化之获取音频数据.mp4 121.03M
| ├──[9.7]–9-7Channel-Stream与编解码器.mp4 95.91M
| ├──[9.8]–9-8创建音频编码器之一.mp4 141.21M
| └──[9.9]–9-9创建Opus编码器.mp4 160.64M
└──课件
| └──课件
| | └──webrtc-master.zip 2.05M
