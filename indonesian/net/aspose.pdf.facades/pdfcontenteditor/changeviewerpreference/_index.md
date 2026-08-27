---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Mengubah preferensi tampilan"
type: docs
weight: 90
url: /id/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

Mengubah preferensi tampilan.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| viewerAttribution | Int32 | Atribusi tampilan yang didefinisikan dalam kelas ViewerPreference. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


