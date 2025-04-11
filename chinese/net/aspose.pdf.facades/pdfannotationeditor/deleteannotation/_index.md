---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。删除具有指定注释名称的注释
type: docs
weight: 20
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation 方法

删除具有指定注释名称的注释。

```csharp
public void DeleteAnnotation(string annotName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| annotName | 字符串 | 注释名称 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### 另见

* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)