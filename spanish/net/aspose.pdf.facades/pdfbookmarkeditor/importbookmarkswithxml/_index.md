---
title: ImportBookmarksWithXML
second_title: Referencia de API de Aspose.PDF para .NET
description: Importa marcadores al documento desde un archivo XML.
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importa marcadores al documento desde un archivo XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| xmlFile | String | El archivo XML que contiene la lista de marcadores. |

### Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Ver también

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* asamblea [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importa marcadores al documento desde un archivo XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Transmisión con datos de marcadores. |

### Ver también

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->