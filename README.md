# 五子棋 / FIR PHP小游戏

## 特性 Features

- 落子记录
- JSON数据文件
- 简易`md5`防修改加密签名算法
- 几乎没有依赖

## 数据文件升级

详情见[数据文件升级页](./docs/data/update.md)

## TODO LIST

- 优化`resume()`函数报错模式
- 增加`AI`
- 增加`悔棋`
- 优化前端代码
- 优化前端界面
- 增加`websocket`支持

## FINISHED

- 修复`index.php`中第一行存在触发器的情况
- 增加`save()`函数无参数情况下自动读取上一次的设置
- 增加`save()`函数保存至其他文件名
