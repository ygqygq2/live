# 直播API概述 {#concept_mmr_bhl_bfb .concept}

请确保在使用这些接口前，已充分了解 视频直播 产品说明、使用协议和收费方式。

当前Live Open API版本号为：2016-11-01。

## 术语表 {#section_n5h_bz5_cfb .section}

## 业务限制资源规格限制说明 {#section_arw_bz5_cfb .section}

见[附录](https://help.aliyun.com/document_detail/27232.html)

## 直播截图 {#section_m3m_2z5_cfb .section}

|API|描述|
|:--|:-|
|[AddLiveAppSnapshotConfig](https://help.aliyun.com/document_detail/48230.html)|添加截图配置|
|[DeleteLiveAppSnapshotConfig](https://help.aliyun.com/document_detail/48231.html)|删除截图配置|
|[DescribeLiveSnapshotConfig](https://help.aliyun.com/document_detail/44796.html)|查询域名下的截图配置|
|[DescribeLiveStreamSnapshotInfo](https://help.aliyun.com/document_detail/44797.html)|查询截图信息|
|[UpdateLiveAppSnapshotConfig](https://help.aliyun.com/document_detail/44798.html)|更新截图配置|

## 直播拉流 {#section_c5n_gz5_cfb .section}

|API|描述|
|:--|:-|
|[DeleteLivePullStreamInfoConfig](https://help.aliyun.com/document_detail/57735.html)|删除拉流|
|[AddLivePullStreamInfoConfig](https://help.aliyun.com/document_detail/57734.html)|添加拉流|
|[DescribeLivePullStreamConfig](https://help.aliyun.com/document_detail/57733.html)|查询拉流信息|

## 状态通知 {#section_o1p_gz5_cfb .section}

|API|描述|
|:--|:-|
|[SetLiveStreamsNotifyUrlConfig](https://help.aliyun.com/document_detail/35415.html)|设置NotifyURL|
|[DescribeLiveStreamsNotifyUrlConfig](https://help.aliyun.com/document_detail/51835.html)|查询NotifyURL|
|[DeleteLiveStreamsNotifyUrlConfig](https://help.aliyun.com/document_detail/51836.html)|删除NotifyURL|

## 直播录制 {#section_nfq_gz5_cfb .section}

|API|描述|
|:--|:-|
|[AddLiveAppRecordConfig](https://help.aliyun.com/document_detail/35416.html)|添加APP录制配置|
|[DeleteLiveAppRecordConfig](https://help.aliyun.com/document_detail/35418.html)|删除APP录制配置|
|[DescribeLiveRecordConfig](https://help.aliyun.com/document_detail/35420.html)|查询域名下录制配置列表|
|[DescribeLiveStreamRecordContent](https://help.aliyun.com/document_detail/35421.html)|查询录制内容|
|[CreateLiveStreamRecordIndexFiles](https://help.aliyun.com/document_detail/35417.html)|创建录制索引文件|
|[DescribeLiveStreamRecordIndexFile](https://help.aliyun.com/document_detail/35422.html)|查询单个录制索引文件|
|[DescribeLiveStreamRecordIndexFiles](https://help.aliyun.com/document_detail/35423.html)|查询录制索引文件|
|[AddLiveRecordNotifyConfig](https://help.aliyun.com/document_detail/51831.html)|添加录制回调配置|
|[DeleteLiveRecordNotifyConfig](https://help.aliyun.com/document_detail/51834.html)|删除录制回调配置|
|[DescribeLiveRecordNotifyConfig](https://help.aliyun.com/document_detail/51833.html)|查询录制回调配置|
|[UpdateLiveRecordNotifyConfig](https://help.aliyun.com/document_detail/51832.html)|更新录制回调配置|

## 直播流管理 {#section_p4q_gz5_cfb .section}

|API|描述|
|:--|:-|
|[ForbidLiveStream](https://help.aliyun.com/document_detail/35413.html)|禁止直播流推送|
|[DescribeLiveStreamsBlockList](https://help.aliyun.com/document_detail/35410.html)|查询推流黑名单列表|
|[DescribeLiveStreamsControlHistory](https://help.aliyun.com/document_detail/35411.html)|查询流控历史|
|[DescribeLiveStreamsOnlineList](https://help.aliyun.com/document_detail/35409.html)|查询推流在线列表|
|[DescribeLiveStreamsPublishList](https://help.aliyun.com/document_detail/35408.html)|查询推流历史|
|[ResumeLiveStream](https://help.aliyun.com/document_detail/35414.html)|恢复直播流推送|
|[DescribeLiveStreamsFrameRateAndBitRateData](https://help.aliyun.com/document_detail/60410.html)|查询直播流实时帧率和码率|
|[DescribeLiveStreamBitRateData](https://help.aliyun.com/document_detail/35424.html)|查询直播流历史帧率和码率|

## 直播转码 {#section_afr_gz5_cfb .section}

|API|描述|
|:--|:-|
|[AddLiveStreamTranscode](https://help.aliyun.com/document_detail/45039.html)|添加转码配置|
|[DeleteLiveStreamTranscode](https://help.aliyun.com/document_detail/45049.html)|删除转码配置|
|[DescribeLiveStreamTranscodeInfo](https://help.aliyun.com/document_detail/45048.html)|查询转码配置信息|
|[AddCustomLiveStreamTranscode](https://help.aliyun.com/document_detail/66944.html)|添加自定义转码配置|
|[AddTrancodeSEI](https://help.aliyun.com/document_detail/66945.html)|添加转码SEI信息|

## 资源监控 {#section_pmr_gz5_cfb .section}

|API|描述|
|:--|:-|
|[DescribeLiveStreamHistoryUserNum](https://help.aliyun.com/document_detail/61267.html)|查询直播流历史在线人数|
|[DescribeLiveStreamOnlineUserNum](https://help.aliyun.com/document_detail/35412.html)|查询直播流实时在线人数|
|[DescribeLiveDomainBpsData](https://help.aliyun.com/document_detail/67406.html)|查询直播域名网络带宽监控数据|
|[DescribeLiveDomainTrafficData](https://help.aliyun.com/document_detail/67409.html)|查询直播域名网络流量监控数据|
|[DescribeLiveDomainTranscodeData](https://help.aliyun.com/document_detail/68942.html)|查询直播域名转码时长数据|
|[DescribeLiveDomainRecordData](https://help.aliyun.com/document_detail/68943.html)|查询直播域名录制时长数据|
|[DescribeLiveDomainSnapshotData](https://help.aliyun.com/document_detail/68944.html)|查询直播域名截图张数数据|

