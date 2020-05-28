# MvpDemo  
MVP架构在Android的使用。
Okhttp3、Retrofit2、Rxjava3 ，AutoDispose解决RxJava内存泄漏

简书地址：https://www.jianshu.com/p/ae0b21d3238a  


2020年5月28日 15:05:09 修改

更新为AndroidX
依赖更新为当前最新版本
Autodispose 2.0 中已包含Rxjava3以及Rxjava3rxAndroid 依赖
删除Butterknife Material-dialogs  jetbrains 依赖


使用的第三方库:  
    //okhttp3
      implementation 'com.squareup.okhttp3:okhttp:4.2.0'
      implementation "com.squareup.okhttp3:logging-interceptor:3.10.0"
      //retrofit2
      implementation 'com.squareup.retrofit2:retrofit:2.9.0'
      implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
      implementation 'com.squareup.retrofit2:adapter-rxjava3:2.9.0'

      //AutoDispose解决RxJava内存泄漏
      implementation 'com.uber.autodispose2:autodispose:2.0.0'
      implementation 'com.uber.autodispose2:autodispose-android:2.0.0'
      implementation 'com.uber.autodispose2:autodispose-lifecycle:2.0.0'
      implementation 'com.uber.autodispose2:autodispose-androidx-lifecycle:2.0.0'

