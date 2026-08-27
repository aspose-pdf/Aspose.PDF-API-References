---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfAnnotationEditor 方法。修改指定页面范围内指定类型的批注。它支持修改以下批注属性：Modified、Title、Contents、Color、Subject 和 Open。"
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

修改指定页面范围内指定类型的批注。支持修改以下批注属性：Modified、Title、Contents、Color、Subject 和 Open。

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 起始页码。 |
| end | Int32 | 结束页码。 |
| 批注 | 批注 | 批注对象包含新属性。 |

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

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


