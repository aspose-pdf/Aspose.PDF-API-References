---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Importa marcadores al documento desde un archivo XML
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importa marcadores al documento desde un archivo XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFile | String | El archivo XML que contiene la lista de marcadores. |

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importa marcadores al documento desde un archivo XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo con datos de marcadores. |

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)