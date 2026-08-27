---
title: "PKCS7Detached"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示符合 Internet RFC 2315 中 PKCS#7 规范的 PKCS#7 对象，<br/>            PKCS #7：密码消息语法，版本 1.5。<br/>            文档字节范围的原始已签名消息摘要被作为普通的 PKCS#7 SignedData 字段加入。<br/>            PKCS#7 SignedData 字段中不应封装任何数据。"
type: docs
weight: 200
url: /zh/python-net/aspose.pdf.forms/pkcs7detached/
---

## PKCS7Detached class

表示符合 Internet RFC 2315 中 PKCS#7 规范的 PKCS#7 对象，<br/>            PKCS #7：密码消息语法，版本 1.5。<br/>            文档字节范围的原始已签名消息摘要被作为普通的 PKCS#7 SignedData 字段加入。<br/>            PKCS#7 SignedData 字段中不应封装任何数据。

PKCS7Detached 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PKCS7Detached(image) | 初始化 PKCS7Detached 类的新实例 |
| PKCS7Detached() | 初始化 [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) 类的新实例。 |
| PKCS7Detached(pfx, password) | 初始化 PKCS7Detached 类的新实例 |
| PKCS7Detached(pfx, password) | 初始化 PKCS7Detached 类的新实例 |
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

