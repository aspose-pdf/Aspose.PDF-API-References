---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。修改指定页面范围内指定类型的注释。它支持修改下列注释属性：修改过的、标题、内容、颜色、主题和打开状态。
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations 方法

修改指定页面范围内指定类型的注释。它支持修改下列注释属性：修改过的、标题、内容、颜色、主题和打开状态。

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 起始页码。 |
| end | Int32 | 结束页码。 |
| annotation | Annotation | 包含新属性的注释对象。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### 另请参见

* 类 [Annotation](../../../aspose.pdf.annotations/annotation/)
* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)