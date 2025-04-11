---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.XImage. Clase que representa un objeto de imagen X
type: docs
weight: 11350
url: /es/net/aspose.pdf/ximage/
---
## Clase XImage

Clase que representa un objeto de imagen X.

```csharp
public sealed class XImage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Si la imagen contiene transparencia, devuelve verdadero; de lo contrario, falso. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Obtiene el tipo de filtro de la imagen. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Obtiene la versión en escala de grises de la imagen. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Obtiene la altura de la imagen. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Obtiene una bandera que indica si la imagen debe ser tratada como una máscara de imagen (ver 8.9.6, "Imágenes enmascaradas"). Si esta bandera es verdadera, el valor de BitsPerComponent debe ser 1 y Mask y ColorSpace no deben ser especificados; las áreas no enmascaradas deben ser pintadas usando el color actual no de trazo. Valor por defecto: falso. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadatos de la imagen. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Obtiene o establece el nombre de la imagen. Tenga en cuenta que si cambia el nombre de la imagen que tiene referencias en el contenido de la página, el documento puede volverse incorrecto. Utilice el método XImage.Rename en este caso. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Obtiene el ancho de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Agrega una máscara de plantilla a la XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Devuelve el tipo de color de la imagen. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Devuelve el nombre de la imagen en su colección. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Recupera los datos de imagen en bruto de la imagen fuente. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Devuelve verdadero si ambas imágenes hacen referencia al mismo objeto. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Cambia el nombre de la imagen y reemplaza todas las referencias a la imagen con el nuevo nombre. |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Guarda los datos de la imagen en el flujo como imagen JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Guarda la imagen en el flujo con el formato solicitado. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Guarda los datos de la imagen en el flujo como imagen JPEG con la resolución especificada. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Guarda la imagen en el flujo con el formato solicitado y la resolución especificada. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Devuelve el flujo de la imagen original. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Véase también

* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)