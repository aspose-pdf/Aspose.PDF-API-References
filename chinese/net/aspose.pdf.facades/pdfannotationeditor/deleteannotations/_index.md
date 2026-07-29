---
title: "PdfAnnotationEditor.DeleteAnnotations"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfAnnotationEditor 方法。删除文档中的所有注释。"
type: docs
weight: 30
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

删除文档中的所有注释。

```csharp
public void DeleteAnnotations()
```

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

删除文档中指定类型的所有注释。

```csharp
public void DeleteAnnotations(string annotType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| annotType | String | 将被删除的注释类型。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


