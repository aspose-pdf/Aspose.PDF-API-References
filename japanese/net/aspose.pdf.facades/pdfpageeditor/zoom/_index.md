---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor プロパティ。ズーム係数を取得または設定します。値 1.0 は 100 に対応します。デフォルト値は 1.0 です。次の例は、ドキュメントページのズームを変更する方法を示しています。
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## PdfPageEditor.Zoom プロパティ

ズーム係数を取得または設定します。値 1.0 は 100% に対応します。デフォルト値は 1.0 です。次の例は、ドキュメントページのズームを変更する方法を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### 関連項目

* クラス [PdfPageEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)