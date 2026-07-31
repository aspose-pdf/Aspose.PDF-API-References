---
title: "PdfAnnotationEditor.ExportAnnotationsXfdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfAnnotationEditor. Esporta il contenuto dei tipi di annotazione specificati in XFDF"
type: docs
weight: 50
url: /it/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Esporta il contenuto dei tipi di annotazione specificati in XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlOutputStream | Stream | Il flusso XFDF di output. |
| start | Int32 | Pagina iniziale da cui le annotazioni del documento saranno esportate. |
| end | Int32 | Pagina finale a cui le annotazioni del documento saranno esportate. |
| annotTypes | String[] | L'array dei tipi di annotazione da esportare. |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Vedi anche

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Esporta il contenuto dei tipi di annotazioni specificati in XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlOutputStream | Stream | Il flusso XFDF di output. |
| start | Int32 | Pagina iniziale da cui le annotazioni del documento saranno esportate. |
| end | Int32 | Pagina finale a cui le annotazioni del documento saranno esportate. |
| annotTypes | AnnotationType[] | L'array dei tipi di annotazione da esportare. |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Vedi anche

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


