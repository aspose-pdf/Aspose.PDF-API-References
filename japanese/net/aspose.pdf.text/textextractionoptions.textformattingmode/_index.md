---
title: "列挙体 TextExtractionOptions.TextFormattingMode"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode 列挙体。PDF ドキュメントをテキストに変換する際に使用できるさまざまなモードを定義します。TextDevice クラスを参照してください"
type: docs
weight: 11080
url: /ja/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

PDF ドキュメントをテキストに変換する際に使用できるさまざまなモードを定義します。!:TextDevice クラスを参照してください。

```csharp
public enum TextFormattingMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Pure | `0` | PDF コンテンツを少しだけフォーマットした形で表現します。 |
| Raw | `1` | PDF コンテンツをそのまま、つまりフォーマットせずに表現します。 |
| Flatten | `2` | テキストフラグメントを座標で位置指定して PDF コンテンツを表現します。基本的には "Raw" モードと似ていますが、"Raw" がドキュメント内のテキストフラグメント（オペレーター）の構造保持に重点を置くのに対し、"Flatten" はテキストを読み取られる順序で保持することに重点を置きます。 |
| MemorySaving | `3` | メモリ節約型の抽出です。ほぼ 'Raw' モードと同じですが、若干高速でメモリ使用量が少なくなります。 |

### 関連項目

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


