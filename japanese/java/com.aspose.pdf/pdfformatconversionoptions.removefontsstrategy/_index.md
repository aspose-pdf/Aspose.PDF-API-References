---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF/A 形式への変換後、一部の文書はサイズが大きくなります。これらの文書のファイルサイズを削減するには、フォント削除の戦略を定義する必要があります。これは列挙型です。"
type: docs
weight: 3760
url: /ja/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

一部の文書は PDF/A 形式に変換した後、サイズが大きくなります。これらの文書のファイルサイズを削減するには、フォント削除の戦略を定義する必要があります。この列挙型は、フォント使用を最適化するために使用できる戦略を宣言します。この列挙型の各戦略は、フラグ {@code OptimizeFileSize} が設定されている場合にのみ意味があります。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | この戦略は、文書内で重複しているすべてのフォントを削除します。文書に重複フォントのグループが含まれている場合、そのグループからは 1 つのフォントだけが文書に埋め込まれます。その他のフォントは文書から削除され、削除されたフォントはすでに埋め込まれている同等のフォントで置き換えられます。 |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | この戦略は {@code RemoveDuplicatedFonts} に似ていますが、完全に重複したフォントだけでなく、パラメータ「Widths」のみが異なる類似フォントを削除します。このパラメータは、フォントの特定シンボルに対するいくつかの幅の集合を含みます。「Widths」集合の各幅の値は、シンボル（グリフ）の実際の幅ではなく、フォントのバイナリデータで既に定義されている実際の幅です。「Widths」集合の幅の値は、そのシンボルの視覚的幅を意味します。つまり、PDF ビューアソフトウェアがシンボルを表示する際に、フォントで定義された実際の幅ではなく、この視覚的幅を使用しなければなりません。より正確には、仕様では次のように述べられています：Acrobat 5.0 以降のビューアは、フォント辞書に格納されたグリフ幅を使用して、フォントプログラム自体のグリフ幅を上書きし、文書の表示および印刷の一貫性を向上させます。この戦略は {@code RemoveDuplicatedFonts} より効果的ですが、場合によっては理論的に変換された文書の視覚的表現を損なう可能性があります。この欠陥は、同じシンボルに対して宣言されたフォント幅が異なる場合に発生し、その場合、フォント置換後にシンボルの幅が新しいものに変更されます。削除されたフォントがすでに埋め込まれているフォントに置き換えられると、シンボルの視覚的幅が変わり、正しく表示されず、テキストの重なりやその他の問題などの視覚的欠陥を引き起こす可能性があります。ただし、記述された視覚的欠陥は非常に稀なケースであり、この戦略は文書のサイズをより効果的に削減します。 |
| [SubsetFonts](#SubsetFonts) | これは文書のサイズを削減する最も効果的な戦略です。完全に埋め込まれたフォントセットを取得し、使用されているサブセットだけに絞り込みます。この戦略は {@code RemoveDuplicatedFonts} または {@code RemoveSimilarFontsWithDifferentWidths} と組み合わせて使用することが推奨され、ファイルサイズに対して複数の圧縮効果を得られます。3 つの戦略を同時に使用しても意味がなく、この場合は {@code RemoveSimilarFontsWithDifferentWidths} 戦略は使用されません。 |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

この戦略は、文書内で重複しているすべてのフォントを削除します。文書に重複フォントのグループが含まれている場合、そのグループからは 1 つのフォントだけが文書に埋め込まれます。その他のフォントは文書から削除され、削除されたフォントはすでに埋め込まれている同等のフォントで置き換えられます。

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

この戦略は {@code RemoveDuplicatedFonts} に似ていますが、完全に重複したフォントだけでなく、パラメータ「Widths」のみが異なる類似フォントを削除します。このパラメータは、フォントの特定シンボルに対するいくつかの幅の集合を含みます。「Widths」集合の各幅の値は、シンボル（グリフ）の実際の幅ではなく、フォントのバイナリデータで既に定義されている実際の幅です。「Widths」集合の幅の値は、そのシンボルの視覚的幅を意味します。つまり、PDF ビューアソフトウェアがシンボルを表示する際に、フォントで定義された実際の幅ではなく、この視覚的幅を使用しなければなりません。より正確には、仕様では次のように述べられています：Acrobat 5.0 以降のビューアは、フォント辞書に格納されたグリフ幅を使用して、フォントプログラム自体のグリフ幅を上書きし、文書の表示および印刷の一貫性を向上させます。この戦略は {@code RemoveDuplicatedFonts} より効果的ですが、場合によっては理論的に変換された文書の視覚的表現を損なう可能性があります。この欠陥は、同じシンボルに対して宣言されたフォント幅が異なる場合に発生し、その場合、フォント置換後にシンボルの幅が新しいものに変更されます。削除されたフォントがすでに埋め込まれているフォントに置き換えられると、シンボルの視覚的幅が変わり、正しく表示されず、テキストの重なりやその他の問題などの視覚的欠陥を引き起こす可能性があります。ただし、記述された視覚的欠陥は非常に稀なケースであり、この戦略は文書のサイズをより効果的に削減します。

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

これは文書のサイズを削減する最も効果的な戦略です。完全に埋め込まれたフォントセットを取得し、使用されているサブセットだけに絞り込みます。この戦略は {@code RemoveDuplicatedFonts} または {@code RemoveSimilarFontsWithDifferentWidths} と組み合わせて使用することが推奨され、ファイルサイズに対して複数の圧縮効果を得られます。3 つの戦略を同時に使用しても意味がなく、この場合は {@code RemoveSimilarFontsWithDifferentWidths} 戦略は使用されません。
