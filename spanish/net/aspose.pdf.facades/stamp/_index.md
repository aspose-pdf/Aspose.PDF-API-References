---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.Stamp. Clase que representa un sello
type: docs
weight: 4720
url: /es/net/aspose.pdf.facades/stamp/
---
## Clase Stamp

Clase que representa un sello.

```csharp
public sealed class Stamp
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Stamp](stamp/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Obtiene o establece un valor de BlendingColorSpace que define un espacio de color que se utiliza para realizar operaciones de transparencia y mezcla en la página. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Obtiene o establece el estado de fondo. Si es verdadero, el sello se colocará como fondo de la página sellada. Por defecto se establece en falso. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Obtiene o establece la opacidad del sello. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Obtiene o establece el número de página. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Obtiene o establece un arreglo con los números de las páginas que se verán afectadas por el sello. Si Pages = null, todas las páginas del documento se ven afectadas. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Obtiene o establece la calidad de la imagen del sello en porcentaje. Valores válidos 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Obtiene o establece la rotación del sello en grados. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Obtiene o establece el identificador del sello. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Establece la imagen que se utilizará como sello. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Establece la imagen como un sello. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Establece el texto como sello. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Establece el archivo PDF y el número de página que se utilizarán como sello. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Establece el archivo PDF y el número de página que se utilizarán como sello. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Establece el estado del texto del sello. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Establece el tamaño del sello de imagen. La imagen se escalará de acuerdo con los valores especificados. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Establece la posición en la página donde se colocará el sello. |

### Ver También

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)