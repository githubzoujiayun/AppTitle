# AppTitle
# 自适应沉浸式以及凹口屏的标题栏

# kotlin 版本
```groovy
implement 'com.xiaolei:AppTitle:1.0.1'
```
# java版本
```groovy
implement 'com.xiaolei:AppTitle-java:1.0.1'
```

![运行示意图](https://raw.githubusercontent.com/xiaolei123/AppTitle/master/src/main/res/drawable-xhdpi/img_screen3.png)

![运行示意图](https://raw.githubusercontent.com/xiaolei123/AppTitle/master/src/main/res/drawable-xhdpi/img_screen4.png)

# GPU绘制表现优秀

![运行示意图](https://raw.githubusercontent.com/xiaolei123/AppTitle/master/src/main/res/drawable-xhdpi/img_screen5.png)

# 自定义属性以及解释

```xml
<!--自定义标题栏-->
<declare-styleable name="APPTittle">
    <!--左边图片是否显示-->
    <attr name="left_img_visible" format="enum">
        <enum name="VISIBLE" value="0x00000000" />
        <enum name="INVISIBLE" value="0x00000004" />
        <enum name="GONE" value="0x00000008" />
    </attr>
    <!--左边图片-->
    <attr name="left_img" format="reference" />
    <!--左边图标的内距-->
    <attr name="left_img_padding" format="dimension" />

    <!--左边文字-->
    <attr name="left_text" format="string" />
    <!--左边文字是否显示-->
    <attr name="left_text_visible" format="enum">
        <enum name="VISIBLE" value="0x00000000" />
        <enum name="INVISIBLE" value="0x00000004" />
        <enum name="GONE" value="0x00000008" />
    </attr>
    <!--左边文字大小-->
    <attr name="left_text_size" format="dimension" />
    <!--左边文字颜色-->
    <attr name="left_text_color" format="color" />


    <!--标题左边icon是否显示-->
    <attr name="title_left_icon_visible" format="enum">
        <enum name="VISIBLE" value="0x00000000" />
        <enum name="INVISIBLE" value="0x00000004" />
        <enum name="GONE" value="0x00000008" />
    </attr>
    <!--标题左边icon-->
    <attr name="title_left_icon" format="reference" />

    <!--标题文字-->
    <attr name="title_text" format="string" />
    <!--标题文字是否显示-->
    <attr name="title_text_visible" format="enum">
        <enum name="VISIBLE" value="0x00000000" />
        <enum name="INVISIBLE" value="0x00000004" />
        <enum name="GONE" value="0x00000008" />
    </attr>
    <!--标题文字大小-->
    <attr name="title_text_size" format="dimension" />
    <!--标题文字颜色-->
    <attr name="title_text_color" format="color" />

    <!--标题右边icon是否显示-->
    <attr name="title_right_icon_visible" format="enum">
        <enum name="VISIBLE" value="0x00000000" />
        <enum name="INVISIBLE" value="0x00000004" />
        <enum name="GONE" value="0x00000008" />
    </attr>
    <!--标题右边icon-->
    <attr name="title_right_icon" format="reference" />

    <!--右边文字-->
    <attr name="right_text" format="string" />
    <!--右边文字是否显示-->
    <attr name="right_text_visible" format="enum">
        <enum name="VISIBLE" value="0x00000000" />
        <enum name="INVISIBLE" value="0x00000004" />
        <enum name="GONE" value="0x00000008" />
    </attr>
    <!--右边文字大小-->
    <attr name="right_text_size" format="dimension" />
    <!--右边文字颜色-->
    <attr name="right_text_color" format="color" />

    <!--右边图片是否显示-->
    <attr name="right_img_visible" format="enum">
        <enum name="VISIBLE" value="0x00000000" />
        <enum name="INVISIBLE" value="0x00000004" />
        <enum name="GONE" value="0x00000008" />
    </attr>
    <!--右边图片-->
    <attr name="right_img" format="reference" />
    <!--右边图片的内距-->
    <attr name="right_img_padding" format="dimension" />
    
    <!--左右两边图标的padding-->
    <attr name="left_right_img_padding" format="dimension" />

</declare-styleable>
```
