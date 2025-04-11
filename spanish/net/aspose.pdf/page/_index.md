---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Page. Clase que representa una página de un documento PDF
type: docs
weight: 8050
url: /es/net/aspose.pdf/page/
---
## Clase Page

Clase que representa una página de un documento PDF.

```csharp
public sealed class Page : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Obtiene la colección de propiedades de la página. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Obtiene la colección de anotaciones de la página. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Obtiene o establece el cuadro de arte de la página. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Obtiene la colección de artefactos en la página. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Obtiene o establece el color de fondo de la página. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Obtiene o establece la imagen de fondo para la página (solo para generador, no se llena al leer el documento). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Obtiene o establece el cuadro de sangrado de la página. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Establece el tipo de color de las páginas basado en la información obtenida de los operadores SetColor, imágenes y formularios. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Obtiene la colección de operadores en el flujo de contenido de la página. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Obtiene o establece el cuadro de recorte de la página. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Obtiene o establece la duración de visualización de la página. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si la duración no está definida. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Obtiene la lista de objetos Field en el orden de tabulación en esta página. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Obtiene o establece el pie de página. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Obtiene o establece una clase de atributos de grupo que especifica los atributos del grupo de páginas de la página para su uso en el modelo de imagen transparente. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Obtiene o establece el encabezado de la página. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Obtiene o establece la adición de párrafos después del último párrafo de la página. |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Obtiene o establece la colección de capas. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Obtiene o establece el cuadro de medios de la página. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Obtiene o establece el estilo de línea para notas. (solo para generador, no se llena al leer el documento) |
| [Number](../../aspose.pdf/page/number/) { get; } | Obtiene el número de la página. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Obtiene o establece la información de la página (solo para generador, no se llena al leer el documento). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Obtiene los párrafos. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Obtiene o establece el rectángulo de la página. Para obtener: se devuelve el cuadro de recorte de la página si se especifica, de lo contrario se devuelve el cuadro de medios de la página. Para establecer: el cuadro de medios de la página siempre se establece. Tenga en cuenta que esta propiedad no considera la rotación de la página. Para obtener el rectángulo de la página considerando la rotación, utilice ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Obtiene los recursos de la página. El objeto de recursos contiene colecciones de imágenes, formularios y fuentes. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Obtiene o establece la rotación de la página. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Obtiene la matriz de transformación para la página. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Obtiene o establece el orden de tabulación de la página. Valores posibles: Fila, Columna. Predeterminado, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Obtiene o establece la información de la tabla de contenido. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Obtiene o establece el cuadro de recorte de la página. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Obtiene o establece el valor de UserUnit. Un número positivo que da el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1 / 72 pulgadas. El valor predeterminado es 1. Establezca un valor cero o negativo para borrar esta entrada en la página. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Obtiene o establece la marca de agua de la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Acepta el objeto visitante [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) que proporciona funcionalidad para trabajar con anotaciones. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Acepta el objeto visitante [`ImagePlacementAbsorber`](../imageplacementabsorber/) que proporciona funcionalidad para trabajar con objetos de colocación de imágenes. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Acepta el objeto visitante [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) que proporciona funcionalidad para trabajar con objetos de texto. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Acepta el objeto visitante [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) que proporciona funcionalidad para trabajar con objetos de texto. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Agrega gráficos a la página. Funciona más rápido que agregar elementos uno por uno con el método [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Agrega una imagen a la página y la ubica en el medio del rectángulo especificado manteniendo la proporción de la imagen. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Agrega una imagen a la página y la ubica en el medio del rectángulo especificado manteniendo la proporción de la imagen. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Agrega una imagen buscable a la página y la ubica en el medio del rectángulo especificado manteniendo la proporción de la imagen. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Agrega una imagen en la página y la coloca según la posición del rectángulo de la imagen. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Coloca un sello en la página. El sello puede ser un número de página, una imagen o un texto simple, por ejemplo, un logotipo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Convierte la página actual en un mapa de bits y luego devuelve un array de bytes. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Convierte la página actual en xml en codificación utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Calcula el valor bbox - rectángulo que contiene contenidos sin márgenes visibles. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Convierte la página a PNG para el flujo de imagen DSR, OMR, OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Elimina gráficos de la página. Funciona más rápido que eliminar elementos uno por uno con el método [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Libera memoria |
| [Flatten](../../aspose.pdf/page/flatten/)() | Elimina todos los campos ubicados en la página y coloca sus valores en su lugar. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Limpia los datos en caché |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Devuelve notificaciones sobre operaciones internas con el contenido de la página. (Solo se admiten notificaciones sobre eventos de párrafo en escenarios de adición de texto en este momento). |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Devuelve el rectángulo de la página de acuerdo con su CropBox (o MediaBox si CropBox es nulo). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Recupera los recursos asociados con la página. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Detecta la presencia de gráficos vectoriales, si están presentes en la página. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Obtiene el indicador de si la página está en blanco o no. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Convierte la página a escala de grises. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Fusiona todas las capas en la página en una sola capa con el nuevo nombre de capa especificado. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Fusiona todas las capas en la página en una sola capa con el nuevo nombre de capa especificado y un Id de grupo de contenido opcional. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Cambia el tamaño de la página. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Envía la página para procesar con el dispositivo de página dado. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Envía la página para procesar con el dispositivo de página dado. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Establece el tamaño de la página para la página. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Intenta guardar gráficos vectoriales si están presentes en la página. El formato de guardado es SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Traduce el valor entero en el miembro de enumeración de rotación correspondiente. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Traduce el miembro de enumeración de rotación en un valor entero. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Evento para personalizar el encabezado y el pie de página. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Procedimiento para personalizar el encabezado y el pie de página. |

### Véase También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)