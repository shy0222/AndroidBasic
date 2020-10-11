一、常用基本控件
1.TextView:
.android:id属性代表着TextView的Id,也就是TextView的唯一标示，在java代码中我们可以通过findViewById()方法来通过Id获取控件。上述控件的唯一id为name_text_view。
(2).android:layout_width属性代表着控件的宽度，该属性的值是match_parent, 表示该控件的宽度与父视图的宽度相同。
(3).android:layout_height属性代表着控件的高度，该属性的值是wrap_content,表示控件的高度根据内容的高度进行改变。
(4).android:gravity属性代表着TextView中文字对齐方式，有多种方式，我们在此选的是center,居中显示。
(5).android:textSize属性代表着TextView中文字的型号，也就是文字的大小。
(6).android:textColor属性设置的是TextView中文字的颜色，属性值是16进制的色值。
(7).android:text属性就是用来设置TextView显示的值的。 
2.Button:
在Activity的类中也是使用findViewById来通过Id获取该按钮，获取按钮后我们需要给按钮绑定点击事件。也就是点击按钮要做的事情，下方给出了两中方式，一种是块的形式，一种是委托代理的形式。
3.EditText:
1).android:hint属性后边是一个字符串，其实就是用来占位用的字符串，功能是提示用户该输入框是干嘛的，在iOS开发中叫做Placeholder。
(2).android:macLines 用来设置输入框的最大行数。
二、四大布局方式
1. LinearLayout (线性布局)
2.RelativeLayout (相对布局)
3.帧布局 (FrameLayout)
4、表格布局（TableLayout）
