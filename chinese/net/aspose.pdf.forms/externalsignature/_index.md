---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ExternalSignature 类。使用 X509Certificate2 创建一个分离的 PKCS7 签名。它支持不带可导出私钥的 USB 智能卡令牌
type: docs
weight: 5040
url: /zh/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class

使用 X509Certificate2 创建一个分离的 PKCS#7 签名。它支持不带可导出私钥的 USB 智能卡和令牌。

```csharp
public class ExternalSignature : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | 使用 X509Certificate2 创建一个分离的 PKCS#7 `(detached)` 签名。它支持不带可导出私钥的 USB 智能卡和令牌。 |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | 使用 X509Certificate2 作为 base64 字符串创建一个 PKCS#7 签名。 |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | 使用 X509Certificate2 作为 base64 字符串创建一个 PKCS#7 `(detached)` 签名。 |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | 使用 X509Certificate2 创建一个分离的 PKCS#7 签名。它支持不带可导出私钥的 USB 智能卡和令牌。 |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | 使用 X509Certificate2 创建一个分离的 PKCS#7 `(detached)` 签名。它支持不带可导出私钥的 USB 智能卡和令牌。 |

## Properties

| Name | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | 签署文档的个人或机构的名称。 |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 获取和设置一个选项，表示是否避免估算签名的长度。 |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | 一对整数数组（起始字节偏移量，字节长度），描述用于摘要计算的确切字节范围。 |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 签署者提供的信息，以便接收者能够联系签署者以验证签名，例如电话号码。 |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | 获取/设置自定义外观。 |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | 自定义签署文档哈希的委托。 |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 签署时间。 |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 获取或设置签名数据的默认长度（以字节为单位）。 |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 签署的 CPU 主机名或物理位置。 |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | 获取/设置 OCSP 设置。 |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 签署的原因，例如（我同意，Pip B.）。 |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段具有预定义的外观格式（表示字符串）： ------------------------------------------- 由 {certificate subject} 数字签名 日期：{signature.Date} 原因：{signature.Reason} 位置：{signature.Location} ------------------------------------------- 其中 {X} 是 X 值的占位符。签名还可以包含图像，在这种情况下，列出的字符串将覆盖图像。默认情况下 ShowProperties 为 true。 |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | 获取/设置时间戳设置。 |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | 获取/设置 LTV 验证标志。 |

## Methods

| Name | Description |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 检索有关签名中使用的签名算法的信息。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | 验证文档与此签名的关系，如果文档有效则返回 true，否则返回 false。 |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | 验证文档与此签名的关系，如果文档有效则返回 true，否则返回 false。 |

## Fields

| Name | Description |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | 带有私钥的证书。 |

### See Also

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)