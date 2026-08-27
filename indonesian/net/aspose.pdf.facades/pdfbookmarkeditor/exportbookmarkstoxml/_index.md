---
title: "PdfBookmarkEditor.ExportBookmarksToXML"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfBookmarkEditor. Mengekspor bookmark ke file XML"
type: docs
weight: 50
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Mengekspor bookmark ke file XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlFile | String | File XML output. |

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Lihat Juga

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Mengekspor bookmark ke aliran XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran keluaran tempat data akan disimpan. |

### Lihat Juga

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


