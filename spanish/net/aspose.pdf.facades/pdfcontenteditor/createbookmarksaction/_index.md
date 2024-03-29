---
title: CreateBookmarksAction
second_title: Referencia de API de Aspose.PDF para .NET
description: Crea un marcador con la acción especificada.
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

Crea un marcador con la acción especificada.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| title | String | El título del marcador. |
| color | Color | El color del título del marcador. |
| boldFlag | Boolean | La bandera de la atribución en negrita. |
| italicFlag | Boolean | La bandera de atribución en cursiva. |
| file | String | Se requiere otro archivo o aplicación cuando el tipo de acción es "GoToR" o "Launch". |
| actionType | String | El tipo de acción. El valor puede ser: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | El destino local o destino remoto o URL. |

### Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
