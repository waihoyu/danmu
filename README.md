 [弹幕](https://juejin.im/post/5ae56927f265da0b7e0c0968)
> 弹幕的核心原理是什么？
 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `文章，在封面图提供一个弹幕效果，让大家的评论
 滚动输出，如果有新的评论，立即输出。`
 - 数据流  data flow
 数据可视化，以时间点为因素的弹幕，
 数据流  评论
 可视化  以弹幕的方式 
 - 技术分析  
  &#160; 评论  数组  动态
     
   &#160; 1.&nbsp;ajax fetch  
   &#160; 2.&nbsp;dom appendChild 动态dom  
   &#160; 3.&nbsp;上面一点，下面一点，弹幕之间不要重叠，随机一点，但是可控的弹幕效果。  
   &#160; 4.&nbsp;定位  
   &#160; 5.&nbsp;随机  Math.random();

