---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。 从 FDF 文件导入所有注释
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf 方法

从 FDF 文件导入所有注释。

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fdfFile | 字符串 | 输入的 FDF 文件。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)