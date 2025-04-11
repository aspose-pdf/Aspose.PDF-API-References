---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-Methode. Holt die Liste der Annotationen der angegebenen Typen
type: docs
weight: 60
url: /de/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Holt die Liste der Annotationen der angegebenen Typen.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | Int32 | Startseite, von der die Annotationen ausgewählt werden. |
| end | Int32 | Endseite, zu der die Annotationen ausgewählt werden. |
| annotTypes | String[] | Das Array der benötigten Annotationstypen. |

### Rückgabewert

Liste der Annotationen.

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Siehe auch

* Klasse [Annotation](../../../aspose.pdf.annotations/annotation/)
* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Holt die Liste der Annotationen der angegebenen Typen.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | Int32 | Startseite, von der die Annotationen ausgewählt werden. |
| end | Int32 | Endseite, zu der die Annotationen ausgewählt werden. |
| annotTypes | AnnotationType[] | Das Array der benötigten Annotationstypen. |

### Rückgabewert

Liste der Annotationen.

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Siehe auch

* Klasse [Annotation](../../../aspose.pdf.annotations/annotation/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)