# e203_Three-stageToFour-stage
蜂鸟E200开源处理器核心
三级流水转化为四级流水步骤：
*   从EXU抽取出WBCK模块
*   给WBCK模块添加的时钟
*   在WBCK模块添加延时再把数据写回
*   处理由于延迟导致的问题【WAR】

 首先下载：https://github.com/LEAUQEAAN/e200_opensource
  
 请先熟悉前一个项目：https://github.com/LEAUQEAAN/e203_Two-stageToThree-stage

 下载本项目：
 
 将本项目的core替换解压后文件夹里的rtl\e203\core目录
 
 将本项目的verilator替换解压后文件夹里的rtl\verilator目录

 安装verilator进入verilator目录里的readme.md进行了解



