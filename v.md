# b站视频外链
##　b站为我们提供了3种分享视频的方法 
1. 链接地址
2. flash地址 
2. Html地址
> 但是我发现,我们直接将地址复制下来之后,链接地址是一个网页,放到我自己的网页上有些不太合适,flash地址和html地址复制下来并不能够直接使用.
### 经过我查了多个资料,我发现我们可以利用 < iframe >标签引用b站的html5播放器,然后在b站中找到自己喜欢视频的cid和aid复制下来就可以了
```html
<iframe id="b" class="b video_pc" src="https://www.bilibili.com/html/html5player.html?cid=24237876&aid=14875829&pre_ad=0" frameborder="0" allowfullscreen="true">
</iframe>  
```
# cid查找方法
* 在视频页单击鼠标右键,查看网页源代码,然后ctrl+f查找cid,将cid和aid复制替换即可
# b站主站地址
> http://www.bilibili.com/index.html