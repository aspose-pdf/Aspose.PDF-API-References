---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: フォントプロパティ。PDFフォント（通常は中国語/日本語/韓国語フォント）は特定のフォント名を持つことがあります。この名前はPDFフォントプロパティ「BaseFont」の値であり、時にはこのプロパティが16進数形式で表されることがあります。この名前を直接読むと、非可読形式で表されることがあります。可読形式を取得するには、このフォントに特有のルールに従ってフォント名をデコードする必要があります。このプロパティはデコードされたフォント名を返すため、非可読の [`FontName`](../fontname/) に出会った場合に使用してください。プロパティ [`FontName`](../fontname/) が可読形式を持つ場合、このプロパティは [`FontName`](../fontname/) と同じになるため、可読形式のフォント名を取得する必要がある場合はこのプロパティを使用できます。
type: docs
weight: 20
url: /ja/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName プロパティ

PDFフォント（通常は中国語/日本語/韓国語フォント）は特定のフォント名を持つことがあります。この名前はPDFフォントプロパティ「BaseFont」の値であり、時にはこのプロパティが16進数形式で表されることがあります。この名前を直接読むと、非可読形式で表されることがあります。可読形式を取得するには、このフォントに特有のルールに従ってフォント名をデコードする必要があります。このプロパティはデコードされたフォント名を返すため、非可読の [`FontName`](../fontname/) に出会った場合に使用してください。プロパティ [`FontName`](../fontname/) が可読形式を持つ場合、このプロパティは [`FontName`](../fontname/) と同じになるため、可読形式のフォント名を取得する必要がある場合はこのプロパティを使用できます。

```csharp
public string DecodedFontName { get; }
```

### 関連項目

* クラス [Font](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)