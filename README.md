# git中的宇宙
git中的宇宙

一、这里是哪里
这里是哪里？
要回答这个问题，首先要定义“这里”。为了简单起见，我们姑且把“这里”认为是本文档（README.MD）。
然后要定义“哪里”。“哪里”表示一种唯一化的称谓，当咱们交流时，使用该称谓，互相间就能明白所指的是这个东西——“这里”。

二、名字
最简单的开始，咱们会把“这里”称为“READMI.MD”——这里是README.MD。
啊哈，没错，这里就是README.MD，当我说README.MD时，你知道我说的是本文档，也就是“这里”。同理，当我说“隔壁老王家”的时候，你知道我说的是本文档所在目录下那个名字叫“隔壁老王家”的目录。
这就是一维空间，咱们只需要一个坐标就可以唯一确定一个地方。
一切是如此简单明了，和谐美好。

三、目录
忽然有一天，咱们发现“隔壁老王家”里面竟然也有一个README.MD。当咱们谈论起“README.MD”时，当咱们读到这一段时，隔壁老王会迷惘地问：“README.MD里面没有你们说的东西啊？”
这时问题来了，“这里”还是这里，但是“README.MD”却不一定说的是“这里”了——一维坐标不够用了。
咱们注意到目录路径。咱们可以定义本文档所在目录叫“根目录”，隔壁老王所在的目录“隔壁老王家”叫“根目录下的隔壁老王家目录”。老王说字太多了记不住，所以咱们通常用符号“/”来进行分隔简化，根目录就是“/”，“根目录下的隔壁老王家目录”就是“/隔壁老王家/”。如此，我们可以称呼本文档为“/README.MD”，称呼隔壁老王家的README.MD为“/隔壁老王家/README.MD”。
于是咱们迎来了二维坐标。注意，“/README.MD”只是在计算机科学领域的写法上连在了一起，用数学领域的写法，这个二维坐标是“( /, README.MD )”，同理，“/隔壁老王家/README.MD”的数学领域写法为“( /隔壁老王家/ , README.MD )”——这里的维度咱们按中国人的习惯从大写起。
另外，请暂时忽略目录的包含关系。如果实在感觉怪异，可以想象一条一维数轴，0为原点，从0到坐标2，岂不是得经过坐标1？目录结构跟这个原理是一样的，所谓的“包含”只不过是一种“路过”——要进入“/隔壁老王家/”，就得路过“/”。
没错，目录树就是一种二维结构。

四、版本
忽然有一天咱们又发现了新大陆：版本——毕竟git是一个版本控制系统（VCS）。
咱们现在所在的版本的上一个版本，也有一个根目录“/”，里面也有README.MD和“隔壁老王家”，而且甚至内容都十分相似！只是“隔壁老王家”里面不是老王，而是年轻时的老王：小王。
但内容毕竟是不一样的。当咱们谈论“隔壁家的老王”时，上一个版本里的小王表示他爸爸没住这里。
哎呀，真糟糕，穿越了呢！
咱们只好把“版本”做为第三个维度。假定咱们现在所在版本为0，这时咱们谈论“隔壁家的老王”时，就变成了“版本0的/隔壁老王家/老王”，数学写法是“( 0 , /隔壁老王家/ , 老王 )”。

五、分支
git作为版本控制软件，一大特色就是分支，很容易使用的分支。
于是咱们又探索到了另一个“版本0的/隔壁老王家/老王”——另一个分支“分支a”里的“版本0的/隔壁老王家/老王”，不得不再加一个维度，以便区分咱们这里的“版本0的/隔壁老王家/老王”和“平行宇宙”里的“版本0的/隔壁老王家/老王”。这个维度很显然就是“分支”。
现在，咱们这里的“版本0的/隔壁老王家/老王”变成了“master分支的版本0的/隔壁老王家/老王”，数学写法是“( master , 0 , /隔壁老王家/ , 老王 )”。

六、现实
现在暂时停下咱们探索git宇宙的脚步来看一下，咱们有四个维度，分别是名字、目录、版本、分支。其中“版本”维度与现实中大家常提及的所谓“第四维”——时间何其相似；而“分支”维度则与科幻宇宙学中的“平行宇宙”如出一辙。剩下的两个维度对应于现实空间中的三维坐标，这就是传说中的由于比现实少一个维度的二次元，哈哈。

七、微观维度
在现实科学的主流传说中，宇宙有十几个维度，除了咱们所处的宏观世界直观可见的四维，其他的维度都蜷缩在微观中。有人说它们隐藏在普朗克尺度之内。
那么当咱们使用四维坐标 “( 现在 , 1 , 2 , 3 )”时，咱们指的究竟是什么？
是宏观宇宙中的一个“点”。
如果咱们引入更多的维度，比如“( 现在 , 1 , 2 , 3 , 4 , 5 , 6 )”，指的是什么？还是宏观宇宙中的一个“点”吗？
回到咱们的git宇宙中。
本README.MD是一个文件，在git宇宙中是一个宏观物体，它也可以分解为更细的尺度。
“这里”到底是哪里？
当咱们在这句话里提到“这里”时，还是上一句话的“这里”吗？
换句话说，本文出现了数十次“这里”这个词，指的都是同一个地方吗？
咱们一开始将“这里”定义为为本文档（README.MD），这有没有问题？
好像有点问题。如果有两只蚂蚁分别爬在两个“这里”上时，它们谈论的“这里”显然跟咱们谈论的不一样。那么它们应该如何表达才能愉快地聊天呢？
每个词的位置。
于是git宇宙的微观尺度显现出来。

八、不同的坐标系
这里咱们先暂时回到现实，还记得中学时几何课学过两种平面坐标么？一种是常用的直角坐标系，一种是极坐标系。对于平面上的同一个点，既可以用直角坐标系表达出来，也可以用极坐标系表达出来。
为啥咱们要提这个令人头疼的极坐标系？
因为它也是科学的，也是一套行之有效的坐标方案，咱们接下来观察微观维度将有异曲同工的联系。

九、词的位置
回到两只蚂蚁的世界，它们需要在前面四个维度
