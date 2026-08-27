---
title: "PdfPageEditor.Zoom"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfPageEditor プロパティ。ズーム係数を取得または設定します。値 1.0 は 100% に相当し、デフォルト値は 1.0 です。以下の例はドキュメントページのズームを変更する方法を示しています。"
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## PdfPageEditor.Zoom property

ズーム係数を取得または設定します。値 1.0 は 100% に相当します。デフォルト値は 1.0 です。以下の例は Document ページのズームを変更する方法を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### 関連項目

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


