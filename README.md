# 使用GITHUB作为个人图库使用说明
## 此仓库使用说明
此仓库为个人文章图库，使用github作为微博的图床，本人尊重Github作为全球代码共享的权威，本人也承若不上传除了个人博客所需图片外的其他非文章所需图片


## 图床搭建说明
图床搭建可以参考文章：[使用GitHub做免费不限流量图床](http://jingpin.jikexueyuan.com/article/36279.html) 来搭建github图床

## 如下为本人实际操作总结
### 一. 提交图片到github方便后续使用：
1. `git clone ‘此仓库url’`   #克隆此仓库到本地，如: `git clone https://github.com/yanxiangyfg/weibo_picture.git`
2. 将所需图片放入仓库，然后执行git操作进行提交：
```bash
git add  .  				#添加新增到本地仓库
git commit -m "提交日志"		#增加提交日志
git push origin master  		#提交本地修改到远程github服务器,输入github的用户名和密码能成功提交
```
### 二.获取网络图片地址，方便在微博中使用
* 点击图片，如此处点击`二叉树.png`，得到地址为：`https://github.com/yanxiangyfg/weibo_picture/blob/master/BlogPictures/%E4%BA%8C%E5%8F%89%E6%A0%91.png`
* 如上网址中，将网址中blob改为raw，然后重新回车刷新,这就是你的图片外链地址了： `https://raw.githubusercontent.com/yanxiangyfg/weibo_picture/master/BlogPictures/%E4%BA%8C%E5%8F%89%E6%A0%91.png`
* 此网址可以直接用来微博中，永久保存。
