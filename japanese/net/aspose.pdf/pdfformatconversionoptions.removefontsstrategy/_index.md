---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy 列挙型。一部の文書は PDF/A 形式に変換した後、大きなサイズになります。これらの文書のファイルサイズを削減するには、フォント削除の戦略を定義する必要があります。この列挙型は、フォントの使用を最適化するために使用できる戦略を宣言します。この列挙型の各戦略は、フラグ [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) が設定されている場合にのみ意味があります。
type: docs
weight: 8400
url: /ja/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy 列挙型

一部の文書は PDF/A 形式に変換した後、大きなサイズになります。これらの文書のファイルサイズを削減するには、フォント削除の戦略を定義する必要があります。この列挙型は、フォントの使用を最適化するために使用できる戦略を宣言します。この列挙型の各戦略は、フラグ [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) が設定されている場合にのみ意味があります。

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | この戦略は、文書内に重複があるすべてのフォントを削除します。文書に重複したフォントのグループが含まれている場合、このグループから1つのフォントのみが文書に埋め込まれます。このグループの他のすべてのフォントは文書から削除され、削除されたフォントはすでに埋め込まれているアナログに置き換えられます。 |
| RemoveSimilarFontsWithDifferentWidths | `1` | この戦略は RemoveDuplicatedFonts に似ていますが、完全に重複したフォントではなく、互いに似ていて「幅」パラメータのみが異なるフォントを削除します。このパラメータには、フォントの指定された記号のためのいくつかの幅のセットが含まれています。この「幅」セットの各幅の値は、記号（グリフ）の実際の幅ではなく、この記号の視覚的な幅を意味します。PDF ビューアソフトウェアは、フォントに定義された実際の幅の代わりに、この記号を表示する際に設定する幅です。より正確には、仕様は次のように述べています：Acrobat 5.0 以降のビューアは、フォント辞書に格納されたグリフの幅を使用して、フォントプログラム自体のグリフの幅を上書きし、文書の表示と印刷の一貫性を向上させます。この戦略は RemoveDuplicatedFonts よりも効果的ですが、この戦略を使用することは、理論的には変換された文書の視覚的なプレゼンテーションを損なう可能性があります。この欠陥は、宣言されたフォントの幅が同じ記号に対して異なる可能性があるために発生する可能性があり、この場合、フォントの置き換え後にこの記号の幅が新しいものに変更されます。記号の視覚的な幅が変更されると、正しく表示されず、この違いがテキストの重なりや他の問題などの視覚的欠陥を引き起こす可能性があります。しかし、記述された視覚的欠陥は非常にまれなケースであり、この戦略は文書のサイズをより効果的に削減します。 |
| SubsetFonts | `2` | これは文書のサイズを削減するための最も効果的な戦略です。完全に埋め込まれたフォントセットを取得し、使用されているサブセットのみにトリミングします。この戦略は、RemoveDuplicatedFonts または RemoveSimilarFontsWithDifferentWidths と組み合わせて使用することをお勧めします。ファイルサイズの圧縮効果を得るために、これらの戦略を同時に使用することには意味がありません。この場合、RemoveSimilarFontsWithDifferentWidths 戦略は使用されません。 |

### 参照

* クラス [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)