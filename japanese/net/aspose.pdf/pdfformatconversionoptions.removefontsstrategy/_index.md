---
title: "列挙型 PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy 列挙型。いくつかの文書は PDF/A 形式への変換後にサイズが大きくなります。これらの文書のファイルサイズを削減するには、フォント削除の戦略を定義する必要があります。この列挙体は、フォント使用を最適化するために使用できる戦略を宣言します。この列挙体の各戦略は、フラグ OptimizeFileSize が設定されている場合にのみ意味があります。"
type: docs
weight: 8540
url: /ja/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

いくつかの文書は PDF/A 形式への変換後にサイズが大きくなります。これらの文書のファイルサイズを削減するには、フォント削除の戦略を定義する必要があります。この列挙体は、フォント使用を最適化するために使用できる戦略を宣言します。この列挙体の各戦略は、フラグ [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) が設定されている場合にのみ意味があります。

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | この戦略は、文書内で重複しているすべてのフォントを削除します。文書に重複フォントのグループが含まれる場合、そのグループからは 1 つのフォントだけが文書に埋め込まれます。その他のフォントは文書から削除され、削除されたフォントは既に埋め込まれている同等のフォントで置き換えられます。 |
| RemoveSimilarFontsWithDifferentWidths | `1` | この戦略は RemoveDuplicatedFonts に似ていますが、完全に重複したフォントではなく、フォント間で"Widths"パラメータだけが異なる類似フォントを削除します。このパラメータは、フォントの特定シンボルに対する幅の集合を含みます。"Widths" 集合の各幅の値は、シンボル（グリフ）の実際の幅ではなく、フォントのバイナリデータで定義された実際の幅に代わって PDF ビューアソフトウェアがシンボルを表示する際に使用すべき視覚的幅を示します。より正確には、Acrobat 5.0 以降のビューアは、フォント辞書に格納されたグリフ幅を使用してフォントプログラム自体の幅を上書きし、文書の表示と印刷の一貫性を向上させます。この戦略は RemoveDuplicatedFonts より効果的ですが、場合によっては変換された文書の視覚的表現を損なう可能性があります。この欠陥は、同一シンボルに対して宣言されたフォント幅が異なる場合に発生し、フォント置換時に削除されたフォントが既に埋め込まれたフォントに置き換えられることでシンボルの幅が新しいものに変わります。シンボルの視覚的幅が変わると、正しく表示されず、テキストの重なりやその他の問題といった視覚的欠陥を引き起こす可能性があります。ただし、このような視覚的欠陥は極めて稀であり、この戦略は文書のサイズをより効果的に削減します。 |
| SubsetFonts | `2` | この戦略は文書のサイズを削減する最も効果的な方法です。完全に埋め込まれたフォントセットを取得し、使用されているサブセットだけに縮小します。この戦略は、RemoveDuplicatedFonts または RemoveSimilarFontsWithDifferentWidths と組み合わせて使用することが推奨され、ファイルサイズに対して複数の圧縮効果を得られます。3 つの戦略を同時に使用しても意味がなく、この場合 RemoveSimilarFontsWithDifferentWidths 戦略は使用されません。 |

### 関連項目

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


