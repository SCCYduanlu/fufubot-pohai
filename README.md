# fufubot_pohai

可使用这个上传迫害图片(

举例,bbs的迫害图片文件名为bbspohai-114514.jpg

那pohai.json里写的就是"bbs": "bbspohai",

如果需要创建新的关键词 直接在pohai.json内另起一行"bbs可爱"："bbspohai",

就行(

图片上传规范:

直接找原来有没有这个人的迫害图片 有 例如有黄瓜了

现在假设黄瓜有8张图 你要上传第9张

就上传上去 然后取名kwpohai-9(


## 表情包与随机迫害用图片

由于我自己的习惯原因 随机迫害的指令会放在最前面, 而表情包会放在json的最后面 而且输出迫害列表的时候会切片掉那一部分

所以请增加被迫害对象的时候注意一下文件名后面有没有pohai之类的字样 如果没有 那就是表情包 请在那个行上面起一行增加迫害对象( 因为表情包会在切片的时候切掉(

## 那种图

需要加的时候直接把文件名改成setugkd开头 然后把后面的数字加一下就可以了

## 啤酒烧烤图

在某次commit后 我在库里加上了Project Sekai Colorful Stage 目前所有的stamp的图片

目前还顺便把日服 国际服 韩服 繁体中文服的所有stamp也塞进去了

并且把除了mfy/khn这样的缩写以外的

几乎所有有可能匹配到角色的关键词全部加了进去

例如说你想匹配小豆泽

你可以使用アズサワ あずさわ azusawa 以及azusawakohane 等各种 罗马音 平假名 片假名等关键词匹配到表情包 (拼音不算嗷)

如果还是匹配不上 而你想加缩写 请手动加到表上去

缩写我真的不想写轮子做了

![](pohai/bpjskkohane_stamp0395.png)![](pohai/bpjskkohane_stamp0395_en.png)![](pohai/bpjskkohane_stamp0395_tc.png)![](pohai/bpjskkohane_stamp0395_kr.png)

