---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfBookmarkEditor. Importe les signets dans le document à partir du fichier XML."
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importe les signets dans le document à partir d'un fichier XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlFile | String | Le fichier XML contenant la liste des signets. |

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importe les signets dans le document à partir d'un fichier XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux contenant les données des signets. |

### Voir aussi

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


