# Android智能下拉刷新框架-SmartRefreshLayout

[![License](https://img.shields.io/badge/License%20-Apache%202-337ab7.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Arsenal](https://img.shields.io/badge/Arsenal%20-%20SmartRefresh-4cae4c.svg)](https://android-arsenal.com/details/1/6001)
[![JCenter](https://img.shields.io/badge/%20JCenter%20-1.1.0-5bc0de.svg)](https://bintray.com/scwang90/maven/SmartRefreshLayout/_latestVersion)
[![MinSdk](https://img.shields.io/badge/%20MinSdk%20-%2012%2B%20-f0ad4e.svg)](https://android-arsenal.com/api?level=12)
[![Methods](https://img.shields.io/badge/Methods%20%7C%20Size%20-%20784%20%7C%20121%20KB-d9534f.svg)](http://www.methodscount.com/?lib=com.scwang.smartrefresh%3ASmartRefreshLayout%3A1.0.4)

<!-- [![Platform](https://img.shields.io/badge/Platform-Android-f0ad4e.svg)](https://www.android.com) -->
<!-- [![Author](https://img.shields.io/badge/Author-scwang90-11bbff.svg)](https://github.com/scwang90) -->

## [English](https://github.com/scwang90/SmartRefreshLayout/blob/master/README_EN.md) | 中文

SmartRefreshLayout以打造一个强大，稳定，成熟的下拉刷新框架为目标，并集成各种的炫酷、多样、实用、美观的Header和Footer。
正如名字所说，SmartRefreshLayout是一个“聪明”或者“智能”的下拉刷新布局，由于它的“智能”，它不只是支持所有的View，还支持多层嵌套的视图结构。
它继承自ViewGroup 而不是FrameLayout或LinearLayout，提高了性能。
也吸取了现在流行的各种刷新布局的优点，包括谷歌官方的 [SwipeRefreshLayout](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html)，
其他第三方的 [Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh)、[TwinklingRefreshLayout](https://github.com/lcodecorex/TwinklingRefreshLayout) 。
还集成了各种炫酷的 Header 和 Footer。

注：本库也在开源中国上开源，如果有时候github出现下载缓慢问题可以转到[开源中国](https://gitee.com/scwang90/SmartRefreshLayout)下载或clone，记得star哦.

## 特点功能:

 - 支持[横向刷新](https://github.com/scwang90/SmartRefreshHorizontal)
 - 支持多点触摸
 - 支持淘宝二楼和二级刷新
 - 支持嵌套多层的视图结构 Layout (LinearLayout,FrameLayout...)
 - 支持所有的 View（AbsListView、RecyclerView、WebView....View）
 - 支持自定义并且已经集成了很多炫酷的 Header 和 Footer.
 - 支持和 ListView 的无缝同步滚动 和 CoordinatorLayout 的嵌套滚动 .
 - 支持自动刷新、自动上拉加载（自动检测列表惯性滚动到底部，而不用手动上拉）.
 - 支持自定义回弹动画的插值器，实现各种炫酷的动画效果.
 - 支持设置主题来适配任何场景的 App，不会出现炫酷但很尴尬的情况.
 - 支持设多种滑动方式：平移、拉伸、背后固定、顶层固定、全屏
 - 支持所有可滚动视图的越界回弹
 - 支持 Header 和 Footer 交换混用
 - 支持AndroidX

## 传送门

 - [属性文档](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_property.md)
 - [常见问题](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_faq.md)
 - [智能之处](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_smart.md)
 - [更新日志](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_update.md)
 - [博客文章](https://segmentfault.com/a/1190000010066071)
 - [源码下载](https://github.com/scwang90/SmartRefreshLayout/releases)
 - [多点触摸](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_multitouch.md)
 - [自定义Header](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_custom.md)

## Demo
[下载 APK-Demo](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/app-debug.apk)

![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/png_apk_rqcode.png)

#### 项目演示
|个人首页|微博列表|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_practive_weibo.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_practive_feedlist.gif)|

|餐饮美食|个人中心|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_practive_repast.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_practive_profile.gif)|

#### 样式演示 Style
|Delivery|DropBox|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_Delivery.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_Dropbox.gif)|
|[Refresh-your-delivery](https://dribbble.com/shots/2753803-Refresh-your-delivery)|[Dropbox-Refresh](https://dribbble.com/shots/3470499-DropBox-Refresh)|

上面这两个是我自己实现的，下面的是我把github上其它优秀的Header进行的整理和集合还有优化：

|BezierRadar|BezierCircle|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_BezierRadar.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_BezierCircle.gif)|
|[Pull To Refresh](https://dribbble.com/shots/1936194-Pull-To-Refresh)|[Pull Down To Refresh](https://dribbble.com/shots/1797373-Pull-Down-To-Refresh)|

|FlyRefresh|Classics|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_FlyRefresh.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_Classics.gif)|
|[FlyRefresh](https://github.com/race604/FlyRefresh)|[ClassicsHeader](#1)|

|Phoenix|Taurus|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_Phoenix.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_Taurus.gif)|
|[Yalantis/Phoenix](https://github.com/Yalantis/Phoenix)|[Yalantis/Taurus](https://github.com/Yalantis/Taurus)

|BattleCity|HitBlock|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_BattleCity.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_HitBlock.gif)|
|[FunGame/BattleCity](https://github.com/Hitomis/FunGameRefresh)|[FunGame/HitBlock](https://github.com/Hitomis/FunGameRefresh)

|WaveSwipe|Material|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_WaveSwipe.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_Material.gif)|
|[WaveSwipeRefreshLayout](https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout)|[MaterialHeader](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html)

|StoreHouse|WaterDrop|
|:---:|:---:|
|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_StoreHouse.gif)|![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/gif_WaterDrop.gif)|
|[CRefreshLayout](https://github.com/cloay/CRefreshLayout)|[WaterDrop](https://github.com/THEONE10211024/WaterDropListView)


看到这么多炫酷的Header，是不是觉得很棒？这时你或许会担心这么多的Header集成在一起，但是平时只会用到一个，是不是要引入很多无用的代码和资源？
请放心，我已经把刷新布局分成三个包啦，用到的时候自行引用就可以啦！

 - SmartRefreshLayout 刷新布局核心实现，自带ClassicsHeader（经典）、BezierRadarHeader（贝塞尔雷达）两个 Header.
 - SmartRefreshHeader 各种Header的集成，除了Layout自带的Header，其它都在这个包中.
 - SmartRefreshFooter 各种Footer的集成，除了Layout自带的Footer，其它都在这个包中.

## 简单用例
#### 1.在 build.gradle 中添加依赖

[【V2.0.0】](https://github.com/scwang90/SmartRefreshLayout/tree/master#%E7%AE%80%E5%8D%95%E7%94%A8%E4%BE%8B) 版本已经在开发，主要是对各个功能类进行分包，比如不用二级刷新就不依赖，避免代码冗余，欢迎大家来体验

```
implementation 'com.scwang.smartrefresh:SmartRefreshLayout:1.1.0'  //1.0.5及以前版本的老用户升级需谨慎，API改动过大
implementation 'com.scwang.smartrefresh:SmartRefreshHeader:1.1.0'  //没有使用特殊Header，可以不加这行

```
如果使用 AndroidX 在 gradle.properties 中添加

```
android.useAndroidX=true
android.enableJetifier=true

```

#### 2.在XML布局文件中添加 SmartRefreshLayout
```xml
<?xml version="1.0" encoding="utf-8"?>
<com.scwang.smartrefresh.layout.SmartRefreshLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/refreshLayout"
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    <android.support.v7.widget.RecyclerView
        android:id="@+id/recyclerView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:overScrollMode="never"
        android:background="#fff" />
</com.scwang.smartrefresh.layout.SmartRefreshLayout>
```

#### 3.在 Activity 或者 Fragment 中添加代码
```java
RefreshLayout refreshLayout = (RefreshLayout)findViewById(R.id.refreshLayout);
refreshLayout.setOnRefreshListener(new OnRefreshListener() {
    @Override
    public void onRefresh(RefreshLayout refreshlayout) {
        refreshlayout.finishRefresh(2000/*,false*/);//传入false表示刷新失败
    }
});
refreshLayout.setOnLoadMoreListener(new OnLoadMoreListener() {
    @Override
    public void onLoadMore(RefreshLayout refreshlayout) {
        refreshlayout.finishLoadMore(2000/*,false*/);//传入false表示加载失败
    }
});
```

## 使用指定的 Header 和 Footer

#### 1.方法一 全局设置
```java
public class App extends Application {
    //static 代码段可以防止内存泄露
    static {
        //设置全局的Header构建器
        SmartRefreshLayout.setDefaultRefreshHeaderCreator(new DefaultRefreshHeaderCreator() {
                @Override
                public RefreshHeader createRefreshHeader(Context context, RefreshLayout layout) {
                    layout.setPrimaryColorsId(R.color.colorPrimary, android.R.color.white);//全局设置主题颜色
                    return new ClassicsHeader(context);//.setTimeFormat(new DynamicTimeFormat("更新于 %s"));//指定为经典Header，默认是 贝塞尔雷达Header
                }
            });
        //设置全局的Footer构建器
        SmartRefreshLayout.setDefaultRefreshFooterCreator(new DefaultRefreshFooterCreator() {
                @Override
                public RefreshFooter createRefreshFooter(Context context, RefreshLayout layout) {
                    //指定为经典Footer，默认是 BallPulseFooter
                    return new ClassicsFooter(context).setDrawableSize(20);
                }
            });
    }
}
```

注意：方法一 设置的Header和Footer的优先级是最低的，如果同时还使用了方法二、三，将会被其它方法取代


#### 2.方法二 XML布局文件指定
```xml
<com.scwang.smartrefresh.layout.SmartRefreshLayout
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:id="@+id/refreshLayout"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#444444"
    app:srlPrimaryColor="#444444"
    app:srlAccentColor="@android:color/white"
    app:srlEnablePreviewInEditMode="true">
    <!--srlAccentColor srlPrimaryColor 将会改变 Header 和 Footer 的主题颜色-->
    <!--srlEnablePreviewInEditMode 可以开启和关闭预览功能-->
    <com.scwang.smartrefresh.layout.header.ClassicsHeader
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
    <TextView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:padding="@dimen/dimenPaddingCommon"
        android:background="@android:color/white"
        android:text="@string/description_define_in_xml"/>
    <com.scwang.smartrefresh.layout.footer.ClassicsFooter
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
</com.scwang.smartrefresh.layout.SmartRefreshLayout>
```

注意：方法二 XML设置的Header和Footer的优先级是中等的，会被方法三覆盖。而且使用本方法的时候，Android Studio 会有预览效果，如下图：

![](https://github.com/scwang90/SmartRefreshLayout/raw/master/art/jpg_preview_xml_define.jpg)

不过不用担心，只是预览效果，运行的时候只有下拉才会出现~

#### 3.方法三 Java代码设置
```java
final RefreshLayout refreshLayout = (RefreshLayout) findViewById(R.id.refreshLayout);
//设置 Header 为 贝塞尔雷达 样式
refreshLayout.setRefreshHeader(new BezierRadarHeader(this).setEnableHorizontalDrag(true));
//设置 Footer 为 球脉冲 样式
refreshLayout.setRefreshFooter(new BallPulseFooter(this).setSpinnerStyle(SpinnerStyle.Scale));
```

#### 4.更多使用说明

 - [属性文档](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_property.md)
 - [常见问题](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_faq.md)
 - [自定义Header](https://github.com/scwang90/SmartRefreshLayout/blob/master/art/md_custom.md)

## 混淆

SmartRefreshLayout 没有使用到：序列化、反序列化、JNI、反射，所以并不需要添加混淆过滤代码，并且已经混淆测试通过，如果你在项目的使用中混淆之后出现问题，请及时通知我。

## 赞赏

如果你喜欢 SmartRefreshLayout 的设计，感觉 SmartRefreshLayout 帮助到了你，可以点右上角 "Star" 支持一下 谢谢！ ^_^

#### 友情链接
[github/faith-hb/WidgetCase](https://github.com/faith-hb/WidgetCase)  
[github/Bamboy120315/Freedom](https://github.com/Bamboy120315/Freedom)  
[github/TommyLemon/APIJSON](https://github.com/TommyLemon/APIJSON)  
[github/dengyuhan](https://github.com/dengyuhan)  
[github/zrp2017](https://github.com/zrp2017)  
[github/fly803/BaseProject](https://github.com/fly803/BaseProject)  
[github/razerdp](https://github.com/razerdp)  
[github/SuperChenC/s-mvp](https://github.com/SuperChenC/s-mvp)  
[github/KingJA/LoadSir](https://github.com/KingJA/LoadSir)  
[github/jianshijiuyou](https://github.com/jianshijiuyou)  
[github/zxy198717](https://github.com/zxy198717)  
[github/addappcn](https://github.com/addappcn)  
[github/RainliFu](https://github.com/RainliFu)  
[github/sugarya](https://github.com/sugarya)  
[github/stormzhang](https://github.com/stormzhang)

## 感谢
[SwipeRefreshLayout](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html)  
[Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh)  
[TwinklingRefreshLayout](https://github.com/lcodecorex/TwinklingRefreshLayout)  
[BeautifulRefreshLayout](https://github.com/android-cjj/BeautifulRefreshLayout)

License
-------

    Copyright 2017 scwang90

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
