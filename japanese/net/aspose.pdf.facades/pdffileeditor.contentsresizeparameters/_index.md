---
title: "クラス PdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters クラス。ページサイズ変更パラメータを指定するクラスです。次のパラメータを設定できます。結果ページのサイズ（幅、高さ）をデフォルトの空間単位または元のページサイズのパーセンテージで指定。左、上、下、右の余白をデフォルトの空間単位または元のページサイズのパーセンテージで指定。一部の値は自動計算のために null のままにできます。これらの値は、明示的に指定された値を除いた残りのページサイズから計算されます。例として、ページ幅が 100 で新しいページ幅が 60 単位と指定された場合、左と右の余白は自動的に (100 - 60) / 2 = 15 と計算されます。このクラスは ResizeContents メソッドで使用されます。"
type: docs
weight: 4600
url: /ja/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

ページサイズ変更パラメータを指定するクラスです。次のパラメータを設定できます：結果ページのサイズ（幅、高さ）をデフォルトの空間単位または元のページサイズのパーセンテージで指定；左、上、下、右の余白をデフォルトの空間単位または元のページサイズのパーセンテージで指定；自動計算のために null のままにできる値があります。これらの値は、明示的に指定された値を除いた残りのページサイズから計算されます。例：ページ幅が 100 で新しいページ幅が 60 単位の場合、左と右の余白は自動的に (100 - 60) / 2 = 15 と計算されます。このクラスは ResizeContents メソッドで使用されます。

```csharp
public class ContentsResizeParameters
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | すべての値が "auto" に設定されたサイズ変更パラメータを作成します。後で必要に応じて余白やコンテンツサイズを指定できます。 |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | 指定された余白値とコンテンツサイズでサイズ変更パラメータを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | 結果ページの下余白を取得または設定します。 |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | 結果ページ上のソースページのコンテンツの高さを取得または設定します。 |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | 結果ページ上のソースページのコンテンツの幅を取得または設定します。 |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | 結果ページの左余白を取得または設定します。 |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | 結果ページの右余白を取得または設定します。 |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | 結果ページの上余白を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | 指定されたコンテンツサイズでサイズ変更パラメータを作成します。 |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | 元のページサイズのパーセンテージで指定されたコンテンツサイズでサイズ変更パラメータを作成します。余白は自動的に計算されます。 |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | 指定された余白値でサイズ変更パラメータを作成します。コンテンツサイズは自動的に計算されます。 |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | サイズ変更パラメータを作成します。余白は元のページサイズのパーセンテージで指定されます。 |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | ページサイズ変更のためのサイズ変更パラメータを作成します。 |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | ページサイズ変更のためのサイズ変更パラメータを作成します。新しいサイズはパーセンテージで指定されます。 |

### 関連項目

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


