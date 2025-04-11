---
title: Class StartEndPageEventArgs
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Printing.StartEndPageEventArgs クラス。PdfViewer クラスの StartPage および EndPage イベントのデータを提供します。
type: docs
weight: 9710
url: /ja/net/aspose.pdf.printing/startendpageeventargs/
---
## StartEndPageEventArgs クラス

[`StartPage`](../../aspose.pdf.facades/pdfviewer/startpage/) および [`EndPage`](../../aspose.pdf.facades/pdfviewer/endpage/) イベントのデータを [`PdfViewer`](../../aspose.pdf.facades/pdfviewer/) クラスに提供します。

```csharp
public sealed class StartEndPageEventArgs : EventArgs
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [StartEndPageEventArgs](startendpageeventargs/)(int, int, int, int) | `StartEndPageEventArgs` クラスの新しいインスタンスを初期化します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| readonly [CurrentCopy](../../aspose.pdf.printing/startendpageeventargs/currentcopy/) | 現在印刷中のコピーの番号を取得します。 |
| readonly [CurrentPage](../../aspose.pdf.printing/startendpageeventargs/currentpage/) | 現在印刷中のページの番号を取得します。 |
| readonly [TotalCopies](../../aspose.pdf.printing/startendpageeventargs/totalcopies/) | 印刷されるコピーの総数を取得します。 |
| readonly [TotalPages](../../aspose.pdf.printing/startendpageeventargs/totalpages/) | 印刷されるページの総数を取得します。 |

### 参照

* 名前空間 [Aspose.Pdf.Printing](../../aspose.pdf.printing/)
* アセンブリ [Aspose.PDF](../../)