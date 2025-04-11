---
title: PdfAnnotationEditor.ImportAnnotationFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-metod. Importerar de angivna anteckningarna från XFDF-fil
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

Importerar de angivna anteckningarna från XFDF-fil.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xfdfFile | Sträng | Den inmatade XFDF-filen. |
| annotType | AnnotationType[] | Arrayen av anteckningar som ska importeras. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### Se Även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

Importerar de angivna anteckningarna från XFDF-datastream.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xfdfStream | Stream | Den inmatade XFDF-datastreamen. |
| annotType | AnnotationType[] | Arrayen av anteckningstyper som ska importeras. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### Se Även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)