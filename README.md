# 一级标题
Hello world!!!!
##二级标题
这是一段普通文本,
直接回车是不能换行的,亲!<br>
如果需要换行请在需要换行的末尾添加(注编辑时左边面的<br>前加了反斜杠\,目的是实现转义,也就是<的转义.) \<br>

###三级标题
`如果你想让一段文字高亮显示,突出强调效果`
使用tab键上面的`键把需要高亮显示的字段用两个这样的符号包含起来
####四级标题
####插入文本
1.单行文本<br>
    hello 大家好,我是JKbai<br>
2.多行文本<br>
    欢迎到访<br>
    共同进步<br>
    谢谢<br>
####插入代码片段
我们需要在代码的上一行和下一行用` `` 标记。``` 不是三个单引号，而是数字1左边，Tab键上面的键。要实现语法高亮那么只要在 ``` 之后加上你的编程语言即可（忽略大小写）。Object-C语言可简写为obj-c,看代码：
```obj-c
- (UITableViewCell *)tableView:(UITableView *)tableView cellForRowAtIndexPath:(NSIndexPath *)indexPath {

    UITableViewCell *cell = [tableView dequeueReusableCellWithIdentifier:@"cell"];

    static NSString *cellIdentifier = @"cell";

    UITableViewCell *cell = [tableView dequeueReusableCellWithIdentifier:cellIdentifier];

    if (cell == nil) {

        cell = [[UITableViewCell alloc]initWithStyle:UITableViewCellStyleDefault reuseIdentifier:cellIdentifier];
    }

    [cell extendAnimation];

    cell.textLabel.text = @"你是猴子请来的逗逼么";

    cell.imageView.image = [UIImage imageNamed:@"heh"];

    return cell;

}
```


####插入图片
#####网络图片
格式:叹号\! + 方括号\[\] + 括号\( \) 其中叹号里是图片的URL。<br>

![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")  <br>

#####插入github项目中的图片
格式:  \<img src="https://github.com/需要上传的图片在项目中的路径(找到相关项目中对应的图片直接拷贝图片链接即可)" width=图片宽度 height=图片高度\>\</img\>

如果担心写错直接在GitHub对应的项目中找到图片然后右键鼠标选择拷贝连接,该链接就是URL<br>
<img src="https://github.com/JKbai/Test/blob/master/Test/1.PNG" width=200px height=300px></img>
<img src="https://github.com/JKbai/Test/blob/master/Test/2.PNG" width=200px height=300px></img>
<img src="https://github.com/JKbai/Test/blob/master/Test/3.PNG" width=200px height=300px></img>
<img src="https://github.com/JKbai/Test/blob/master/Test/4.PNG" width=200px height=300px></img>
#####五级标题
给一段文字加入超链接的格式是这样的 \[ 要显示的文字 \]\( 链接的地址 \)。比如：<br>
\[我的博客\]\(http://www.cnblogs.com/yinxiao-bai1014/\),效果如下:<br>

[我的博客](http://www.cnblogs.com/yinxiao-bai1014/)<br>
[我的GitHub](https://github.com/JKbai)<br>
[我的简书](http://www.jianshu.com/users/46a9daddd47b/timeline)<br>
######六级标题
>我的英文名:JackBai<br>
>>我的职业:iOS开发<br>
>>>我的追求的动漫:火影忍者

