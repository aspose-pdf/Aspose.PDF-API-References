---
title: "Stamp"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "用于各种后代印章的抽象类。"
type: docs
weight: 1440
url: /zh/python-net/aspose.pdf/stamp/
---

## Stamp class

用于各种后代印章的抽象类。

Stamp 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| background | 设置或获取一个布尔值，指示内容是否作为背景进行盖章。<br/>            如果该值为 true，盖章内容放置在底部。<br/>            默认情况下，该值为 false，盖章内容放置在顶部。 |
| opacity | 获取或设置一个值，以指示盖章的不透明度。该值范围为 0.0 到 1.0。<br/>            默认情况下，该值为 1.0。 |
| outline_opacity | 获取或设置一个值，以指示盖章轮廓的不透明度。该值范围为 0.0 到 1.0。<br/>            默认情况下，该值为 1.0。 |
| outline_width | 获取或设置盖章轮廓宽度的值。<br/>            默认情况下，该值为 1.0。 |
| rotate | 设置或获取盖章内容的旋转角度，依据 [Rotation](/pdf/python-net/aspose.pdf/rotation/) 的取值。<br/>            注意：此属性用于设置 90 度的整数倍角度（0、90、180、270 度）。<br/>            若要设置任意角度，请使用 RotateAngle 属性。<br/>            如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| x_indent | 水平盖章坐标，起始于左侧。 |
| y_indent | 垂直盖章坐标，起始于底部。 |
| horizontal_alignment | 获取或设置盖章在页面上的水平对齐方式。 |
| vertical_alignment | 获取或设置盖章在页面上的垂直对齐方式。 |
| left_margin | 获取或设置盖章的左边距。 |
| right_margin | 获取或设置盖章的右边距。 |
| bottom_margin | 获取或设置盖章的底部边距。 |
| top_margin | 获取或设置盖章的顶部边距。 |
| zoom_x | 印章的水平缩放因子。允许水平缩放印章。 |
| width | 页面上印章的期望宽度。 |
| 高度 | 页面上印章的期望高度。 |
| zoom_y | 印章的垂直缩放因子。允许垂直缩放印章。 |
| zoom | 印章的缩放因子。允许缩放印章。<br/>            请注意，属性对 ZoomX 和 ZoomY 允许分别为每个轴设置缩放因子。 <br/>            设置此属性会同时更改 ZoomX 和 ZoomY 属性。 <br/>            如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 的值。 |
| rotate_angle | 获取或设置印章的旋转角度（单位：度）。<br/>            此属性允许设置任意旋转角度。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| put(page) | 在页面上添加印章。 |
| set_stamp_id(value) | 设置印章 ID。 |
| get_stamp_id() | 返回印章 ID。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

