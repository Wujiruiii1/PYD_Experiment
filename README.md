#处理堪萨斯城某街区地图数据
#首先读取OSM数据，利用osmosis命令行工具裁切数据。裁切边界polygon，得到txt数据格式。目测估计判断点聚焦范围，在QGIS中绘制polygon边界，再编写polygon到osmosis格式的polygon代码，最后得出地图图片
https://github.com/Wujiruiii1/PYD_Experiment/raw/main/osm%E5%9B%BE%E7%89%872.png 
https://github.com/Wujiruiii1/PYD_Experiment/raw/main/osm%E5%9B%BE%E7%89%871.png
用osm2sqlite把osm格式的文件转化成sqlite格式，在ghpython中读取sqlite格式文件，得到结果 
https://github.com/Wujiruiii1/PYD_Experiment/raw/main/ghpython%E5%A4%84%E7%90%86%E5%9B%BE.png