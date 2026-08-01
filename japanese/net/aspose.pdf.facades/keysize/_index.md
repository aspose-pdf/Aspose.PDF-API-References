---
title: "列挙型 KeySize"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.KeySize 列挙型。PDF ドキュメントの暗号化に使用できるさまざまな鍵サイズを定義します。"
type: docs
weight: 4510
url: /ja/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

pdf documents を暗号化するために使用できるさまざまな鍵サイズを定義します。

```csharp
public enum KeySize
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| x40 | `0` | 40 ビット鍵。この鍵サイズは RC4 アルゴリズムで使用され、低レベルのセキュリティを提供します。ただし、古いバージョンの PDF ドキュメントはこの鍵（バージョン 1.3 以下）でのみ暗号化できます。 |
| x128 | `1` | 128 ビット鍵。RC4 と AES の両アルゴリズムでこの鍵サイズが使用できます。 |
| x256 | `2` | 256 ビット鍵。この鍵サイズは AES のみで使用でき、最新の Adobe Reader バージョン（v.9 以降）で認識されます。 |

### 関連項目

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


