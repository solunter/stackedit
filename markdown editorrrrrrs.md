为什么要折腾markdown呢？可能折腾本身就是一件趣事。。。

早在大学期间就接触到markdown，试着用来写笔记，因为很容易上手，而且又有很多editor支持渲染LaTeX公式，对于一名物理系的学生来说，这个太重要了，而且当时抱着学习LaTeX的态度，尝试使用markdown写文档，记笔记，写文章什么的。大学期间并没有折腾太多，疯狂百度谷歌哪个编辑器最好用，用到的大都是作业部落。作业部落现在断断续续也在用，写简单的日志和文献阅读的笔记。

大概在17年下半年的时候，有了写博客的想法，当然也是突然的idea，并不知道自己要写什么o(╯□╰)o。当时接触到了hexo这个平台（在一通疯狂的谷歌而且纠结之后的选择，其实我也注册了wordpress，简书，账户都还在，都没管了），开始用hexo写工作日志，文献阅读的notes，对于我来说是非常有用的，而且可以简单地部署到github，生成静态博客，觉得很好玩。

基本用到的就是作业部落记录日常，hexo记录工作，一直就有些问题，其实这我使用两个平台的界限并不明显，这对于有点强迫症的我来说是挺难受的。所以想找一个囊括linux，ios，Android平台的markdown编辑器，然后就只用那一个平台就好了。好，接下来就又是疯狂的谷歌了。。。

>不作世界永远会太平

## Joplin
最先找到的是[Joplin](https://github.com/laurent22/joplin)这个平台。是真的各个平台都有！github这个项目上面显示的contributor就`lartent22`一个人，牛逼地不行啊！

愉快地clone下来，然后安装，不记得有没有遇到问题了（虽然就是昨天的事情）。在terminal下是command模式，可以，很geek！
 
 ![Joplin](https://lh3.googleusercontent.com/Vg_0rnnFmE0mX-QA3bNYzd20Sa7ZftHNF_6V1bH80VFT543Na1JaWr7LM4uEi_5Tc-eJ0ipzD25K)

就在摸索Joplin的时候，我学到了可以用Dropbox作为云端，实现文档共享，即使是不同的软件平台也可以做到。如果想实现pad和手机上也能查看文档，Joplin就只能利用Dropbox。Joplin还有linux的桌面版，真的很全面了。我在Android手机和pad上装好了以后，挂上VPN算才能与Dropbox关联上了，而且同步很慢，可能因为我在国内？但是linux下，command模式和桌面模式都打死没有办法与Dropbox关联，这就难过了！我不得不放弃Joplin，希望后续会解决这些问题。另外Joplin的app体验也还比较不错，简洁但不简单，我估计作者缺人手，一个人维护这么多怎么搞得过来。。。
*（写着写着，这stackedit导入照片有点麻烦，得通过Google Drive传）*

## Boostnote
Boostnote也是全平台支持，看主页有很多开发者合作。boostnote是可以支持Dropbox云同步的,但是app的体验也太差劲了,都比不上Joplin,UI丑,仿佛是十几年前的应用,功能很有限,还有就是保存到Dropbox里的是`.cson`文件,不是很懂, 也不方便移植．不过他们有个社区[boostlog](https://boostlog.io/)，我有关注他们的fb，会看到一些关于编程的分享．

在linux平台上，如果想联动Dropbox, 在Dropbox文件夹和boostnote默认储存note的文件夹之间建立软链接就可以了, 这样在boostnote里保存的note就会自动同步到Dropbox, 还是挺方便的. 后面用到的VNote就是这么干的. 

关注一下后续发展, 期待变得更好用. 

## VNote
依据作者, VNote的设计灵感来自vim. 在linux里选择的编辑器就是VNote, 默认保存的note文件软链接到Dropbox本地文件夹, 一旦有更新就会自动同步到Dropbox云端(当然需要网络支持). 

VNote的几个默认主题渲染效果其实不是很满意, 强迫症又犯了, 昨天写着写着笔记, 觉得代码高亮太丑, 去[Highlight.js](https://highlightjs.org/)下载了几种样式, 顺带找了些阅读模式的渲染样式, 但是直接使用会出现彼此冲突, 效果奇丑无比. 最好的方式是去改默认的主题, 当然这就又是另外一个故事了, 将来再折腾吧......

## Stackedit



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MzkyOTIzNzIsODMxMzExOTM4LC01OD
U4MTQyNSwxNjk3NTE1NzM2LDgyNjg3MDU1XX0=
-->