---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfAnnotationEditor. Exporte le contenu des types d'annotations spécifiés en XFDF
type: docs
weight: 50
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Exporte le contenu des types d'annotations spécifiés en XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlOutputStream | Stream | Le flux XFDF de sortie. |
| start | Int32 | Page de départ à partir de laquelle les annotations du document seront exportées. |
| end | Int32 | Page de fin vers laquelle les annotations du document seront exportées. |
| annotTypes | String[] | Le tableau des types d'annotations à exporter. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Voir aussi

* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Exporte le contenu des types d'annotations spécifiés en XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlOutputStream | Stream | Le flux XFDF de sortie. |
| start | Int32 | Page de départ à partir de laquelle les annotations du document seront exportées. |
| end | Int32 | Page de fin vers laquelle les annotations du document seront exportées. |
| annotTypes | AnnotationType[] | Le tableau des types d'annotations à exporter. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Voir aussi

* énum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)