# 图片懒加载示例

# 运行示例

npm i -g http-server
http-server . -c-1

# 知识点

* 防抖函数 debounce 
* 获取图片高度与可视区域高度做差值, 判断当前图片是否用户可见, 如果可见就给src赋值