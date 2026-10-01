# 服务区边界来源与许可

数据来源：wmgeolab/geoBoundaries，固定提交 9469f09592ced973a3448cf66b6100b741b64c0d，下载日期 2026-09-18。

- 福建：CHN ADM1中 shapeName=Fujian Province，来源 geoBoundaries / Wikimedia Commons，2019年代表边界，Public Domain。
- 马来西亚：MYS ADM0，来源 OpenStreetMap / Wambacher，2017年代表边界，Open Data Commons Open Database License 1.0；署名 OpenStreetMap contributors，https://www.openstreetmap.org/copyright 。衍生rings CSV与源几何沿用该数据许可。
- [CHN元数据](https://www.geoboundaries.org/api/current/gbOpen/CHN/ADM1/)
- [MYS元数据](https://www.geoboundaries.org/api/current/gbOpen/MYS/ADM0/)
- [CHN下载](https://github.com/wmgeolab/geoBoundaries/raw/9469f09/releaseData/gbOpen/CHN/ADM1/geoBoundaries-CHN-ADM1_simplified.geojson)
- [MYS下载](https://github.com/wmgeolab/geoBoundaries/raw/9469f09/releaseData/gbOpen/MYS/ADM0/geoBoundaries-MYS-ADM0_simplified.geojson)

这里使用简化边界做工程采样，不是测绘级行政边界或海域权益判定。保留源GeoJSON；rings CSV只作无Mapping Toolbox条件下的等价多边形读取，保留多部件及孔洞。
