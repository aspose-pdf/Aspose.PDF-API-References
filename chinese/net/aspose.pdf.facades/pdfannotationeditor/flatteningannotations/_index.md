---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 方法。扁平化文档中的所有注释
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

扁平化文档中的所有注释。

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

* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

扁平化文档中的所有注释。

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flattenSettings | FlattenSettings | 指定扁平化模式。 |

### 另请参见

* 类 [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

扁平化指定类型的注释。

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| start | Int32 | 起始页。 |
| end | Int32 | 结束页。 |
| annotType | AnnotationType[] | 应该被扁平化的注释类型。 |

## 示例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### 另请参见

* 枚举 [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* 类 [PdfAnnotationEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)