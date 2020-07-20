# Simplified Chinese Edgerouter Translater|EdgerRouter全版本汉化工具
特性：
- 没有型号、版本依赖。升级固件后再运行一次就可以了，大不了新词汇找不到还是E文而已。
- 安全。也就是一个简单的脚本，谁都能打开来看，不象其它编译的程序或是别人弄好的模板，要担心有没夹带私货。
- 字典开放，任何人都可以参与维护。  
    
使用方法：
- 用软件将两个文件  er-en2zh-0.99.ER.noarch.tar.gz 和  er-dict.txt上传到路由器中任意一个文件夹中，进入管理界面，打开CLI，用管理员账户登录
- 进入你上传好的那个目录  
``` cd /home/ubnt <!--将目录换成你自己的-->```   
```  tar zxvf er-en2zh-0.99.ER.noarch.tar.gz <!--切忌用windows解压缩后上传，必须用tar命令解压缩-->```   
``` sudo ./er-en2zh make <!--翻译-->```   
```  sudo ./er-en2zh zh <!--将语言定为中文-->```  
``` sudo ./er-en2zh en <!--将语言定为英文--> ```     
    
注意：路由器汉化过程中可能会遇到xxx.xxx.xxx.xxx拒绝连接的页面，此时稍等片刻后重启路由器即可    
     
EdgeRouter全版本汉化工具   
原载于https://bbs.ui.com.cn/t/edgerouter/49395     
字典库目前还不够完善，需要更多的人参与维护    
#######分###########割#############线#############   
Simplified-Chinese-Edgerouter-Translater include a translater as well as a dictionary which is not complete,aiming to add Simplified Chinese interface to edgerouter
