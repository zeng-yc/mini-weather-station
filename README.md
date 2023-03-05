# 基于CH32V208WB和CH32V003F4的微型气象站
  微型气象站主要实现对居住或办公场所内温度、湿度、大气压强和光照等气象变化实时监测，更为准确呈现屋内或办公区域的气象变化，便于直观感知。
  
  微型气象站由检测端和接收端两部分组成。检测端连接传感器，将传感器测量数据上报至腾讯云物联网平台。在腾讯云物联网平台建立数据流转规则，将检测端上报的数据以MQTT报文形式转发至接收端。接收端处理收到的数据，显示在液晶屏上。实现一处检测，多处查看。
  
## Bilibili运行视频展示
[基于CH32V208和CH32V003的微型气象站](https://www.bilibili.com/video/BV1Ts4y1f7pG "Test")
  
## Bilibili专栏文章
[Bilibili专栏合集](https://www.bilibili.com/read/readlist/rl679941 "bilibili专栏")

## 补充说明
  程序均使用MounRiver Studio作为IDE开发编写。文件编码使用默认的GBK，绝大多数文件内都添加了方便理解的汉字注释(符合语法规范)，如果使用默认文件格式是UTF-8格式的编辑器或者IDE打开出现乱码，请使用增强型文本编辑器转换一下格式即可。

## CH32V208WB检测端
![4 硬件组成](https://user-images.githubusercontent.com/92245992/221368938-5e836a06-368c-425e-8171-936bd21879f2.jpg#pic_center)
![3 显示内容](https://user-images.githubusercontent.com/92245992/221368944-a1f158ed-1e68-41aa-98f0-9d35283b0c3e.jpg#pic_center)

## CH32V003F4接收端
![5 接收端硬件组成](https://user-images.githubusercontent.com/92245992/221397799-5dbf1750-8307-4a4d-8879-15b2b6761397.jpg#pic_center)
![6 接收端显示内容展示](https://user-images.githubusercontent.com/92245992/221397805-5518f234-b79f-43e1-831e-62a9ba89baff.jpg#pic_center)
