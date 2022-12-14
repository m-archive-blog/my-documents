# 南川 Effie 使用初体验

- Effie 的官网：https://www.effie.co/

## 关于【一位大四学子兼李自然颜粉使用两小时 Effie 后的修改建议】

- 原文地址：https://www.octopath.cn/373e15d8

* 关于【加入微信分享】，agree
  - 这里涉及到微信的分享机制，需要设计一定的分享格式，技术上倒不是很难的问题，我相信 Effie 之后应该会完善的。
  - 而且 Effie 和微信也没有直接竞争关系，所以不会像拼多多微信那样被微信封杀。

- 关于【加入低频字符窗口】，dismiss
  - 这个功能需求，事实上不属于编辑器的目标需求，而是输入法的……建议可以多多研究自己的输入法，我用的搜狗输入法是有打开特殊符号面板的快捷键的（尽管我平时并不会用到……）。
- 关于【加入列表同级交互】，doubt
  - 我个人觉得支持思维导图层面操作结点的关系已经够了，原因有二：
    - 1. 思维导图层面操作结点关系更加直观，相较于在文字编辑模式内更方便。
    - 2. 某些软件的设计，就完全是编辑模式与阅览模式分离的，比如为知笔记和知名的 Vim 软件，它们注重内容的安全问题，有效防止误操作。在 Effie 的编辑模式不考虑列表顺序的调整，一方面可以减少对鼠标的依赖，另一方面也容易保护这种安全，此外，也可以减少使用者的关注点分离。总之：编辑模式就是输入文字与展示。（可以看到，Effie 的父级列表支持展开与收起，它不影响列表的内容）
- 关于【深色模式字体颜色】，doubt
  - 我觉得还好，一般到了晚上，应该是沉浸式写作的大好时机，所以基本上都会关闭侧边栏，因此就不用考虑和侧边栏色调的同一问题。此外，这个灰度还是能够有效减少对眼睛的伤害的。
  - 当然了，你说的灰色和白色的中间色，我觉得应该也可以。
- 关于【Ctrl+1 的快捷键】，doubt
  - 在流行的 Markdown 编辑软件 Typora 中，它的 Ctrl+1~6 六个快捷键能够将一段文本变成 1~6 级标题，我认为这个快捷键设置是比较合理的。
  - 在 Mac 上，目前 Effie 只配置了 Command+1，用于开启或关闭侧边栏，个人觉得相对于 Typora 来说，这个快捷键有点点奢侈……可以考虑考虑采纳 Typora 的快捷键，因为就我自己的使用体验来说，Command+1~6 快速设置段落的标题级别还是很常用的，体验很好。
  - 至于顺不顺手……这……使用习惯问题趴。
- 关于【编程软件的思路】
  - 其实不叫编程软件，而是 Markdown 规范。在 Markdown 书写语系里，N 个#号接空格后的段落就是 N 级标题，-号接空格后的段落就是无序列表，数字加点接空格后的段落就是有序列表。
  - 目前能够流畅输出 Markdown 的编辑软件很多，比较典型的是 Typora，也兼顾了审美和功能，Effie 可以说是同类产品中审美方面确实是做的最极致的，但同时，功能上也确实略有不足。
  - 期待看到“思考家”的标签能走多远，是想想而已，还是真地沉思，有待未来 Effie 的自我迭代。

## 我的使用收获与建议

- 思维导图
  - 这个必须点赞！其实吧，思维导图用过的人都知道，这玩意更适合分享而非存储，所以在 Effie 里，以文字为载体，思维导图作为附加的展示形式附庸在文字的主体上，这是一个很有趣也高明的设计。
  - 对于这款软件内为什么要支持思维导图，设计的考虑等，李自然大哥已经在宣传视频里讲的很清楚了，观点我也基本认同。
- 段落号
  - **简洁的真谛不是删去什么而是留下什么**，于是，不是行号，而是段落号，这就像一个个里程碑，稀疏地散落在自己的足迹上，兼顾了审美需求与功能需求，是非常值得肯定的。
  - 不过呢，我个人觉得，也不能如此死板，我推荐的设计是输入模式与向下滚动时是沉浸式写作，但向上滚动时，应该能够显示文章名、字符总数等基本信息，在开发层面这就是一个 Sticky Header，倒也不难实现。
  - 但个人建议空段落不计数。
- 图片

  - 尽快加入对图片的支持，还是有必要的，Markdown 刚推出来的时候也是不支持图片，目前呢？几乎没有一个主流 Markdown 编辑器、解析器、IDE 是不支持图片的。

- 留白

  - 在文章篇幅较长，超过半屏甚至一屏后，文字的输入已经到达了屏幕底部，但留给用户下方的留白并不够，我尝试了一下向上滑动，发现也滑不了。
  - 个人建议应支持滑动展示更多留白，否则只能通过多敲几个空白段落以使留白能够撑起至少三分之一的下方屏幕，但在 Effie 里这是灾难性的，因为空白段落依旧会有右边的段落号……

  * 个人建议考虑一下 Typora 支持的“打字机模式”，即始终使输入焦点保持在屏幕中间那一行，还是很有意思的。

- 总结
  - 除了不支持图片插入导致文章的整体呈现还缺少一定的表现力度之外，与留白不够导致必须插入几个空段落使目光聚焦点能够上移之外，无其他任何觉得不适之处。
  - 惊喜远大于不足，这是一款审美在线、理性与感性兼具的产品，我愿意将它作为自己持续生产的主要战场。
  - **Yes，Effie！**
- 最后
  - 感谢杜海川同学的推荐！
  - 感谢李自然大哥的创意与设计！
  - （时机成熟，我打算自己用 React Native 模仿开发一下 Effie，嘿嘿）
