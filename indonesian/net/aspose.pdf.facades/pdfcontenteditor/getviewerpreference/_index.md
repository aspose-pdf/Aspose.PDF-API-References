---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Mengembalikan preferensi tampilan
type: docs
weight: 390
url: /id/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## Metode PdfContentEditor.GetViewerPreference

Mengembalikan preferensi tampilan.

```csharp
public int GetViewerPreference()
```

### Nilai Kembali

Mengembalikan sekumpulan bendera ViewerPrefernece

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)