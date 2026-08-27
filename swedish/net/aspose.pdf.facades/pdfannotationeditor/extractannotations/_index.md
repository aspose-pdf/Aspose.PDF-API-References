---
title: "PdfAnnotationEditor.ExtractAnnotations"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor-metod. Hämtar listan med annotationer av de angivna typerna"
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Hämtar listan över Annotation av de angivna typerna.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Startsidan från vilken annotationerna ska väljas. |
| end | Int32 | Slutsidan till vilken annotationerna ska väljas. |
| annotTypes | String[] | Arrayen med nödvändiga annotationstyper. |

### Returvärde

Lista över annotationer.

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Se även

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Hämtar listan över Annotation av de angivna typerna.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Startsidan från vilken annotationerna ska väljas. |
| end | Int32 | Slutsidan till vilken annotationerna ska väljas. |
| annotTypes | AnnotationType[] | Arrayen med nödvändiga annotationstyper. |

### Returvärde

Lista över annotationer.

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Se även

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


