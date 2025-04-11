---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Exporta marcadores para arquivo XML
type: docs
weight: 50
url: /pt/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Exporta marcadores para arquivo XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlFile | String | O arquivo XML de saída. |

## Exemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Exporta marcadores para fluxo XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Fluxo de saída onde os dados serão armazenados. |

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)