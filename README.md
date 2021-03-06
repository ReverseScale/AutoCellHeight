# AutoCellHeightDemo

![](https://img.shields.io/badge/platform-iOS-red.svg) 
![](https://img.shields.io/badge/language-Objective--C-orange.svg) 
![](https://img.shields.io/badge/download-8.2MB-brightgreen.svg)
![](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg) 

[EN](#Requirements) | [中文](#中文说明)

OC + Swift dual version dynamic list UITableView data loading and cell dynamics highly adaptive.

Centralized management of TableView Data for temporary fixed class table structure, the page jump by the Runtime class method (and storyboard dynamic jump), suitable for changes in the sort of list data.

Swift, Objective-C dual-version synchronization update:
* Common UITableView practical specifications
* Reuse / disable reuse example
Off-screen rendering problem optimization program
* Model setter assignment specification

|1.List page |2.JSON dynamic form page |3.Dynamic jump detail page |4.Package static form example |
| ------------- | ------------- | ------------- | ------------- |
| ![](http://ghexoblogimages.oss-cn-beijing.aliyuncs.com/18-11-22/36220011.jpg) | ![](http://ghexoblogimages.oss-cn-beijing.aliyuncs.com/18-11-22/3450458.jpg) | ![](http://ghexoblogimages.oss-cn-beijing.aliyuncs.com/18-11-22/61700298.jpg) | ![](http://ghexoblogimages.oss-cn-beijing.aliyuncs.com/18-11-22/97403040.jpg) |
| Building a basic framework via storyboard | JSON dynamic list page | dynamic data jump detail page | package static list page |



## 🚀 Advantage
* 1. Less documents, code concise
* 2. Easy to implement and flexible
* 3. Have a high custom


## 🤖 Requirements
* iOS 7+
* Xcode 8+

93520148.jpg
## 🛠 Usage 
### OC Data
```
self.arrayList = @[@[@"Logo", @"Workplace"], @[@"Watermark"]];

self.titleDic = @{
                   @"Logo":@"GAVTH is a design & development studio.",
                   @"Workplace":@"Definition of GAVTH in old language is deep pit. The logotype, in fact, composed exclusively of contour and curved lines that inspired from topographic lines. The choice of the color is not random; blue is a represent the figure of depth and clean, gray is an earth surface color and it gives neutrality and quiet.",
                   @"Watermark":@"Definition of GAVTH in old language is deep pit. The logotype, in fact, composed exclusively of contour and curved lines that inspired from topographic lines."
                   };
self.picDic = @{
                 @"Logo":@"Icon.png",
                 @"Workplace":@"PicImg.png",
                 @"Watermark":@"PicText.png"
                 };
```
### Swift data
```
arrayList = [
    ["Logo","Workplace"],
    ["Watermark"]
]
titleDic = [
    "Logo":"GAVTH is a design & development studio.",
    "Workplace":"Definition of GAVTH in old language is deep pit. The logotype, in fact, composed exclusively of contour and curved lines that inspired from topographic lines. The choice of the color is not random; blue is a represent the figure of depth and clean, gray is an earth surface color and it gives neutrality and quiet.",
    "Watermark":"Definition of GAVTH in old language is deep pit. The logotype, in fact, composed exclusively of contour and curved lines that inspired from topographic lines."
    ]
picDic = [
    "Logo":"Icon.png",
    "Workplace":"PicImg.png",
    "Watermark":"PicText.png"
    ]
```

## ⚖ License

```
MIT License

Copyright (c) 2017 ReverseScale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 😬 Contributions

* WeChat : WhatsXie
* Email : ReverseScale@iCloud.com
* Blog : https://reversescale.github.io

---
# 中文说明

OC + Swift 双版本实现动态列表 UITableView 数据加载及 cell 动态高度自适应。

集中管理 TableView Data ，适用于暂时固定的类表结构，页面跳转由 Runtime 的类方法实现（和 storyboard 动态跳转），适合对列表数据排序变动的情况。

Swift、Objective-C 双版本同步更新：
* 常用 UITableView 的实用规范
* 重用/禁用重用机制示例
* 离屏渲染问题优化方案
* Model setter 赋值规范

|1.列表页 |2.JSON 动态表格页 |3.动态跳转详情页 |4.封装静态表格示例 |
| ------------- | ------------- | ------------- | ------------- |
| ![](http://ghexoblogimages.oss-cn-beijing.aliyuncs.com/18-11-22/36220011.jpg) | ![](http://ghexoblogimages.oss-cn-beijing.aliyuncs.com/18-11-22/3450458.jpg) | ![](http://ghexoblogimages.oss-cn-beijing.aliyuncs.com/18-11-22/61700298.jpg) | ![](http://ghexoblogimages.oss-cn-beijing.aliyuncs.com/18-11-22/97403040.jpg) |
| 通过 storyboard 搭建基本框架 | JSON 动态列表页 | 动态数据跳转详情页 | 封装静态列表页 |


## 🚀 框架的优势
* 1.文件少，代码简洁
* 2.实现简单，灵活性强
* 3.具备较高自定义性


## 🤖 要求
* iOS 7+
* Xcode 8+


## 🛠 使用方法
### OC 数据
```
self.arrayList = @[@[@"Logo", @"Workplace"], @[@"Watermark"]];

self.titleDic = @{
                   @"Logo":@"GAVTH is a design & development studio.",
                   @"Workplace":@"Definition of GAVTH in old language is deep pit. The logotype, in fact, composed exclusively of contour and curved lines that inspired from topographic lines. The choice of the color is not random; blue is a represent the figure of depth and clean, gray is an earth surface color and it gives neutrality and quiet.",
                   @"Watermark":@"Definition of GAVTH in old language is deep pit. The logotype, in fact, composed exclusively of contour and curved lines that inspired from topographic lines."
                   };
self.picDic = @{
                 @"Logo":@"Icon.png",
                 @"Workplace":@"PicImg.png",
                 @"Watermark":@"PicText.png"
                 };
```
### Swift 数据
```
arrayList = [
    ["Logo","Workplace"],
    ["Watermark"]
]
titleDic = [
    "Logo":"GAVTH is a design & development studio.",
    "Workplace":"Definition of GAVTH in old language is deep pit. The logotype, in fact, composed exclusively of contour and curved lines that inspired from topographic lines. The choice of the color is not random; blue is a represent the figure of depth and clean, gray is an earth surface color and it gives neutrality and quiet.",
    "Watermark":"Definition of GAVTH in old language is deep pit. The logotype, in fact, composed exclusively of contour and curved lines that inspired from topographic lines."
    ]
picDic = [
    "Logo":"Icon.png",
    "Workplace":"PicImg.png",
    "Watermark":"PicText.png"
    ]
```


## ⚖ 协议

```
MIT License

Copyright (c) 2017 ReverseScale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 😬  联系

* 微信 : WhatsXie
* 邮件 : ReverseScale@iCloud.com
* 博客 : https://reversescale.github.io
