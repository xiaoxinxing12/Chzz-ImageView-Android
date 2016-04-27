:running:ChzzImageView-Android:running:
============

* 使用v4包中的RoundedBitmapDrawable实现圆角矩形、圆形
* 描边圆形
* 根据宽度确定高度的正方形

### 效果图

![Image of ChzzImageViewDemo](http://7xk9dj.com1.z0.glb.clouddn.com/imageview/ChzzImageView.jpg?imageView2/2/w/320)

### Gradle依赖 [![Maven Central](https://maven-badges.herokuapp.com/maven-central/cn.bingoogolapple/bga-imageview/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cn.bingoogolapple/bga-imageview) ***「latestVersion」指的是左边这个 maven-central 徽章后面的「数字」，请自行替换。***

```groovy
dependencies {
    compile 'com.android.support:support-v4:latestVersion'
    compile 'org.chzz.imageview:imageview:1.0.0'
}
```

### 自定义属性说明

```xml
<!-- 默认图片资源，默认为null -->
<attr name="android:src" />
<!-- 是否是圆形，默认值为false -->
<attr name="bga_iv_isCircle" format="boolean" />
<!-- 圆角矩形的半径，默认值为0dp -->
<attr name="bga_iv_cornerRadius" format="reference|dimension" />
<!-- 是否是矩形，默认值为false -->
<attr name="bga_iv_isSquare" format="boolean" />
<!-- 描边的宽度，默认值为0dp -->
<attr name="bga_iv_borderWidth" format="reference|dimension" />
<!-- 描边的颜色，默认值为Color.WHITE -->
<attr name="bga_iv_borderColor" format="reference|color" />
```

