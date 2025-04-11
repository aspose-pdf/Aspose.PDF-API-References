---
title: Delegate PdfQueryPageSettingsEventHandler
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer の PdfQueryPageSettings イベントを処理するメソッドを表します
type: docs
weight: 4620
url: /ja/net/aspose.pdf.facades/pdfquerypagesettingseventhandler/
---
## PdfQueryPageSettingsEventHandler デリゲート

[`PdfQueryPageSettings`](../pdfviewer/pdfquerypagesettings/) イベントを処理するメソッドを表します [`PdfViewer`](../pdfviewer/) の。

```csharp
public delegate void PdfQueryPageSettingsEventHandler(object sender, 
    PdfQueryPageSettingsEventArgs queryPageSettingsEventArgs, PdfPrintPageInfo currentPageInfo);
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sender | Object | イベントの発生源。 |
| queryPageSettingsEventArgs | PdfQueryPageSettingsEventArgs | イベントデータを含む [`PdfQueryPageSettingsEventArgs`](../../aspose.pdf.printing/pdfquerypagesettingseventargs/) 。 |
| currentPageInfo | PdfPrintPageInfo | 現在印刷中のページ情報。 |

### 参照

* クラス [PdfQueryPageSettingsEventArgs](../../aspose.pdf.printing/pdfquerypagesettingseventargs/)
* クラス [PdfPrintPageInfo](../pdfprintpageinfo/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)