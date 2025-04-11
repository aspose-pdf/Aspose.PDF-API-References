---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor method. Exports the content of the specified annotation types into XFDF
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
| xmlOutputStream | Stream | Lo stream XFDF di output. |
| start | Int32 | Pagina di partenza da cui verranno esportate le annotazioni del documento. |
| end | Int32 | Pagina finale a cui verranno esportate le annotazioni del documento. |
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

### Vedi Anche

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Esporta il contenuto dei tipi di annotazione specificati in XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlOutputStream | Stream | Lo stream XFDF di output. |
| start | Int32 | Pagina di partenza da cui verranno esportate le annotazioni del documento. |
| end | Int32 | Pagina finale a cui verranno esportate le annotazioni del documento. |
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

### Vedi Anche

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)