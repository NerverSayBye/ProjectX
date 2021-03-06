# ProjectX
![ICON](https://raw.githubusercontent.com/AlexMofer/ProjectX/master/ProjectX.png)

整体项目合集，包括Widget、Drawable以及一些工具类。
## Widget
- [***BaseTabStrip***](https://github.com/AlexMofer/ProjectX/tree/master/basetabstrip)

    TabStrip基础类，其实现了类似于PagerTabStrip的一些基础方法，继承该类型并实现相应方法达到自定义的PagerTabStrip同类型的效果。
- [***GradientTabStrip***](https://github.com/AlexMofer/ProjectX/tree/master/gradienttabstrip)

    继承自BaseTabStrip，实现微信式渐变底部Tab效果
- [***TagTabStrip***](https://github.com/AlexMofer/ProjectX/tree/master/tagtabstrip)

    继承自BaseTabStrip，实现ViewPager滚动标记点
- [***IndicatorTabStrip***](https://github.com/AlexMofer/ProjectX/tree/master/indicatortabstrip)

    继承自BaseTabStrip，移动式下标渐变缩放Tab，Item不建议超过5个
- [***ShapeImageView***](https://github.com/AlexMofer/ProjectX/tree/master/shapeimageview)

    图形裁剪ImageView，API 21 及以上 使用 View.setOutlineProvider(ViewOutlineProvider) 方式实现，API 18 及以上 使用 Canvas.clipPath(Path) 方式实现，API 18 以下   使用 Paint.setXfermode(Xfermode) 方式实现（使用的是PorterDuffXfermode），均支持动态图；支持固定高宽缩放比缩放，支持前景Drawable，支持ImageView的所有ScaleType
- [***StateFrameLayout***](https://github.com/AlexMofer/ProjectX/tree/master/stateframelayout)

    状态帧布局，通常用于网络请求的四种状态，普通、载入、错误、空白。支持Drawable或者View来展示，也可以混搭
- [***WrapLayout***](https://github.com/AlexMofer/ProjectX/tree/master/wraplayout)

    自动换行布局，支持不等长不等宽子项，且可以设置垂直间距与水平间距及子项对齐模式
- [***ReplaceLayout***](https://github.com/AlexMofer/ProjectX/tree/master/replacelayout)

    交替布局，配合TabStrip使用，达到伴随ViewPager动作而进行改变的效果
- [***DrawableRatingBar***](https://github.com/AlexMofer/ProjectX/tree/master/drawableratingbar)

    双图片评级控件，可设置图片间距，支持拖动进度及点击进度，可控制最大值最小值，及是否可手动。
- [***HeaderFooterGridView***](https://github.com/AlexMofer/ProjectX/tree/master/headerfootergridview)

    头尾GridView，支持AUTO_FIT模式，头尾模式有两种，无反射代码。
- [***MultiActionTextView***](https://github.com/AlexMofer/ProjectX/tree/master/multiactiontextview)

    文字可点击TextView，设置文字部分可点击，点击执行不同操作。
- [***SelectionView***](https://github.com/AlexMofer/ProjectX/tree/master/selectionview)

    快速跳选，常用于联系人列表快速选取。
- [***CircleProgressBar***](https://github.com/AlexMofer/ProjectX/tree/master/circleprogressbar)

    带载入动画的环形进度条，可高度配置，支持配置成表盘。
- [***ZxingScanView***](https://github.com/AlexMofer/ProjectX/tree/master/zxingscanview)

    一个View实现zxing条码扫描视图。
- [***SmoothInputLayout***](https://github.com/AlexMofer/ProjectX/tree/master/smoothinputlayout)

    仿微信式，平滑输入面板，防止键盘的出现与消失导致特殊输入面板的顶起与塌陷。
## Drawable
- [***DoubleCircleDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)

    双圈动图，用于载入提示。
- [***CirclingDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)

    外围小点转圈动图。
- [***CenterDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)

    中心图片，背景可绘制形状，一般用于ImageView的src，保证缩放后，中心的Drawable不变形。用于一般background属性的话，无需使用本控件，直接使用layer-list来定义即可。
- [***CombinationDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)

    双层图片，与CenterDrawable类似，背景为另一Drawable，一般用于ImageView的src，保证缩放后，中心的Drawable不变形。用于一般background属性的话，无需使用本控件，直接使用layer-list来定义即可。
- [***CornerDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)
    
    尖角框，使用该Drawable时，会改变View的Padding值。
- [***LineDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)

    横线图片，主要是底色为透明或半透明色时有用，为不透明时，通过layer-list即可实现。
- [***LinearDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)
    
    线性图片，多张图片排列，支持设置间隔，主要用于替代多个ImageView排列，节省性能。
- [***TextDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)
    
    文字图片。
- [***CircleExpandDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)
    
    圆圈扩大图片。
- [***MaterialProgressDrawable***](https://github.com/AlexMofer/ProjectX/tree/master/drawable)

    SwipeRefreshLayout载入动图。

## Other
- [***Printer***](https://github.com/AlexMofer/ProjectX/tree/master/printer)

    标准ES-POS命令打印，固定IP或蓝牙打印，支持黑白图片打印
- [***Security***](https://github.com/AlexMofer/ProjectX/tree/master/security)

    加密解密，主要为3DES、AES、RSA加密算法的整理
- [***Support***](https://github.com/AlexMofer/ProjectX/tree/master/support)

    支持包

## Demo
[<img src="https://play.google.com/intl/zh_cn/badges/images/apps/en-play-badge.png" width="164px" height="48px" />](https://play.google.com/store/apps/details?id=am.project.x)[<img src="https://raw.githubusercontent.com/AlexMofer/ProjectX/master/release/ic_download.png" height="45px" />](https://raw.githubusercontent.com/AlexMofer/ProjectX/master/release/ProjectX.apk)