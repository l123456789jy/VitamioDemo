# VitamioDemo
Vitamio简介：Vitamio是一个支持所有Android设备的多媒体框架。Vitamio与Android默认的MediaPlayer工作方式相似，但包含更加强大的功能！（注意：Vitamio商业化后个人免费、公司收费）

[vitamio官网](https://www.vitamio.org)

[vitamio SDK地址](https://github.com/yixia/VitamioBundle)

在该项目基础上增加了对7.0以上的支持   https://github.com/xiaohaibin/VitamioDemo
  
  
### 效果图
  

### 使用步骤  
  - 引入vitamio SDK的方式有两种：
  - 直接以module的方式引入
  - 通过Complie的方式引入
 作者是采用的第一种方式，下面是一些需要注意的地方：
  - 清单文件配置：

1）权限设置：
```
<uses-permission android:name="android.permission.WAKE_LOCK" />
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
```  
2）application配置：
```
<!-- 必须初始化 -->
<activity    
android:name="io.vov.vitamio.activity.InitActivity"    
android:configChanges="orientation|screenSize|smallestScreenSize|keyboard|keyboardHidden|navigation"    
android:launchMode="singleTop"    
android:theme="@android:style/Theme.NoTitleBar"    
android:windowSoftInputMode="stateAlwaysHidden" />
```

License
--
    Copyright (C) 2016 xhb_199409@163.com

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
  

