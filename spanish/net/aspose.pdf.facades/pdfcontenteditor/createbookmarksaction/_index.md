---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea un marcador con la acción especificada
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## Método PdfContentEditor.CreateBookmarksAction

Crea un marcador con la acción especificada.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| title | String | El título del marcador. |
| color | Color | El color del título del marcador. |
| boldFlag | Boolean | La bandera de atribución en negrita. |
| italicFlag | Boolean | La bandera de atribución en cursiva. |
| file | String | Otro archivo o aplicación requerido cuando el tipo de acción es "GoToR" o "Launch". |
| actionType | String | El tipo de acción. El valor puede ser: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | El destino local o destino remoto o URL. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)