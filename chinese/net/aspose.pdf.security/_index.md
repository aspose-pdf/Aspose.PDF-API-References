---
title: "Aspose.Pdf.Security"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Security 命名空间包含用于加密和数字签名的类。"
type: docs
weight: 210
url: /zh/net/aspose.pdf.security/
---
**Aspose.Pdf.Security** 命名空间包含用于加密和数字签名的类。

## 类

| 类 | 描述 |
| --- | --- |
| [CertificateEncryptionOptions](./certificateencryptionoptions/) | 表示用于使用基于证书的加密方法对 PDF 文档进行加密的选项类。用于打开加密的 PDF 文档。 |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | 表示有关 DSA 签名算法信息的类。 |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | 表示有关 ECDSA 签名算法信息的类。 |
| [EncryptionParameters](./encryptionparameters/) | 表示加密参数类。 |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | 表示有关密钥签名算法信息的类。 |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | 表示有关 RSA 签名算法信息的类。 |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | 表示有关签名算法信息的类，包括其类型、加密标准和摘要哈希算法。 |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | 表示在 PDF 签名期间发生的错误。如果使用 [`SignHash`](../aspose.pdf.forms/signhash/) 对文档进行签名，并且签名的实际长度大于 [`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/) 选项中指定的长度，则会发生此错误。 |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | 表示有关时间戳签名算法信息的类。 |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | 表示未知签名算法信息的类。 |
| [ValidationOptions](./validationoptions/) | 表示用于验证 PDF 文档中数字签名的选项。 |
| [ValidationResult](./validationresult/) | 表示证书验证过程的结果。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [ICustomSecurityHandler](./icustomsecurityhandler/) | 自定义安全处理程序接口。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | 表示用于保护 PDF 文档的可用加密标准。 |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | 枚举用于数字签名的签名算法类型。 |
| [ValidationMethod](./validationmethod/) | 表示定义用于证书验证的方法的枚举。 |
| [ValidationMode](./validationmode/) | 指定 PDF 签名验证过程的验证模式。 |
| [ValidationStatus](./validationstatus/) | 表示证书验证的验证状态。 |


