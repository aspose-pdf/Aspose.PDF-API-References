---
title: SignatureField.Sign
second_title: Aspose.PDF for .NET API Reference
description: SignatureField 方法。使用此签名字段对文档进行签名
type: docs
weight: 50
url: /zh/net/aspose.pdf.forms/signaturefield/sign/
---
## Sign(Signature, Stream, string) {#sign_1}

使用此签名字段对文档进行签名。

```csharp
public void Sign(Signature signature, Stream pfx, string pass)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | Signature | 签名对象，参见 [`PKCS1`](../../pkcs1/)，[`PKCS7`](../../pkcs7/)，[`PKCS7Detached`](../../pkcs7detached/)。 |
| pfx | Stream | 包含证书的流。 |
| pass | String | 访问 *pfx* 中私钥的密码。 |

### 另见

* 类 [Signature](../../signature/)
* 类 [SignatureField](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## Sign(Signature) {#sign}

使用此签名字段对文档进行签名。

```csharp
public void Sign(Signature signature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | Signature | 签名对象，参见 [`PKCS1`](../../pkcs1/)，[`PKCS7`](../../pkcs7/) 和 [`PKCS7Detached`](../../pkcs7detached/)。 |

### 另见

* 类 [Signature](../../signature/)
* 类 [SignatureField](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)