---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Exporta marcadores a un archivo XML
type: docs
weight: 50
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Exporta marcadores a un archivo XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFile | String | El archivo XML de salida. |

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Exporta marcadores a un flujo XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de salida donde se almacenarán los datos. |

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)