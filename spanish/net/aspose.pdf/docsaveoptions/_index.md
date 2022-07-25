---
title: DocSaveOptions
second_title: Referencia de API de Aspose.PDF para .NET
description: Guardar opciones para exportar a formato Doc
type: docs
weight: 1840
url: /es/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Guardar opciones para exportar a formato Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocSaveOptions](docsaveoptions)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend) { get; set; } | Usar saltos de párrafo o de línea |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize) { get; set; } | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Obtiene o establece un valor booleano que indica que el objeto de respuesta se cerrará después de que el documento se guarde en la respuesta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Este atributo activó la funcionalidad para extraer imágenes o texto para documentos PDF con subcapa OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format) { get; set; } | Formato de salida |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx) { get; set; } | Imágenes convertidas Resolución X. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony) { get; set; } | Imágenes convertidas Y resolución. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines) { get; set; } | Este parámetro se usa para agrupar líneas de texto en párrafos. Determina qué tan separadas pueden estar dos líneas de texto relativas. Especificado en cientos de por ciento de la altura de las líneas de texto. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath) { get; set; } | Define la ruta (nombre de archivo o nombre de directorio) para contener datos temporales al convertir en modo de ahorro de memoria. |
| [Mode](../../aspose.pdf/docsaveoptions/mode) { get; set; } | Modo reconocimiento. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets) { get; set; } | Activar el reconocimiento de balas |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity) { get; set; } | En Pdf, las palabras pueden representarse internamente con operadores que imprimen palabras imprimiendo independientemente sus letras o sílabas. Entonces, para detectar palabras, a veces necesitamos detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre elementos de texto (letras, sílabas) que debe tratarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen . (la presencia de espacios vacíos al menos con este ancho entre letras significa que elementos textuales pertenecen a palabras diferentes). Está normado al tamaño de fuente - 1.0 significa 100% del tamaño de fuente de la supuesta palabra. ¡ATENCIÓN! Se usa solo en casos cuando el PDF de origen contiene fuentes específicas poco utilizadas para las cuales no se puede calcular el valor óptimo a partir de la fuente. Entonces, en la gran mayoría de los casos, este parámetro no cambia nada en el documento de resultados. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Formato de guardado de datos. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Devolución de llamada para manejar cualquier advertencia generada. WarningHandler devuelve el elemento de enumeración ReturnAction especificando Continuar o Anular. Continuar es la acción predeterminada y la operación Guardar continúa; sin embargo, el usuario también puede devolver Anular, en cuyo caso la operación Guardar debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler) | Este controlador se puede usar para manejar eventos de progreso de conversión fe, se puede usar para mostrar la barra de progreso o mensajes sobre la cantidad actual de páginas procesadas, el ejemplo del código del controlador que muestra el progreso en la consola es: |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | A veces, los archivos PDF contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico juntas colocadas una cerca de otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo , causa que sus técnicas de suavizado de bordes de imagen (anti-aliasing) sean diferentes de Acrobat Reader. Si parece que el documento exportado contiene límites tan visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de de eso efecto no deseado ¡ATENCIÓN! Esta optimización de la calidad suele ralentizar esencialmente la conversión, así que, utilice esta opción solo cuando sea realmente necesario. |

### Ver también

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
