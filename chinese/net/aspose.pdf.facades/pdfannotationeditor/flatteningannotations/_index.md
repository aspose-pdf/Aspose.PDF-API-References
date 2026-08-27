---
title: "PdfAnnotationEditor.FlatteningAnnotations"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfAnnotationEditor 方法。将文档中的所有批注展平。"
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

将文档中的所有注释扁平化。

```csharp
public void FlatteningAnnotations()
```

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### 另请参见

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

将文档中的所有注释扁平化。

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flattenSettings | FlattenSettings | 指定展平模式。 |

### 另请参见

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

将指定类型的注释扁平化。

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 起始页。 |
| end | Int32 | 然后结束页面。 |
| annotType | AnnotationType[] | 注释类型应该被展平。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### 另请参见

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


