---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters クラス。ページのリサイズパラメータを指定するためのクラス。次のパラメータを設定できます。結果ページのサイズ（幅、高さ）をデフォルトの空間単位または初期ページサイズのパーセントで指定します。左、上、下、右のマージンをデフォルトの空間単位または初期ページサイズのパーセントで指定します。一部の値は自動計算のために null のままにすることができます。これらの値は、明示的に指定された値の計算後にページサイズの残りから計算されます。たとえば、ページの幅が 100 で、新しいページの幅が 60 単位と指定された場合、左と右のマージンは自動的に計算されます：(100 - 60) / 2 = 15。このクラスは ResizeContents メソッドで使用されます。
type: docs
weight: 4480
url: /ja/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters クラス

ページのリサイズパラメータを指定するためのクラス。次のパラメータを設定できます：結果ページのサイズ（幅、高さ）をデフォルトの空間単位または初期ページサイズのパーセントで指定します。左、上、下、右のマージンをデフォルトの空間単位または初期ページサイズのパーセントで指定します。一部の値は自動計算のために null のままにすることができます。これらの値は、明示的に指定された値の計算後にページサイズの残りから計算されます。たとえば：ページの幅 = 100 で、新しいページの幅が 60 単位と指定された場合、左と右のマージンは自動的に計算されます：(100 - 60) / 2 = 15。このクラスは ResizeContents メソッドで使用されます。

```csharp
public class ContentsResizeParameters
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | すべての値が「自動」に設定されたリサイズパラメータを作成します。後で必要に応じてマージンとコンテンツサイズを指定できます。 |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | 指定されたマージン値とコンテンツサイズを持つリサイズパラメータを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | 結果ページの下マージンを取得または設定します。 |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | 結果ページのソースページのコンテンツの高さを取得または設定します。 |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | 結果ページのソースページのコンテンツの幅を取得または設定します。 |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | 結果ページの左マージンを取得または設定します。 |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | 結果ページの右マージンを取得または設定します。 |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | 結果ページの上マージンを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | 指定されたコンテンツサイズを持つリサイズパラメータを作成します。 |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | 初期ページサイズのパーセントで指定されたコンテンツサイズを持つリサイズパラメータを作成します。マージンは自動的に計算されます。 |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | 指定されたマージン値を持つリサイズパラメータを作成します。コンテンツサイズは自動的に計算されます。 |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | リサイズパラメータを作成します。マージンは初期ページサイズのパーセントで指定されます。 |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | ページリサイズのためのリサイズパラメータを作成します。 |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | ページリサイズのためのリサイズパラメータを作成します。新しいサイズはパーセントで指定されます。 |

### 参照

* クラス [PdfFileEditor](../pdffileeditor/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)