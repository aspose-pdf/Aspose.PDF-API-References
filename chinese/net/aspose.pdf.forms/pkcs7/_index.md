---
title: Class PKCS7
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7 class. 表示符合互联网RFC 2315 PKCS 7加密消息语法版本1.5的PKCS7对象。文档字节范围的SHA1摘要被封装在PKCS7 SignedData字段中。
type: docs
weight: 5180
url: /zh/net/aspose.pdf.forms/pkcs7/
---
## PKCS7 class

表示符合互联网RFC 2315的PKCS#7对象，PKCS #7：加密消息语法，版本1.5。文档字节范围的`SHA1 digest`被封装在PKCS#7 SignedData字段中。

```csharp
public sealed class PKCS7 : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [PKCS7](pkcs7/#constructor)() | 初始化`PKCS7`类的新实例。 |
| [PKCS7](pkcs7/#constructor_1)(Stream, string) | 初始化`PKCS7`类的新实例。 |
| [PKCS7](pkcs7/#constructor_2)(string, string) | 初始化`PKCS7`类的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | 签署文档的个人或机构的名称。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 获取和设置一个选项，表示是否避免估算签名的长度。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | 描述用于摘要计算的确切字节范围的整数对数组（起始字节偏移量，字节长度）。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 签署人提供的信息，以便接收者能够联系签署人以验证签名，例如电话号码。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | 获取/设置自定义外观。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | 自定义签署文档哈希的委托。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 签署时间。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 获取或设置签名数据的默认长度（以字节为单位）。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 签署的CPU主机名或物理位置。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | 获取/设置ocsp设置。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 签署的原因，例如（我同意，Pip B.）。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 强制显示/隐藏签名属性。如果ShowProperties为true，签名字段具有预定义的外观格式（表示字符串）： ------------------------------------------- 由{certificate subject}数字签名 日期：{signature.Date} 原因：{signature.Reason} 位置：{signature.Location} ------------------------------------------- 其中{X}是X值的占位符。签名也可以有图像，在这种情况下，列出的字符串会覆盖图像。默认情况下ShowProperties为true。 |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | 获取/设置时间戳设置。 |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | 获取/设置ltv验证标志。 |

## Methods

| Name | Description |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 检索有关签名中使用的签名算法的信息。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | 验证文档与此签名的关系，如果文档有效则返回true，否则返回false。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | 验证文档与此签名的关系，如果文档有效则返回true，否则返回false。 |

### See Also

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)