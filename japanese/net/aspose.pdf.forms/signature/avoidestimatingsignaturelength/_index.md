---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Signature プロパティ。署名の長さの推定を回避するかどうかを示すオプションを取得および設定します"
type: docs
weight: 30
url: /ja/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

署名の長さの推定を回避するかどうかを示すオプションを取得および設定します。

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## 備考

署名ドキュメントの前に署名長さの推定を回避します。[`CustomSignHash`](../customsignhash/) および [`ExternalSignature`](../../externalsignature/) を使用した署名に利用されます。[`CustomSignHash`](../customsignhash/) が [`DefaultSignatureLength`](../defaultsignaturelength/) より長い署名を返す場合、[`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) がスローされます。デフォルト値は `false` です。

### 関連項目

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


