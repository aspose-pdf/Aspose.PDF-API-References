---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metod. Exporterar innehållet av de angivna annotationstyperna till XFDF
type: docs
weight: 50
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Exporterar innehållet av de angivna annotationstyperna till XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlOutputStream | Stream | Utdata XFDF-ström. |
| start | Int32 | Start sida från vilken annotationerna i dokumentet kommer att exporteras. |
| end | Int32 | Slut sida till vilken annotationerna i dokumentet kommer att exporteras. |
| annotTypes | String[] | Array av annotationstyper som behöver exporteras. |

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

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Exporterar innehållet av de angivna annotationstyperna till XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlOutputStream | Stream | Utdata XFDF-ström. |
| start | Int32 | Start sida från vilken annotationerna i dokumentet kommer att exporteras. |
| end | Int32 | Slut sida till vilken annotationerna i dokumentet kommer att exporteras. |
| annotTypes | AnnotationType[] | Array av annotationstyper som behöver exporteras. |

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

### Se Även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* klass [PdfAnnotationEditor](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)