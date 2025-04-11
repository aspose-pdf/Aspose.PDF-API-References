---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Görünüm tercihlerini değiştirir
type: docs
weight: 90
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference metodu

Görünüm tercihlerini değiştirir.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| viewerAttribution | Int32 | ViewerPreference sınıfında tanımlanan görünüm atıfı. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)