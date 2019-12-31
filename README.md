# mo-cli

使用 python setup.py install 安装
# 使用文档
### CLI目前有以下功能：
1.	登录
2.	查看项目列表
3.	新建项目
4.	删除项目
5.	查看项目文件
6.	上传下载项目文件
7.	查看某项目下的Job列表
8.	查看某个具体Job的Log
9.	创建一个Job
10.	终止一个Job

### 1.	登录
输入mo auth, CLI将会要求输入用户名以及密码，一次登录成功后，使用同账号将不需要再次登录。例如 
注意CLI其他所有功能均需要登录
![](https://imgbed.momodel.cn/denglu.png)
### 2.	查看项目列表
如已登录，输入mo list-project将会打印目前该账号下所有项目的信息，例如下图 
![](https://imgbed.momodel.cn/chakanxiangmu.png)
### 3.	新建项目
如已登录，输入mo create-project将会在该账号下新建一个项目，例如 
![](https://imgbed.momodel.cn/xinjianxiangmu.png)
### 4.	删除项目
如已登录，输入mo delete-project project-id将会删除id为project-id的项目，例如 
![](https://imgbed.momodel.cn/shanchuxiangmu.png)
### 5.	查看项目文件
如已登录，输入mo view-project-file project-id将会显示id为project-id的项目下的文件，例如 
![](https://imgbed.momodel.cn/xiangkanxiangmuwenjina.png)
### 6.	上传下载项目文件
如已登录，输入mo upload-file project-id file-path即可上传路径为file-path的文件至id为project-id的项目下，例如 
![](https://imgbed.momodel.cn/shangchaunxiazaiwenjian.png)
### 7.	查看某项目下的Job列表
如已登录，输入mo view-job, CLI将提示用户输入项目类型与项目ID，提交后将会显示该项目下目前的Job列表，例如
 ![](https://imgbed.momodel.cn/chakanxianjobliebiao.png)
### 8.	查看某个Job的Log
如已登录，输入mo view-job-log JOB_ID后，即可查看ID为JOB_ID的Job的Log,例如 
![](https://imgbed.momodel.cn/chakanjobdelog.png)
### 9.	创建一个Job
如已登录，输入mo create-job, 分别根据提示填写项目ID，项目类型，脚本路径，运行环境以及可选的额外参数与Job file后，即可创建一个新的Job
 ![](https://imgbed.momodel.cn/chuangjianjob.png)
### 10.		终止一个Job
如已登录，输入mo terminate-job JOB_ID后便可终止ID为JOB_ID的Job,例如
![](https://imgbed.momodel.cn/zhongzhijob.png)
