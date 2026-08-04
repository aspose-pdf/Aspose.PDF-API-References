---
title: "PKCS1"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示符合 PKCS#1 标准的签名对象。<br/>            使用 RSA 加密算法和 SHA-1 摘要方法进行签名。"
type: docs
weight: 180
url: /zh/python-net/aspose.pdf.forms/pkcs1/
---

## PKCS1 class

表示符合 PKCS#1 标准的签名对象。<br/>            使用 RSA 加密算法和 SHA-1 摘要方法进行签名。

PKCS1 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PKCS1(image) | 初始化 PKCS1 类的新实例 |
| PKCS1() | 初始化 [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/) 类的新实例。 |
| PKCS1(pfx, password) | 初始化 PKCS1 类的新实例 |
| PKCS1(pfx, password) | 初始化 PKCS1 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| custom_appearance | 获取/设置自定义外观。 |
| authority | 签署文档的个人或机构的名称。 |
| date | 签署时间。 |
| location | 签署的 CPU 主机名或物理位置。 |
| reason | 签署的原因，例如 (I agreeРІР‚В¦)。 |
| contact_info | 签署人提供的信息，以便收件人联系签署人 <br/>            验证签名，例如电话号码。 |
| byte_range | 整数对数组（起始字节偏移量，字节长度） <br/>             用于描述摘要计算的精确字节范围。 |
| timestamp_settings | 获取/设置时间戳设置。 |
| ocsp_settings | 获取/设置 OCSP 设置。 |
| use_ltv | 获取/设置 ltv 验证标志。 |
| show_properties | 强制显示/隐藏签名属性。<br/>如果 ShowProperties 为 true，签名字段具有预定义的外观格式（用于表示的字符串）：<br/>-------------------------------------------<br/>由 {certificate subject} 数字签名<br/>日期: {signature.Date}<br/>原因: {signature.Reason}<br/>位置: {signature.Location}<br/>-------------------------------------------<br/>其中 {X} 是 X 值的占位符。签名也可以包含图像，在这种情况下，上述字符串会放置在图像上。<br/>ShowProperties 默认为 true. |
## 方法
| 名称 | 描述 |
| :- | :- |
| verify() | 验证与此签名相关的文档，如果文档有效则返回 true，<br/>否则返回 false。 |

### 另请参阅

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

