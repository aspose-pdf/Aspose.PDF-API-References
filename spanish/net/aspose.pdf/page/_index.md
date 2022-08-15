---
title: Page
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase que representa la página del documento PDF.
type: docs
weight: 5790
url: /es/net/aspose.pdf/page/
---
## Page class

Clase que representa la página del documento PDF.

```csharp
public sealed class Page : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | Obtiene la colección de propiedades de la página. |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | Obtiene la colección de anotaciones de página. [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | Obtiene o establece el cuadro de arte de la página. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | Obtiene la colección de artefactos en la página. |
| [Background](../../aspose.pdf/page/background) { get; set; } | Obtiene o establece el color de fondo de la página. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | Obtiene o establece la imagen de fondo de la página (solo para el generador). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | Obtiene o establece el cuadro de sangrado de la página. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | Establece el tipo de color de las páginas en función de la información obtenida de los operadores SetColor, imágenes y formularios. |
| [Contents](../../aspose.pdf/page/contents) { get; } | Obtiene una colección de operadores en el flujo de contenido de la página. [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | Obtiene o establece el cuadro de recorte de la página. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | Obtiene la duración de visualización de la página establecida. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si no se define la duración. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | Obtiene una lista de objetos de campo en orden de tabulación en esta página. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | Obtiene o establece el pie de página. |
| [Group](../../aspose.pdf/page/group) { get; set; } | Obtiene o establece una clase de atributos de grupo que especifica los atributos del grupo de páginas de la página para usar en el modelo de imagen transparente. |
| [Header](../../aspose.pdf/page/header) { get; set; } | Obtiene o establece el encabezado de la página. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | Obtiene o establece la adición de párrafos después del último párrafo de la página |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | Obtiene o establece la colección de capas. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | Obtiene o establece el cuadro multimedia de la página. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | Obtiene o establece el estilo de línea para las notas (solo para el generador) |
| [Number](../../aspose.pdf/page/number) { get; } | Obtener número de página. |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | Obtiene o establece la información de la página (solo para el generador, no se completa al leer el archivo). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | Obtiene los párrafos. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | Obtiene o establece el rectángulo de la página. Se devuelve el cuadro de recorte de página si se especifica; de lo contrario, se devuelve el cuadro de medios de página. Tenga en cuenta que esta propiedad no tiene en cuenta la rotación de páginas. Para obtener un rectángulo de página teniendo en cuenta la rotación, utilice ActualRect. |
| [Resources](../../aspose.pdf/page/resources) { get; } | Obtiene los recursos de la página. El objeto de recursos contiene colecciones de imágenes, formularios y fuentes. [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | Obtiene o establece la rotación de la página. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | Obtiene la matriz de transformación de la página. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | Obtiene o establece el orden de tabulación de la página. Valores posibles: Fila, Columna. Predeterminado, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | Obtiene o establece la tabla de contenido info. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | Obtiene o establece el cuadro de recorte de la página. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | Obtiene o establece el valor de UserUnit. Un número positivo que indica el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1 ⁄ 72 pulgadas. El valor predeterminado es 1. Establezca un valor cero o negativo para borrar esta entrada en la página. |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | Obtiene o establece la marca de agua de la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | Acepta[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector) objeto visitante que proporciona funcionalidad para trabajar con anotaciones. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | Acepta[`ImagePlacementAbsorber`](../imageplacementabsorber) objeto de visitante que proporciona funcionalidad para trabajar con objetos de colocación de imágenes. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | Acepta[`TextAbsorber`](../../aspose.pdf.text/textabsorber) objeto visitante que proporciona funcionalidad para trabajar con objetos de texto. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | Acepta[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber) objeto visitante que proporciona funcionalidad para trabajar con objetos de texto. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | Agrega una imagen a la página y la ubica en el medio del rectángulo especificado guardando la proporción de la imagen. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | Agrega una imagen a la página y la ubica en el medio del rectángulo especificado guardando la proporción de la imagen. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | Agrega una imagen de búsqueda en la página y la ubica en el medio del rectángulo especificado guardando la proporción de la imagen. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | Agrega una imagen en la página y la coloca según la posición del rectángulo de la imagen. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | Poner sello en página. El sello puede ser un número de página, una imagen o un texto simple, por ejemplo, algún logotipo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | Convierte la página actual como mapa de bits y luego devuelve una matriz de bytes. |
| [AsXml](../../aspose.pdf/page/asxml)() | Convierte la página actual como xml en codificación utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | Calcula el valor de bbox: rectángulo que contiene contenido sin márgenes visibles. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | Convertir página a PNG para flujo de imágenes DSR, OMR, OCR. |
| [Dispose](../../aspose.pdf/page/dispose)() | Libera memoria |
| [Flatten](../../aspose.pdf/page/flatten)() | Elimina todos los campos ubicados en la página y coloca sus valores en su lugar. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | Borra los datos almacenados en caché |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | Devuelve notificaciones sobre operaciones internas con el contenido de la página. (Ahora solo se admiten notificaciones sobre eventos de párrafo en escenarios de adición de texto). |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | Devuelve el rectángulo de la página. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | Obtiene el indicador de si la página está en blanco o no. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | Convierte la página a escala de grises. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | Envía la página para procesar con el dispositivo de página dado. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | Envía la página para procesar con el dispositivo de página dado. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | Establece el tamaño de página por página. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | Traduce el valor entero al miembro de enumeración de rotación correspondiente. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | Traduce el miembro de enumeración de rotación en un valor entero. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | Procedimiento para personalizar encabezado y pie de página. |

### Ver también

* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
