# open string

## chrome 插件

弹出一个框, 上面由data中配置的数据生成表格, 是一个表单网页, 需要用户输入一些字符, 然后和事先确定好的字符串(URL)组合后打开

## 使用示例

比如打开Pixiv的uid, 使用谷歌搜索等

## 吐槽

设置数据的储存地方是本地磁盘上的, 在当前文件的data/config.json中, 使用ajax请求到他, 但是尴尬的是, 没法依靠js向其中写入.
如果需要可以进行修改参数的操作, 应该使用localstorage或storage作为储存参数的.

改进方向, 设置中, 用户可以向storage中添加自定义的参数, 可以增删改.