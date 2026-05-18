标题： 尝试用Uncle城的模板做树链剖分详解

内容：

​上个月 @网络小白_Uncle城 大佬开源了他的html PPT模板，但我昨晚才终于成功抽出时间试用了一下。最初版的Prompt非常简单（发给qwen网页端），如下：

大佬，你是一名专家前端工程师，精通前端工程化。请参考下面这个html PPT的UI风格，制作一个html PPT，介绍树链剖分算法。
技术栈：React、Tailwind CSS。输出单个html文件。

用于参考的html PPT完整代码：

// web_animation\PPT Template-level2\1.html 完整代码 

令人惊讶的是，第一版PPT就和图里的样子差不多了。不过因为模型能力的限制，里面的不少文案、两棵树的示意图（llm用svg画的）和代码都有错误。简单修复这些错误后就是图里的样子了。

html PPT传送门： http://github.com/Hans774882968/web_ppt_animation/blob/main/web_animation/%E6%A0%91%E9%93%BE%E5%89%96%E5%88%86%E7%AE%97%E6%B3%95%E8%AF%A6%E8%A7%A3.html

PS：
1. 氵这篇动态主要是为了激励自己多尝试新工具
2. PPT的文案主要是llm写的，直接拿来做知识教学肯定是不行的。如果要用于教学，需要把人类写好的旁白发给llm，让llm在约束下工作。如果里面有什么知识性错误，欢迎大佬指出~
