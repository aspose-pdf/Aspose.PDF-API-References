---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor メソッド。FDF ファイルからすべての注釈をインポートします
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf メソッド

FDF ファイルからすべての注釈をインポートします。

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fdfFile | 文字列 | 入力 FDF ファイル。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)