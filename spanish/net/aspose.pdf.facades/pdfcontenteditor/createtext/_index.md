---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea una anotación de texto en el documento PDF
type: docs
weight: 290
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## Método PdfContentEditor.CreateText

Crea una anotación de texto en el documento PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| title | String | El título de la anotación. |
| contents | String | El contenido de la anotación. |
| open | Boolean | Una bandera que especifica si la anotación debe mostrarse inicialmente abierta. |
| icon | String | El nombre de un ícono que se utilizará para mostrar la anotación. Este valor puede ser: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| page | Int32 | El número de la página original donde se creará la anotación de texto. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)