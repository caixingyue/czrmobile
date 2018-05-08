# 关于czrmobile
czrmobile是一款嵌入在PC端页面上展示手机网页效果的插件，可以让你在电脑后台上实时看到手机上展示的效果。

![image](https://github.com/caixingyue/czrmobile/blob/master/images/examples.jpg)
# 如何使用czrmobile
● 在需要使用czrmobile的页面引入“js/czrmobile.js” <br>
● 在需要展示的位置添加div并设置id <br>
● 调用插件：<br>
$('#demo').czrMobile({<br>
content:'Hello'<br>
//这里可以继续填写其他参数哦<br>
});<br>
  
# 参数
● 主体大小：area:字符串时为宽高一致，可用数组填写宽/高大小[默认宽度350px，高度auto]<br>
● 主体背景：background:color_name/hex_number/rgb_number/transparent[默认无颜色，可填写图片地址]<br>
● 标题内容：title:内容/false不显示[默认false]<br>
● 标题位置：titleSite:center/justify/left/right[默认center]<br>
● 标题背景颜色：titleBackground:color_name/hex_number/rgb_number/transparent[默认灰色]<br>
● 标题字体大小：titleSize:medium/smaller/larger/length/%/inherit[默认12px]<br>
● 任务栏展示：top:true显示/false不显示[默认true]<br>
● 任务栏背景颜色：topBackground:color_name/hex_number/rgb_number/transparent[默认蓝色]<br>
● 任务栏时间：time:true显示/false不显示/字符串则显示字符串信息[默认true]<br>
● 内容：content:内容，支持元素[默认空]<br>
● 内容背景颜色：contentBackground:color_name/hex_number/rgb_number/transparent[默认无颜色，可填写图片地址]<br>
● 导航栏展示：footer:true显示/false不显示[默认true]<br>
● 导航栏背景颜色：footerBackground:color_name/hex_number/rgb_number/transparent[默认黑色]<br>
● 导航栏菜单按钮事件：footerMenu:办法[默认无][事件仅最后一个模拟页有效]<br>
● 导航栏首页按钮事件：footerHome:办法[默认首页][事件最后一个模拟页有效]<br>
● 导航栏返回按钮事件：footerBack:办法[默认真实网页返回上一页][事件仅最后一个模拟页有效]<br>
