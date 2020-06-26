# pi-wifi6-nas
NAS与WiFi6+究竟能擦出怎样的火花？ 如何让“派”告别吃灰的尴尬处境？ 千兆带宽“无限制”

# 1 似曾相识的场景
不知道关注我的小伙伴们有没有如下体验。

 - **学习工作**：
 	- 为了便于PDF文档资料移动查阅，进行麻烦的电脑导入手机平板的操作，浪费时间；
 	- 多文档因多处备份，而由此进一步出现的多备份不同步的场景（网速无限用云备份的请绕道）；
 	- 与同学好友共享的资料因体积太大，出现如下尴尬的提示。![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626214850812.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center =280x175)
 	- 好友索要巨大体积的软件安装包，既浪费好友的时间，也浪费自己的时间精力，正可谓“一箭双雕”呀！
 		- 机械硬盘弹出、弹出、弹出...
 		- 机械硬盘插入、识别、拷贝---------11%--------12%、弹出、弹出、弹出...
 		- 机械硬盘插入、识别、识别、识别、拷贝---------11%--------12%；
 	-  ...。
- **生活娱乐**
	 - 在PT上下载了4K电影，同时为了舒服想躺在床上看，可是手机的容量捉襟见肘；
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626215755198.png#pic_center =400x70)
	- 舍友想要小电影资源，需要不少时间精力去分享——同理巨大体积的安装包共享；
	- 用PT下载个高清电影还得考虑一会那巨低的分享率，啊！！！我的PT因为分享率过低被封号了wuwuwu。
	- ...。
- **资源回收**
	- 你的树莓派、rock派、香蕉派、橙子派等各种😋的派，吃灰良久，眼泪汪汪等着你开发利用（最好具备USB3.0与千兆以太网）；
	![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626220836128.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center)
	- 笔记本更新换代多次，看着替换下来的**数枚**机械硬盘，而找不到合适的应用场景😡。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626221428821.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center)

隐忍数年，“巧遇”疫情，抓住“机遇”，于是乎趁机创造解决如上场景的小平台，暂命名为**迷你PT仓库**
这个是我的第一版部分硬件预览图
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020062622311518.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center)

**注：上述仅仅是个人部分粗鄙的体验，不全面不合理之处还望不吝赐教。**

# 2 迷你PT仓库原型机

 - **整体硬件效果**
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626210621458.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center =600x800)

	**注：上面的展示用的是第二版电路，最高可扩展5盘，目前仅支持2.5寸**

 - **Windows端的硬盘挂载情况**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626210619813.png#pic_center)
 - **手机端的硬盘挂载情况**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626225804836.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center =300x350)
**手机OS**：我的容量可以超乎你想象，通过网络扩展上百T都没问题😜。

 - **WiFi6连接状态**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626210619864.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center =340x420)

 - **树莓派挂载的机械硬盘的IO状况**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626210619838.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center)

 - **实际的文件传输效果**
	 - 从**迷你PT仓库** **读取**文件
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626210619951.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center)


 	- **写入**文件到**迷你PT仓库**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626210619948.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center)
 	- **迷你PT仓库**挂载硬盘实际的读取性能
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200626210619935.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center)

**WiFi6压榨了机械硬盘全部IO性能，同时也基本是千兆以太网口的极限，与你的移动硬盘对比下，说不定还没有那么快呢。**

注：不建议从远程终端的大型安装包，进行安装文件，不信的话，可以体会一下。




# 3 开源内容
目前能开源的

 - 软件：传输协议是现成的，主要是samba配置优化，网上分享的大都是不全面的，小白很容易进坑里，而不知其所以然。
 - 硬件：需要的各种材料，以及PCB源码。

未来设想的功能

 - 添加温湿度传感器、喇叭、红外发射器、UPS电源等组件，使之成为一个24H不间断工作的小终端。
 - 添加智能语音识别模块，实现基本的语音交互控制，电影音乐推荐及下载。
 - ...。

以上功能仅仅是个人设想，需要时间与机会逐渐将如上功能变成现实，如果有小伙伴们有想法，欢迎后台私聊。


**看完后，是不是有点心动呢？如何DIY一款属于自己的高性能NAS，让你的🥧告别吃灰的命运呢？那么就关注本公众号未来的推送。**


<br />
<br />

**原创不易，严禁剽窃！**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918110341834.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1NzEyMTY5,size_16,color_FFFFFF,t_70#pic_center  =200x200)


欢迎大家关注我创建的微信公众号——小白仓库
原创经验资料分享：包含但不仅限于FPGA、ARM、RISC-V、Linux、LabVIEW等软硬件开发，另外分享生活中的趣事以及感悟。目的是建立一个平台记录学习过的知识，并分享出来自认为有用的与感兴趣的道友相互交流进步。


