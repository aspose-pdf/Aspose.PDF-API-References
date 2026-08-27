---
title: "PdfAnnotationEditor.ImportAnnotationFromXfdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor metod. Importerar de angivna annotationerna från XFDF-fil"
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

Importerar de angivna Annotation från XFDF‑filen.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xfdfFile | String | Den inmatade XFDF-filen. |
| annotType | AnnotationType[] | Annotation-arrayen som ska importeras. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### Se även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

Importerar de angivna Annotation från XFDF‑datastreamen.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xfdfStream | Stream | Den inmatade XFDF-dataströmmen. |
| annotType | AnnotationType[] | Arrayen av annotationstyper som ska importeras. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### Se även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


