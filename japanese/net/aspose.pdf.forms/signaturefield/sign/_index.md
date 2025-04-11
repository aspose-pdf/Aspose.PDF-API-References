---
title: SignatureField.Sign
second_title: Aspose.PDF for .NET API Reference
description: SignatureField メソッド。この署名フィールドを使用して文書に署名します
type: docs
weight: 50
url: /ja/net/aspose.pdf.forms/signaturefield/sign/
---
## Sign(Signature, Stream, string) {#sign_1}

この署名フィールドを使用して文書に署名します。

```csharp
public void Sign(Signature signature, Stream pfx, string pass)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signature | Signature | Signature オブジェクト、[`PKCS1`](../../pkcs1/)、[`PKCS7`](../../pkcs7/)、[`PKCS7Detached`](../../pkcs7detached/)を参照してください。 |
| pfx | Stream | 証明書を含むストリーム。 |
| pass | String | *pfx* のプライベートにアクセスするためのパスワード。 |

### 参照

* クラス [Signature](../../signature/)
* クラス [SignatureField](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## Sign(Signature) {#sign}

この署名フィールドを使用して文書に署名します。

```csharp
public void Sign(Signature signature)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signature | Signature | Signature オブジェクト、[`PKCS1`](../../pkcs1/)、[`PKCS7`](../../pkcs7/) および [`PKCS7Detached`](../../pkcs7detached/)を参照してください。 |

### 参照

* クラス [Signature](../../signature/)
* クラス [SignatureField](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)