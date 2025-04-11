---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-Methode. Flattened alle Annotationen im Dokument
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Flattened alle Annotationen im Dokument.

```csharp
public void FlatteningAnnotations()
```

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Siehe auch

* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Flattened alle Annotationen im Dokument.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Gibt die Modi des Flattenings an. |

### Siehe auch

* Klasse [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Flattened die Annotationen der angegebenen Typen.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | Int32 | Die Startseite. |
| end | Int32 | Die Endseite. |
| annotType | AnnotationType[] | Die Annotationstypen, die geflattet werden sollen. |

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Siehe auch

* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)