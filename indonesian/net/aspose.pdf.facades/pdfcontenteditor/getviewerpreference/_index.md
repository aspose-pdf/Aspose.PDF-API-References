---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfContentEditor metode. Mengembalikan preferensi tampilan"
type: docs
weight: 390
url: /id/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

Mengembalikan preferensi tampilan.

```csharp
public int GetViewerPreference()
```

### Nilai Kembalian

Mengembalikan sekumpulan flag ViewerPrefernece

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


