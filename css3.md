# css3
## css3 选择器
* 后代类型

|选择器|用途|
|:----:|:----:|
|:nth-child()|做为子元素是第几个|
|:nth-last-child()|作为子元素是第几个（倒数）|
|:first-child|做为子元素是第一个|
|:last-child|做为子元素是最后一个|
|:only-child|做为子元素是唯一的一个|

|选择器|用途|
|:----:|:----:|
|:nth-of-type()|做为子元素是同类型第几个|
|:nth-last-of-type()|作为子元素是同类型第几个（倒数）|
|:first-of-type|做为子元素是同类型第一个|
|:last-of-type|做为子元素是同类型最后一个|
|:only--of-type|做为子元素是同类型唯一的一个|
* 属性选择器

|选择器|用途|
|:----:|:----:|
|[attr]|具有某个属性的元素|
|[attr=val]|某个属性为某个特定值的元素|
|[attr^=val]|某个属性以某个特定值开始的元素|
|[attr$=val]|某个属性以某个特定值结束|
|[attr*=val]|某个属性并且包含特定值|

* 其他

|选择器|用途|
|:----:|:----:|
|:empty|不包含子元素或者任何内容的元素|
|:target|选择当前锚链接指向的元素|

* 表单

|选择器|用途|
|:----:|:----:|
|:enabled|选择没有被禁用的|
|:disabled|选择被禁用掉的|
|:checked|被选中的元素|
|:first-line|选中段落中的第一行文字|
|:first-letter|选中段落里面的第一个文字|
|:before|在选中的元素之前插入一段内容|
|:after|在选中的元素之后插入一段内容|
|:not(selector)|排除某些元素|
|a+b|选择紧邻在a元素后的b元素|
|a~b|选择前面有a元素的b元素|
## box-sizing
> 定义盒子模型形式 border-box
## outline
> 定义描边/轮廓线

|属性|值|
|:----:|:----:|
|outline-width|轮廓线的宽度|
|outline-style|轮廓线的样式|
|outline-color|轮廓线的颜色|
|outline-offset|轮廓线向外的偏移量 可以为负值|
> outline 不支持跟随圆角变化

## border-radius
> 可以设置1/2/3/4个值

> 同一个位置的两个值 a/b 或者 a1 b1 c1 d1/a2 b2 c2 d2

## box-shadow
> 横向偏移量 纵向偏移量 阴影的模糊程度
 阴影的大小
 阴影的颜色
 阴影的位置(inset)

>阴影可以添加很多组值

## background
 * background-clip
 > 当前背景图片的裁剪范围
 * background-orgin
 > 当前背景图片的定位参照
 * background-size
 > 长度 百分比  cover 等比例放大图片 直到铺满容器位置
 contain 等比例放大图片 直到不能再继续放大位置
 * 设置多组值
## border-image
|属性|值|
|:----:|:----:|
|border-image-source|图片的路径|
|border-image-slice|图片截取量|
|border-image-width|图片边框的宽度|
|border-image-outset|图片向外的偏移量|
|border-image-repeat|图片重复的方式|


1. 在管理控制台添加部署 添加数据库
 * 数据库的名称 ROtjaQhrLsdpfKNrYqZA
 * 数据库的地址 sqld.duapp.com:4050
 * 数据库的账号 3aa531573984499b82d2eee00c57d0c0
 * 数据库的密码 22527c4ce96b4c05adf17d558826f606

2. 数据库
  * 导出数据库文件将localhost替换为wangqiccc.duapp.com
  * 在服务器端将数据库导入
3. 上传代码
  * svn svn检出到对应文件夹
  * 删掉无用的文件
  * 拷贝自己的文件到这文件夹中
  * caches/configs/database.php
  ![](http://localhost:63342/myproject/12.20/upload.jpg)
  * caches/configs/system.php localhost==>wangqiccc.duapp
 ![](http://localhost:63342/myproject/12.20/upload2.jpg)
  * 通过svn上传


  * git
    * git clone https://git.duapp.com/appidf6bah85rnc
    * git rm index.html
    * git commit -m "remove"
    * git push

    * git add phpcms
    * git commit -m "add"
    * git push