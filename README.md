#### 目前的任务和计划

**eva textBox文本显示框组件加载效果 - V0**
1. 可以配置 标题/内容文字（可分段）/字体以及边框颜色
2. 加载边框动画
3. 添加打字机效果
4. 添加抖屏效果/抖音三色字体扩散效果

**eva startLoading组件加载效果 - V0**
1. 初始化加载页面使用驾驶舱信息构建效果 - 类似与钢铁战衣启动效果
2. 加载进度条使用 充能进度条展示（支持多线程进度条展示效果）
3. 加载完成动画时 使用光波轰击效果完成白屏过渡

**eva button按钮组件动态优化方案参考1**
1. https://kentatoshikura.com/project/fil/
   1. 这个页面主要参考 其按钮变化效果与鼠标位置结合--其实就是ipad 鼠标指针的效果
   2. 其次在于使用大规模按钮时，自身触发效果可以基于鼠标位置而改变
   3. 按钮的加载效果需要另外制作，保持eva风格

**eva navBar导航栏组件 - V0**
1. 包裹eva button(默认)
2. 可以动态编辑
3. 注入到this作为公用函数使用
4. 添加消息提示组件