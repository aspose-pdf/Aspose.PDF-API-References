---
title: "类 PKCS7Detached"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Forms.PKCS7Detached 类。表示符合 Internet RFC 2315 PKCS 7 加密消息语法第 1.5 版规范的 PKCS7 对象。原始签名的消息摘要（覆盖文档字节范围）被合并为普通的 PKCS7 SignedData 字段。PKCS7 SignedData 字段中不应封装任何数据。"
type: docs
weight: 5310
url: /zh/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached class

表示符合 PKCS#7 规范（Internet RFC 2315，PKCS #7：密码消息语法，版本 1.5）的 PKCS#7 对象。文档字节范围的原始已签名消息摘要被作为普通的 PKCS#7 SignedData 字段包含。PKCS#7 SignedData 字段中不封装任何数据。

```csharp
public sealed class PKCS7Detached : Signature
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | 初始化 `PKCS7Detached` 类的新实例。 |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | 初始化 `PKCS7Detached` 类的新实例。 |

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


