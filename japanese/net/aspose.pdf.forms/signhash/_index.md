---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントハッシュをカスタム署名するためのデリゲート
type: docs
weight: 5260
url: /ja/net/aspose.pdf.forms/signhash/
---
## SignHash デリゲート

ドキュメントハッシュをカスタム署名するためのデリゲート。

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hash | Byte[] | ドキュメントの入力ハッシュ。 |
| digestHashAlgorithm | DigestHashAlgorithm | ハッシュを作成するために使用されるダイジェストアルゴリズム。値は決して Auto と等しくなりません。 |

### 戻り値

出力署名。

## 備考

デジタル署名が分離されているかどうかにかかわらず、ハッシュ引数は常に署名される最終ハッシュになります。

### 関連項目

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)