### 58同城品牌公寓爬虫


#### 2016.08.13
1. 更新后同步挂载于： http://codelover.link:8080
2. 下一步准备加入更多的房源信息(PS:只是准备...)
3. 知乎专栏无耻求赞（ https://zhuanlan.zhihu.com/p/21998221）

#### 2016.08.13
1. 加入城市名匹配58同城城市简称功能，去除城市名转拼音导致无法准确定位城市问题
2. 继续感谢衣衣姐去除58同城广告数据的commit


##### 2016.08.13
1. 去除输入城市名定位问题，改为移动地图直接获取地图中心所在城市
2. 下一步准备构建城市名-城市简称字典，用于快速匹配正常的58同城地址
3. 修复已知bug...

##### 2016.08.12
1. 感谢衣姐的重构代码的commit
2. 修复输入城市中文名导致地图房子位置点击后跳转页面错误问题
3. 输入城市名无法直接定位到城市这个问题正在解决


##### 2016.08.08
1. 完成指定城市名定位
2. 修复上版本bug
3. 更正为全国版


##### 2016.08.7
1. 改版于 https://zhuanlan.zhihu.com/p/21883516
2. 使用高德地图API
3. 挂载于 http://codelover.link:8080
4. 手动输入城市名还有点bug，暂时无法正常使用