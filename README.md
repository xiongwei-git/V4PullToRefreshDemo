V4PullToRefreshDemo
===================
该代码用来展示如何使用原生V4中自带的下拉刷新控件，并且演示了不同的V4包中的下拉效果不一样。

****
###　　　　　　　　　　　　Author:Ted
###　　　　　　　　　 E-mail:xiong-wei@hotmail.com

===========================


###截图
* V4包版本  com.android.support:support-v4:21.0.2
![](https://github.com/xiongwei-git/V4PullToRefreshDemo/blob/master/screenshots/high_v4.gif)


* V4包版本  com.android.support:support-v4:19.1.0
![](https://github.com/xiongwei-git/V4PullToRefreshDemo/blob/master/screenshots/low_v4.gif)

##如何快速切换高低版本的V4包  
```Java
dependencies {
    /**高版本*/
    //compile 'com.android.support:support-v4:21.0.2'
    /**低版本*/
    compile 'com.android.support:support-v4:19.1.0'
    compile fileTree(dir: 'libs', include: ['*.jar'])
}
```
