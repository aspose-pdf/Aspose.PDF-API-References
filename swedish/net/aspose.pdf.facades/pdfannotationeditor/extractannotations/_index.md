---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-metod. Hämtar listan över anteckningar av de angivna typerna
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Hämtar listan över anteckningar av de angivna typerna.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Start sida från vilken anteckningarna kommer att väljas. |
| end | Int32 | Slut sida till vilken anteckningarna kommer att väljas. |
| annotTypes | String[] | Array av nödvändiga anteckningstyper. |

### Returvärde

Lista över anteckningar.

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Se Även

* klass [Annotation](../../../aspose.pdf.annotations/annotation/)
* klass [PdfAnnotationEditor](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Hämtar listan över anteckningar av de angivna typerna.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Start sida från vilken anteckningarna kommer att väljas. |
| end | Int32 | Slut sida till vilken anteckningarna kommer att väljas. |
| annotTypes | AnnotationType[] | Array av nödvändiga anteckningstyper. |

### Returvärde

Lista över anteckningar.

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Se Även

* klass [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* klass [PdfAnnotationEditor](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)