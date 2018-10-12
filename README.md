# 超星军事理论课刷课脚本
## 小白如何使用

1.环境要求：python3.6，火狐浏览器，外加自行安装好.py文件内import的包。  
2.搜索.py文件中“开始课程序号”注释，那一行的i即为开始刷课的地方，可以自行设置。（不分章节直接累加）  
3.打开浏览器登陆自己的超星账号进入课程播放界面，复制网址，替换.py文件中的url。  
4.[运行python脚本](https://jingyan.baidu.com/article/22fe7ced18776f3002617f2e.html)  
5.之后会弹出浏览器框，30秒内输入账号密码验证码登陆后，挂在电脑后台慢慢等待即可，注意：不要调整浏览器大小就让他保持最大化以免出现问题。

## 实现细节
1.主要是调了selenium库，然后加了很多sleep和try catch语句块，保证稳定性。  
2.增加了查出错的代码块，会一直刷直到出错列表为空。  

## 存在问题
1.刷课序号可能有问题。  

