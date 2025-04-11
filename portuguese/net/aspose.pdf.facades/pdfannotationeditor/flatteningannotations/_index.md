---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Achata todas as anotações no documento
type: docs
weight: 70
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Achata todas as anotações no documento.

```csharp
public void FlatteningAnnotations()
```

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Veja Também

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Achata todas as anotações no documento.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Especifica modos de achatamento. |

### Veja Também

* classe [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Achata as anotações dos tipos especificados.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| start | Int32 | A página inicial. |
| end | Int32 | A página final. |
| annotType | AnnotationType[] | Os tipos de anotações que devem ser achatados. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Veja Também

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)