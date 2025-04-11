---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metodu. Yer imlerini XML dosyasına aktarır
type: docs
weight: 50
url: /tr/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Yer imlerini XML dosyasına aktarır.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFile | String | Çıktı XML dosyası. |

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Yer imlerini XML akışına aktarır.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Verilerin depolanacağı çıktı akışı. |

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)