---
title: "デリゲート SignHash"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ドキュメントハッシュにカスタム署名するためのデリゲート"
type: docs
weight: 5380
url: /ja/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

ドキュメントハッシュに対してカスタム署名を行うデリゲートです。

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ハッシュ | Byte[] | ドキュメントの入力ハッシュ。 |
| digestHashAlgorithm | DigestHashAlgorithm | ハッシュを作成するために使用されるダイジェストアルゴリズムです。値は Auto と等しくなることはありません。 |

### 戻り値

出力署名。

## 備考

デジタル署名が分離形式かどうかにかかわらず、hash 引数は常に署名対象となる最終ハッシュであることに注意してください。

### 関連項目

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


