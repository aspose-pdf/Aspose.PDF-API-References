---
title: PdfAnnotationEditor.ImportAnnotationFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belirtilen notları XFDF dosyasından içe aktarır
type: docs
weight: 80
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

Belirtilen notları XFDF dosyasından içe aktarır.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xfdfFile | String | Girdi XFDF dosyası. |
| annotType | AnnotationType[] | İçe aktarılacak notlar dizisi. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

Belirtilen notları XFDF veri akışından içe aktarır.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xfdfStream | Stream | Girdi XFDF veri akışı. |
| annotType | AnnotationType[] | İçe aktarılacak not türleri dizisi. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)