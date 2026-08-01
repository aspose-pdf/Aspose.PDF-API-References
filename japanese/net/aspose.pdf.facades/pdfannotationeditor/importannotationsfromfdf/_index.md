---
title: "PdfAnnotationEditor.ImportAnnotationsFromFdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAnnotationEditor メソッド。FDF ファイルからすべての注釈をインポートします"
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method

FDF ファイルからすべての注釈をインポートします。

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fdfFile | String | 入力 FDF ファイルです。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


