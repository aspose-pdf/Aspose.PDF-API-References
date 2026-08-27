---
title: "PdfAnnotationEditor.FlatteningAnnotations"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfAnnotationEditor metodo. Appiattisce tutte le annotazioni nel documento"
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

### Vedi anche

* class [PdfAnnotationEditor](../)
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

### Vedi anche

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
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
| start | Int32 | La pagina iniziale. |
| end | Int32 | Quindi la pagina finale. |
| annotType | AnnotationType[] | I tipi di annotazione dovrebbero essere appiattiti. |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Vedi anche

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


