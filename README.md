# KA盟 · 店铺分布地图 Demo

KA盟店铺分布地图演示页面：近30天发了积分的积分赛店铺分布，可切换全国/城市、按 TCG 筛选、缩放拖拽、hover 查看每场积分赛明细。

- 底图：高德地图（免 key 瓦片，demo 用）
- 库：Leaflet（unpkg CDN）
- 数据：point_log 按 `action=1`、`point_type_id∈{2,3}` 判定「发了积分」

上线建议接入高德/腾讯 JS SDK（配 key）以获取合规稳定的底图与精确到门牌号的坐标。
