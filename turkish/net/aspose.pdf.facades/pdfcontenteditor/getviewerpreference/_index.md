---
title: GetViewerPreference
second_title: Aspose.PDF for .NET API Referansı
description: Görünüm tercihini döndürür.
type: docs
weight: 390
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

Görünüm tercihini döndürür.

```csharp
public int GetViewerPreference()
```

### Geri dönüş değeri

ViewerPrefernece bayrakları kümesini döndürür

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
