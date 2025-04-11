---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Importa marcadores para o documento a partir de arquivo XML
type: docs
weight: 70
url: /pt/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importa marcadores para o documento a partir de arquivo XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlFile | String | O arquivo XML contendo a lista de marcadores. |

## Exemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importa marcadores para o documento a partir de arquivo XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Stream com dados de marcadores. |

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)