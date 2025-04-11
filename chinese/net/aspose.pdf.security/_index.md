---
title: Aspose.Pdf.Security
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security 命名空间包含用于加密和数字签名的类
type: docs
weight: 220
url: /zh/net/aspose.pdf.security/
---
**Aspose.Pdf.Security** 命名空间包含用于加密和数字签名的类。

## 类

| 类 | 描述 |
| --- | --- |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | 表示有关 DSA 签名算法的信息的类。 |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | 表示有关 ECDSA 签名算法的信息的类。 |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | 表示有关带密钥签名算法的信息的类。 |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | 表示有关 RSA 签名算法的信息的类。 |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | 表示有关签名算法的信息的类，包括其类型、加密标准和摘要哈希算法。 |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | 表示在 PDF 签名过程中发生的错误。如果使用 [`SignHash`](../aspose.pdf.forms/signhash/) 签署文档，并且签名的实际长度大于 [`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/) 选项中指定的长度，则会发生此错误。 |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | 表示有关时间戳签名算法的信息的类。 |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | 表示未知签名算法信息的类。 |
| [ValidationOptions](./validationoptions/) | 表示在 PDF 文档中验证数字签名的选项。 |
| [ValidationResult](./validationresult/) | 表示证书验证过程的结果。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | 表示用于保护 PDF 文档的可用加密标准。 |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | 枚举用于数字签名的签名算法类型。 |
| [ValidationMethod](./validationmethod/) | 表示定义用于证书验证的方法的枚举。 |
| [ValidationMode](./validationmode/) | 指定 PDF 签名验证过程的验证模式。 |
| [ValidationStatus](./validationstatus/) | 表示证书验证的验证状态。 |