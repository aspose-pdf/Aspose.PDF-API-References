---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea una anotación de sello de goma
type: docs
weight: 260
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Crea una anotación de sello de goma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | El número de la página original donde se creará la anotación. |
| annotRect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| icon | String | Un ícono que se utilizará para mostrar la anotación. Valor predeterminado: 'Borrador'. |
| annotContents | String | El contenido de la anotación. |
| color | Color | El color de la anotación. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Crea una anotación de sello de goma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | El número de la página original donde se creará la anotación. |
| annotRect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| annotContents | String | El contenido de la anotación. |
| color | Color | El color de la anotación. |
| appearanceFile | String | La ruta del archivo de apariencia. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Crea una anotación de sello de goma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | El número de la página original donde se creará la anotación. |
| annotRect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| annotContents | String | El contenido de la anotación. |
| color | Color | El color de la anotación. |
| appearanceStream | Stream | El flujo del archivo de apariencia. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)