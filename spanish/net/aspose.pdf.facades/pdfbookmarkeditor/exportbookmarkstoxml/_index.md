---
title: ExportBookmarksToXML
second_title: Referencia de API de Aspose.PDF para .NET
description: Exporta marcadores a un archivo XML.
type: docs
weight: 50
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Exporta marcadores a un archivo XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| xmlFile | String | El archivo XML de salida. |

### Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Ver también

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* asamblea [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Exporta marcadores a flujo XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de salida donde se almacenarán los datos. |

### Ver también

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
