---
title: "类 PKCS1"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Forms.PKCS1 类。表示符合 PKCS1 标准的签名对象。签名使用 RSA 加密算法和 SHA1 摘要方法。"
type: docs
weight: 5290
url: /zh/net/aspose.pdf.forms/pkcs1/
---
## PKCS1 class

表示符合 PKCS#1 标准的签名对象。签名使用 RSA 加密算法和 SHA-1 摘要方法。

```csharp
public sealed class PKCS1 : Signature
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | 初始化 `PKCS1` 类的新实例。 |
| [PKCS1](pkcs1/#constructor_1)(Stream) | 初始化 `PKCS1` 类的新实例。 |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | 初始化 `PKCS1` 类的新实例。 |
| [PKCS1](pkcs1/#constructor_3)(string, string) | 初始化 `PKCS1` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | 签署文档的个人或机构的名称。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 获取或设置一个选项，表示是否避免估计签名的长度。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | 一个整数对数组（起始字节偏移量，字节长度），用于描述摘要计算的精确字节范围。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 签名者提供的信息，以便收件人联系签名者验证签名，例如电话号码。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | 获取/设置自定义外观。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | 用于自定义签署文档哈希的委托。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 签署时间。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 获取或设置签名数据的默认字节长度。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 签署的 CPU 主机名或物理位置。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | 获取/设置 OCSP 设置。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 签署原因，例如（I agree, Pip B.）。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段将具有预定义的外观格式（字符串表示）： ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- 其中 {X} 为 X 值的占位符。签名也可以包含图像，在此情况下上述字符串会放置在图像上。ShowProperties 默认为 true。 |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | 获取/设置时间戳设置。 |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | 获取/设置 LTV 验证标志。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 检索关于签名中使用的签名算法的信息。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | 验证文档相对于此签名的有效性，如果文档有效则返回 true，否则返回 false。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | 验证文档相对于此签名的有效性，如果文档有效则返回 true，否则返回 false。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)(X509Certificate2, ValidationOptions, out ValidationResult) | 验证文档相对于此签名的有效性，如果文档有效则返回 true，否则返回 false。验证使用外部公钥证书进行。 |

### 另请参见

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


