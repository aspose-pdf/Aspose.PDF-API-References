---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfAnnotationEditor. Appiattisce tutte le annotazioni nel documento
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Appiattisce tutte le annotazioni nel documento.

```csharp
public void FlatteningAnnotations()
```

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Vedi Anche

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Appiattisce tutte le annotazioni nel documento.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Specifica le modalità di appiattimento. |

### Vedi Anche

* classe [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Appiattisce le annotazioni dei tipi specificati.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | Int32 | La pagina di inizio. |
| end | Int32 | La pagina di fine. |
| annotType | AnnotationType[] | I tipi di annotazione devono essere appiattiti. |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Vedi Anche

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)