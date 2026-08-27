---
title: "PdfPageEditor.GetPages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfPageEditor メソッド。ページ総数を返します"
type: docs
weight: 150
url: /ja/net/aspose.pdf.facades/pdfpageeditor/getpages/
---
## PdfPageEditor.GetPages method

ページ総数を返します。

```csharp
public int GetPages()
```

### 戻り値

ページ数。

## 例

次の例は GetPages() メソッドの使用例を示しています：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
Console.WriteLine("Document has: " + editor.GetPages());
```

### 関連項目

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


