# region2coord

因为个人项目需求，需要根据城市名称得到经纬度信息用于地图展示，由于城市名称是由 [ip2region](https://github.com/lionsoul2014/ip2region) 匹配得到，需要有一个城市集合尽量大于 ip2region 中的城市精度，便根据 [city-geo](https://github.com/88250/city-geo) 项目的数据整理

经测试，绝大部分城市名称可以与 ip2region 中的城市名称匹配

『儋州市』在 ip2region 中为『儋州』

注：仅包括中国大陆，不含港澳台，共 337 个城市，精确到地级市