---
title: "PdfAnnotationEditor.FlatteningAnnotations"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor-metod. Plattar till alla annotationer i dokumentet"
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Plattar till alla Annotation i Document.

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

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Plattar till alla Annotation i Document.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Anger lägen för plattning. |

### Se även

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Plattar till Annotation av de angivna typerna.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Startsidan. |
| end | Int32 | Sedan slutsidan. |
| annotType | AnnotationType[] | Annotationstyperna bör plattas till. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Se även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


