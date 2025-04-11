---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode 列挙型。PDF ドキュメントをテキストに変換する際に使用できるさまざまなモードを定義します。TextDevice クラスを参照してください。
type: docs
weight: 10900
url: /ja/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode 列挙型

PDF ドキュメントをテキストに変換する際に使用できるさまざまなモードを定義します。!:TextDevice クラスを参照してください。

```csharp
public enum TextFormattingMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Pure | `0` | PDF コンテンツを少しのフォーマットルーチンで表現します。 |
| Raw | `1` | PDF コンテンツをそのまま表現します。すなわち、フォーマットなしで。 |
| Flatten | `2` | PDF コンテンツをその座標によってテキストフラグメントを配置して表現します。基本的には「Raw」モードに似ています。しかし、「Raw」はドキュメント内のテキストフラグメント（オペレーター）の構造を保持することに重点を置いているのに対し、「Flatten」はテキストが読み取られる順序を保持することに重点を置いています。 |
| MemorySaving | `3` | メモリを節約しながらの抽出。ほぼ「Raw」モードと同じですが、わずかに速く動作し、メモリを少なく使用します。 |

### 参照

* クラス [TextExtractionOptions](../textextractionoptions/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)