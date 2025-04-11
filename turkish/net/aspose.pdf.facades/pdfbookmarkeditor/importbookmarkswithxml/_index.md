---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metodu. XML dosyasından belgeye yer imleri aktarır
type: docs
weight: 70
url: /tr/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

XML dosyasından belgeye yer imleri aktarır.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFile | String | Yer imleri listesini içeren XML dosyası. |

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

XML dosyasından belgeye yer imleri aktarır.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Yer imleri verileri içeren akış. |

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)