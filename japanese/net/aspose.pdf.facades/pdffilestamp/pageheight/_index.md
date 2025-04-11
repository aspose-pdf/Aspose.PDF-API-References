---
title: PdfFileStamp.PageHeight
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp プロパティ。ソースファイルの最初のページの高さを取得します
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/pdffilestamp/pageheight/
---
## PdfFileStamp.PageHeight プロパティ

ソースファイルの最初のページの高さを取得します。

```csharp
public float PageHeight { get; }
```

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Console.WriteLine("Height = " + fileStamp.PageHeight);
fileStamp.Close();
```

### 参照

* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)