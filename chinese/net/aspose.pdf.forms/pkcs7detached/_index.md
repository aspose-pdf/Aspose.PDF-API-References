---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7Detached 类。表示符合互联网 RFC 2315 PKCS 7 加密消息语法版本 1.5 的 PKCS7 对象。原始签名消息摘要在文档字节范围内作为正常的 PKCS7 SignedData 字段包含。PKCS7 SignedData 字段中不应封装任何数据。
type: docs
weight: 5190
url: /zh/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached class

表示符合 PKCS#7 规范的 PKCS#7 对象，符合互联网 RFC 2315，PKCS #7：加密消息语法，版本 1.5。原始签名消息摘要在文档的字节范围内作为正常的 PKCS#7 SignedData 字段包含。PKCS#7 SignedData 字段中不应封装任何数据。

```csharp
public sealed class PKCS7Detached : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | 初始化 `PKCS7Detached` 类的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | 签署文档的人员或机构的名称。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 获取和设置一个选项，表示是否避免估算签名的长度。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | 一对整数数组（起始字节偏移量，字节长度），描述摘要计算的确切字节范围。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 签署者提供的信息，以便接收者能够联系签署者以验证签名，例如电话号码。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | 获取/设置自定义外观。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | 自定义签署文档哈希的委托。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 签署时间。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 获取或设置签名数据的默认长度（以字节为单位）。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 签署的 CPU 主机名或物理位置。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | 获取/设置 OCSP 设置。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 签署的原因，例如（我同意，Pip B.）。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段具有预定义的外观格式（表示的字符串）： ------------------------------------------- 由 {certificate subject} 数字签名 日期：{signature.Date} 原因：{signature.Reason} 位置：{signature.Location} ------------------------------------------- 其中 {X} 是 X 值的占位符。签名还可以具有图像，在这种情况下，列出的字符串将放置在图像上。默认情况下 ShowProperties 为 true。 |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | 获取/设置时间戳设置。 |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | 获取/设置 LTV 验证标志。 |

## Methods

| Name | Description |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 检索有关签名中使用的签名算法的信息。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | 验证文档与此签名的关系，如果文档有效则返回 true，否则返回 false。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | 验证文档与此签名的关系，如果文档有效则返回 true，否则返回 false。 |

### See Also

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)