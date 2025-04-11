---
title: PdfPageEditor.GetPages
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor メソッド。ページの総数を返します
type: docs
weight: 150
url: /ja/net/aspose.pdf.facades/pdfpageeditor/getpages/
---
## PdfPageEditor.GetPages メソッド

ページの総数を返します。

```csharp
public int GetPages()
```

### 戻り値

ページ数。

## 例

以下の例は、GetPages() メソッドの使用を示しています：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
Console.WriteLine("Document has: " + editor.GetPages());
```

### 参照

* クラス [PdfPageEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)