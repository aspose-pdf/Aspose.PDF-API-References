---
title: ExtractAnnotations
second_title: Aspose.PDF for .NET API 参考
description: 获取指定类型的注解列表
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

获取指定类型的注解列表。

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 从中选择注释的起始页。 |
| end | Int32 | 将选择注释的结束页面。 |
| annotTypes | String[] | 所需注释类型的数组。 |

### 返回值

注释列表。

### 例子

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### 也可以看看

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfannotationeditor)
* 部件 [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

获取指定类型的注解列表。

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 从中选择注释的起始页。 |
| end | Int32 | 将选择注释的结束页面。 |
| annotTypes | AnnotationType[] | 所需注释类型的数组。 |

### 返回值

注释列表。

### 例子

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### 也可以看看

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfannotationeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->