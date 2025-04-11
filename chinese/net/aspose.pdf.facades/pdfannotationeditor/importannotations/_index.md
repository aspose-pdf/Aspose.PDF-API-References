---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。从另一个 PDF 文档的数组中将指定的注释导入文档
type: docs
weight: 90
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

从另一个 PDF 文档的数组中将指定的注释导入文档。

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| annotFile | String[] | 包含源注释的 PDF 文档路径数组。 |
| annotType | AnnotationType[] | 要导入的注释类型数组。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### 另见

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

从另一个 PDF 文档的数组中将注释导入文档。

```csharp
public void ImportAnnotations(string[] annotFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| annotFile | String[] | 包含源注释的 PDF 文档路径数组。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### 另见

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

从另一个 PDF 文档流的数组中将指定的注释导入文档。

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| annotFileStream | Stream[] | 包含源注释的 PDF 文档流的数组。 |
| annotType | AnnotationType[] | 要导入的注释类型。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
stream[0]= File.OpenRead("with_annots1.pdf");
stream[1]= File.OpenRead("with_annots2.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(streams, annotTypes);
editor.Save("example_out.pdf");
stream[0].Close();
stream[1].Close();
```

### 另见

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

从另一个 PDF 文档流的数组中将注释导入文档。

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| annotFileStream | Stream[] | 包含源注释的 PDF 文档流的数组。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
streams[0]= File.OpenRead("with_annots1.pdf");
streams[1]= File.OpenRead("with_annots2.pdf");
editor.ImportAnnotations(streams);
editor.Save("example_out.pdf");
streams[0].Close();
streams[1].Close();
```

### 另见

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)