---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Signature 类。一个抽象类，表示 PDF 文档中的签名对象。签名是具有签名对象值的字段，最后包含用于验证文档有效性的数据。
type: docs
weight: 5270
url: /zh/net/aspose.pdf.forms/signature/
---
## 签名类

一个抽象类，表示 PDF 文档中的签名对象。签名是具有签名对象值的字段，最后包含用于验证文档有效性的数据。

```csharp
public abstract class Signature
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Signature](signature/#constructor)() | 初始化 `Signature` 类的新实例。 |
| [Signature](signature/#constructor_1)(Stream, string) | 初始化 `Signature` 类的新实例。 |
| [Signature](signature/#constructor_2)(string, string) | 初始化 `Signature` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | 签署文档的人员或机构的名称。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 获取和设置一个选项，表示是否避免估算签名的长度。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | 一组整数对（起始字节偏移量，字节长度），描述用于摘要计算的确切字节范围。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 签署者提供的信息，以便接收者能够联系签署者以验证签名，例如电话号码。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | 获取/设置自定义外观。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | 自定义签署文档哈希的委托。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 签署时间。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 获取或设置签名数据的默认字节长度。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 签署的 CPU 主机名或物理位置。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | 获取/设置 OCSP 设置。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 签署的原因，例如（我同意，Pip B.）。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段具有预定义的外观格式（表示字符串）： ------------------------------------------- 数字签名由 {certificate subject} 日期： {signature.Date} 原因： {signature.Reason} 位置： {signature.Location} ------------------------------------------- 其中 {X} 是 X 值的占位符。签名还可以有图像，在这种情况下，列出的字符串会覆盖图像。默认情况下 ShowProperties 为 true。 |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | 获取/设置时间戳设置。 |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | 获取/设置 LTV 验证标志。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 检索有关签名中使用的签名算法的信息。 |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | 验证文档与此签名的关系，如果文档有效则返回 true，否则返回 false。 |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | 验证文档与此签名的关系，如果文档有效则返回 true，否则返回 false。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../)