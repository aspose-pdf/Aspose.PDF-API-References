---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Signature プロパティ。署名の長さを推定しないかどうかを設定するオプションを取得および設定します。
type: docs
weight: 30
url: /ja/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength プロパティ

署名の長さを推定しないかどうかを設定するオプションを取得および設定します。

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## 備考

署名文書の前に署名の長さを推定しないようにします。[`CustomSignHash`](../customsignhash/) および [`ExternalSignature`](../../externalsignature/) を介して署名するために使用されます。[`CustomSignHash`](../customsignhash/) が [`DefaultSignatureLength`](../defaultsignaturelength/) よりも長い署名を返すと、[`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) がスローされます。デフォルト値は `false` です。

### 参照

* クラス [Signature](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)