---
title: ExtractAnnotations
second_title: Aspose.PDF för .NET API Referens
description: Hämtar listan över anteckningar av de angivna typerna.
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
| start | Int32 | Startsida från vilken anteckningarna kommer att väljas. |
| end | Int32 | Slutsida som anteckningarna kommer att väljas till. |
| annotTypes | String[] | Mängden nödvändiga anteckningstyper. |

### Returvärde

Anteckningslista.

### Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Se även

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfannotationeditor)
* hopsättning [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Hämtar listan över anteckningar av de angivna typerna.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Startsida från vilken anteckningarna kommer att väljas. |
| end | Int32 | Slutsida som anteckningarna kommer att väljas till. |
| annotTypes | AnnotationType[] | Mängden nödvändiga anteckningstyper. |

### Returvärde

Anteckningslista.

### Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Se även

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfannotationeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->