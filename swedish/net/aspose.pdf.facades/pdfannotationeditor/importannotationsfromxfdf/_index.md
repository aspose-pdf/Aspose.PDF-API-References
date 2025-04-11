---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metod. Importerar alla anteckningar från XFDF-fil
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Importerar alla anteckningar från XFDF-fil.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xfdfFile | Sträng | Den inmatade XFDF-filen. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Importerar alla anteckningar från XFDF datastream.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xfdfStream | Stream | Den inmatade XFDF datastream. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)