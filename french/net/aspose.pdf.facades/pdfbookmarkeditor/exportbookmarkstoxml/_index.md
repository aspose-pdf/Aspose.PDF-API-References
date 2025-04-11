---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfBookmarkEditor. Exporte les signets vers un fichier XML
type: docs
weight: 50
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Exporte les signets vers un fichier XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlFile | String | Le fichier XML de sortie. |

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Voir aussi

* classe [PdfBookmarkEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Exporte les signets vers un flux XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie où les données seront stockées. |

### Voir aussi

* classe [PdfBookmarkEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)