---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea anotación de línea
type: docs
weight: 180
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## Método PdfContentEditor.CreateLine

Crea anotación de línea.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectángulo | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | Cadena | El contenido de la anotación. |
| x1 | Simple | La coordenada horizontal de inicio de la línea. |
| y1 | Simple | La coordenada vertical de inicio de la línea. |
| x2 | Simple | La coordenada horizontal de fin de la línea. |
| y2 | Simple | La coordenada vertical de fin de la línea. |
| page | Int32 | El número de la página original donde se creará la anotación. |
| border | Int32 | El ancho del borde en puntos. Si este valor es 0, no se dibuja ningún borde. El valor predeterminado es 1. |
| clr | Color | El color de la línea. |
| borderStyle | Cadena | El estilo del borde que especifica el ancho y el patrón de guiones que se utilizará para dibujar la línea. Este valor puede ser: "S" (Sólido), "D" (Discontinuo), "B" (Biselado), "I" (Inseto), "U" (Subrayado). |
| dashArray | Int32[] | Un arreglo de guiones que define un patrón de guiones y espacios que se utilizará para dibujar un borde discontinuo. Si se utiliza, borderSyle debe configurarse en consecuencia a "D". |
| LEArray | Cadena[] | Un arreglo de dos valores que especifican respectivamente el estilo de inicio y fin de la línea de dibujo. Los valores pueden ser: "Cuadrado", "Círculo", "Rombo", "FlechaAbierta", "FlechaCerrada", "Ninguno", "Corte", "RFlechaAbierta", "RFlechaCerrada", "Raya". |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)