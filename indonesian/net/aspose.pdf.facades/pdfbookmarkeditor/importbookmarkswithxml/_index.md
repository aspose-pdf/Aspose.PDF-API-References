---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfBookmarkEditor. Mengimpor bookmark ke dokumen dari file XML
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Mengimpor bookmark ke dokumen dari file XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlFile | String | File XML yang berisi daftar bookmark. |

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Mengimpor bookmark ke dokumen dari file XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Stream dengan data bookmark. |

### Lihat Juga

* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)