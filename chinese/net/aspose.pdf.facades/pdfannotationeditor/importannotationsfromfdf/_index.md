---
title: "PdfAnnotationEditor.ImportAnnotationsFromFdf"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfAnnotationEditor 方法。导入所有来自 FDF 文件的注释。"
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method

从 FDF 文件导入所有注释。

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fdfFile | String | 输入的 FDF 文件。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


