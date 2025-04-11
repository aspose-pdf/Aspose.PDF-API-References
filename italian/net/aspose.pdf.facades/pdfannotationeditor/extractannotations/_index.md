---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfAnnotationEditor. Ottiene l'elenco delle annotazioni dei tipi specificati
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Ottiene l'elenco delle annotazioni dei tipi specificati.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | Int32 | Pagina di partenza da cui verranno selezionate le annotazioni. |
| end | Int32 | Pagina finale a cui verranno selezionate le annotazioni. |
| annotTypes | String[] | L'array dei tipi di annotazione necessari. |

### Valore di ritorno

Elenco delle annotazioni.

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Vedi Anche

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Ottiene l'elenco delle annotazioni dei tipi specificati.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | Int32 | Pagina di partenza da cui verranno selezionate le annotazioni. |
| end | Int32 | Pagina finale a cui verranno selezionate le annotazioni. |
| annotTypes | AnnotationType[] | L'array dei tipi di annotazione necessari. |

### Valore di ritorno

Elenco delle annotazioni.

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Vedi Anche

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)