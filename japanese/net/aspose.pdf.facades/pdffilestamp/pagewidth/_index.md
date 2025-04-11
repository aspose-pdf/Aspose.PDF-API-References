---
title: PdfFileStamp.PageWidth
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp プロパティ。入力ファイルの最初のページの幅を取得します
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/pdffilestamp/pagewidth/
---
## PdfFileStamp.PageWidth プロパティ

入力ファイルの最初のページの幅を取得します。

```csharp
public float PageWidth { get; }
```

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Console.WriteLine("Width = " + fileStamp.PageWidth);
fileStamp.Close();
```

### 関連項目

* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)