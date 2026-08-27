---
title: "PdfAnnotationEditor.ExtractAnnotations"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfAnnotationEditor 方法。获取指定类型的批注列表。"
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

获取指定类型注释的列表。

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 起始页，从该页选择批注。 |
| end | Int32 | 结束页，批注将被选择至该页。 |
| annotTypes | String[] | 所需批注类型的数组。 |

### 返回值

批注列表。

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### 另请参见

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

获取指定类型注释的列表。

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 起始页，从该页选择批注。 |
| end | Int32 | 结束页，批注将被选择至该页。 |
| annotTypes | AnnotationType[] | 所需批注类型的数组。 |

### 返回值

批注列表。

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### 另请参见

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


