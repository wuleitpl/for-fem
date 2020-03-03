# for-fem
finite element method; ANSYS; 有限元分析
***
（1）注册github账号：
用户名，邮箱; 
页面图片验证，邮箱连接验证
***
（2）fork合作仓库  
>登录自己账号  
地址栏输入：www.github.com/wuleitpl/for-fem  
点击右上方位置的Fork  
***
（3）安装windows版git  
>下载路径：http://msysgit.github.io/  
全部next，直到结束
***
（4）配对远程账户：  
>运行Git Bash  
输入：ssh-keygen -t rsa -C "你的完整电子邮件"  
一直回车，不用输入任何内容 
然后，会在当前路径下“自动”生成.shh文件夹，文件夹中的id_rsa文件不要给任何人，id_rsa.pub文件可以公开。
***	
（5）github个人主页，点开最右上角的下三角位置:  
>找到settings  
左边SSH and GPG keys  
上面New SSH key ，然后输入任意英文标题  
复制.ssh文件夹下的id_rsa.pub文件中的内容，粘贴到title下面打大框中  
提交  
远程账户设置完毕
***	 
（6）克隆远程仓库
>在Git Bash中输入
git clone git@github.com:你的Github用户名/for-fem.git  
随后，你的当前文件夹下将自动创建一个新文件夹，其内容与网上完全一致
***