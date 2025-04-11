---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. XFDF dosyasından tüm notları içe aktarır
type: docs
weight: 110
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

XFDF dosyasından tüm notları içe aktarır.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xfdfFile | String | Girdi XFDF dosyası. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

XFDF veri akışından tüm notları içe aktarır.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xfdfStream | Stream | Girdi XFDF veri akışı. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)