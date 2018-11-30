# Alfred Workflow
这里是我个人使用的`workflows`,有自己写的，也有别人写的我备份到这里的

#### youdao
* 来自 [wensonsmith/YoudaoTranslate](https://github.com/wensonsmith/YoudaoTranslate),有道翻译
* `keyword: yd`

#### Open++
* 快速打开应用，现在只写了快速打开指定网站,`json格式化校验`,`在线正则表达式测试`,`iconfont`等
* 添加网站可以直接添加代码，如下：

	```
	if [[ "wanandroid" == ${q}* ]];then
	genItem "json" "open http://www.wanandroid.com" "imgs/wanandroid.png"
	fi
	```
* `keyword: o`
![](imgs/iconfont.png)

### short_url
* 短网址，支持`tinyurl`,`suo.im`
* 修改自[`shorten-url`](http://www.packal.org/workflow/shorten-url)
* `keyword: short`
![](imgs/short_url.png)
