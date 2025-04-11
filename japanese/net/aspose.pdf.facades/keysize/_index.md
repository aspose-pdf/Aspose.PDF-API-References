---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.KeySize 列挙型。PDF ドキュメントを暗号化するために使用できる異なるキーサイズを定義します。
type: docs
weight: 4390
url: /ja/net/aspose.pdf.facades/keysize/
---
## KeySize 列挙型

PDF ドキュメントを暗号化するために使用できる異なるキーサイズを定義します。

```csharp
public enum KeySize
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| x40 | `0` | 40 ビットキー。このキーサイズは RC4 アルゴリズムで使用され、低いセキュリティレベルを提供します。それにもかかわらず、古いバージョンの PDF ドキュメントはこのようなキー（v. 1.3 およびそれ以下）でのみ暗号化できます。 |
| x128 | `1` | 128 ビットキー。RC4 および AES アルゴリズムの両方がこのキーサイズを使用できます。 |
| x256 | `2` | 256 ビットキー。このキーサイズは AES のみで使用でき、最新の Adobe Reader バージョン（v.9 以降）で認識されます。 |

### 参照

* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)