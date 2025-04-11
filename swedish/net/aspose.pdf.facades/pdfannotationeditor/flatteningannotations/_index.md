---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metod. Plattar ut alla anteckningar i dokumentet
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Plattar ut alla anteckningar i dokumentet.

```csharp
public void FlatteningAnnotations()
```

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Plattar ut alla anteckningar i dokumentet.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Anger lägen för utplattning. |

### Se Även

* klass [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Plattar ut anteckningarna av de angivna typerna.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Startsidnummer. |
| end | Int32 | Slut sidnummer. |
| annotType | AnnotationType[] | De anteckningstyper som ska plattas ut. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Se Även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)