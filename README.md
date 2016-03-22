# Chapter1 - Task3 - Vizards
> 百度IFE - 第一阶段 - 任务3 - 三栏式布局

### 任务描述
- 使用 HTML 与 CSS 按照下图实现三栏式布局。
   ![三栏式布局图](http://7xrp04.com1.z0.glb.clouddn.com/task_1_3_1.png)
- 左右两栏宽度固定，中间一栏根据父元素宽度填充满，最外面的框应理解为浏览器。
  背景色为 #eee 区域的高度取决于三个子元素中最高的高度。

### 参考资料
- [MDN：position](https://developer.mozilla.org/zh-CN/docs/Web/CSS/position)：了解 CSS position 属性的基本知识
- [MDN：float](https://developer.mozilla.org/zh-CN/docs/Web/CSS/float)：了解 CSS float 属性的基本知识
- [Learn CSS Positioning in Ten Steps](http://www.barelyfitz.com/screencast/html-training/css/positioning/)：通过具体的例子熟悉 position 属性
- [清除浮动（clearfix hack）](http://zh.learnlayout.com/clearfix.html)：清除浮动是什么，如何简单地清除浮动
- [StackOverflow：Which method of ‘clearfix’ is best?](http://stackoverflow.com/questions/211383/which-method-of-clearfix-is-best)：清除浮动黑科技完整解读

### 实现总结
- 由于平时使用float布局较少因此这里尝试使用一下float布局
- 清除浮动的兼容ie6方案
  ```
  .clearfix {
    overflow: auto;
    zoom: 1;
  }
  ```
- 在HTML中，使用float的div应该在没有使用float的div前面，否则就会出现没有float的div“被换行”

### 任务完成情况
- [x] 代码实现
- [x] 任务总结
- [x] 任务提交
