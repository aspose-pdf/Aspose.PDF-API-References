---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。将指定注释类型的内容导出为 XFDF
type: docs
weight: 50
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

将指定注释类型的内容导出为 XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlOutputStream | Stream | 输出的 XFDF 流。 |
| start | Int32 | 从文档中导出注释的起始页。 |
| end | Int32 | 导出文档注释的结束页。 |
| annotTypes | String[] | 需要导出的注释类型数组。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### 另请参见

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

将指定注释类型的内容导出为 XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlOutputStream | Stream | 输出的 XFDF 流。 |
| start | Int32 | 从文档中导出注释的起始页。 |
| end | Int32 | 导出文档注释的结束页。 |
| annotTypes | AnnotationType[] | 需要导出的注释类型数组。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### 另请参见

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)