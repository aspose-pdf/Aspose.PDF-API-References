---
title: "PdfAnnotationEditor.ImportAnnotationsFromXfdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor-metod. Importerar alla annoteringar från en XFDF-fil."
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Importerar alla annotationer från en XFDF-fil.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xfdfFile | String | Den inmatade XFDF-filen. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Importerar alla annotationer från en XFDF-dataström.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xfdfStream | Stream | Den inmatade XFDF-dataströmmen. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


