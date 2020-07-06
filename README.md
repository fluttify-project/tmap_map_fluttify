![Logo](https://github.com/fluttify-project/fluttify-core-example/blob/develop/other/Logo-Landscape.png?raw=true)

# 腾讯地图 地图组件 Flutter插件

[![pub package](https://img.shields.io/pub/v/tmap_map_fluttify.svg)](https://pub.Flutter-io.cn/packages/tmap_map_fluttify)

**专业版为付费插件, 如有需要请联系qq 382146139**

**专业版为付费插件, 如有需要请联系qq 382146139**

**专业版为付费插件, 如有需要请联系qq 382146139**

## 依赖
```yaml
dependencies:
  flutter:
    sdk: flutter
  tmap_map_fluttify: ^x.x.x
```

## 配置
### Android
1. 在AndroidManifest.xml的application标签下配置app key:
```xml
<application>
    <meta-data
            android:name="TencentMapSDK"
            android:value="FQxxxxxxxxxxxxxxxxxxxxxxx2R"/>
</application>
```

### iOS
1. 使用地图需要使能UiKitView, 在Info.plist中添加:
```xml
<key>io.flutter.embedded_views_preview</key>
<string>YES</string>
```
2. 如果是swift项目(flutter创建项目时默认), 需要注释掉Podfile中的`use_frameworks!`, 如下:
```ruby
target 'Runner' do
  # use_frameworks!
  use_modular_headers!

  # Flutter Pod
...
```

## 使用
参考[wiki](https://github.com/fluttify-project/tmap_map_fluttify/wiki/_new).

## 导入
```dart
import 'package:tmap_map_fluttify/tmap_map_fluttify.dart';
```

## 社区
| QQ2群 | QQ1群(已满) |
| :----------: | :----------: |
| 加入QQ群讨论 <br/> <img src="https://github.com/fluttify-project/fluttify-project/blob/master/resources/qrcode_1593774649831.jpg?raw=true" height="300"> |加入QQ群讨论 <br/> <img src="https://github.com/fluttify-project/fluttify-project/blob/master/resources/1593774713224_temp_qrcode_share_9993.png?raw=true" height="300"> | 

## 社区版与专业版
|       | 社区版 | 专业版 |
|:-----:|:-----:|:-----:|
|  显示地图  |  ✅ |  ✅   |
|  显示室内地图  |  ✅ |  ✅   |
|  选择显示图层  |  ✅ |  ✅   |
|  显示路况信息  |  ✅ |  ✅   |
|  显示缩放控件  |  ✅ |  ✅   |
|  显示缩放控件  |  ✅ |  ✅   |
|  显示指南针  |  ✅ |  ✅   |
|  显示定位按钮  |  ✅ |  ✅   |
|  显示比例尺控件  |  ✅ |  ✅   |
|  缩放手势使能  |  ✅ |  ✅   |
|  滑动手势使能  |  ✅ |  ✅   |
|  旋转手势使能  |  ✅ |  ✅   |
|  倾斜手势使能  |  ✅ |  ✅   |
|  添加marker  |  ✅ |  ✅   |
|  显示我的位置  |  ✅ |  ✅   |
|  设置地图中心点  |  ✅ |  ✅   |
|  把marker列表从地图上移除  |  ✅ |  ✅   |
|  清除地图上所有覆盖物  |  ✅ |  ✅   |
|  添加折线  |  ✅ |  ✅   |
|  添加多边形  |  ✅ |  ✅   |
|  添加圆  |  ✅ |  ✅   |
|  设置marker点击监听事件  |  ✅ |  ✅   |

## LICENSE
> Copyright (C) 2020 yohom
> 
> This program is free software: you can redistribute it and/or modify
> it under the terms of the GNU General Public License as published by
> the Free Software Foundation, either version 3 of the License, or
> (at your option) any later version.
> 
> This program is distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
> GNU General Public License for more details.
> 
> You should have received a copy of the GNU General Public License
> along with this program.  If not, see <https://www.gnu.org/licenses/>.
