---
title: "PdfAnnotationEditor.ExportAnnotationsXfdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor-metod. Exporterar innehållet för de angivna annoteringstyperna till XFDF."
type: docs
weight: 50
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Exporterar innehållet för de angivna Annotation‑typerna till XFDF.

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlOutputStream | Stream | Utdata-XFDF-strömmen. |
| start | Int32 | Startsidan från vilken dokumentets annoteringar kommer att exporteras. |
| end | Int32 | Slutsidan till vilken dokumentets annoteringar kommer att exporteras. |
| annotTypes | String[] | Arrayen med annoteringstyper som ska exporteras. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Exporterar innehållet för de angivna Annotation‑typerna till XFDF.

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlOutputStream | Stream | Utdata-XFDF-strömmen. |
| start | Int32 | Startsidan från vilken dokumentets annoteringar kommer att exporteras. |
| end | Int32 | Slutsidan till vilken dokumentets annoteringar kommer att exporteras. |
| annotTypes | AnnotationType[] | Arrayen med annoteringstyper som ska exporteras. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Se även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


