---
title: SvgSaveOptions
second_title: Referencia de API de Aspose.PDF para .NET
description: Guardar opciones para exportar a formato SVG
type: docs
weight: 6450
url: /es/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

Guardar opciones para exportar a formato SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Obtiene o establece un valor booleano que indica que el objeto de respuesta se cerrará después de que el documento se guarde en la respuesta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Este atributo activó la funcionalidad para extraer imágenes o texto para documentos PDF con subcapa OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Formato de guardado de datos. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Devolución de llamada para manejar cualquier advertencia generada. WarningHandler devuelve el elemento de enumeración ReturnAction especificando Continuar o Anular. Continuar es la acción predeterminada y la operación Guardar continúa; sin embargo, el usuario también puede devolver Anular, en cuyo caso la operación Guardar debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive) | Especifica si la salida se creará como un archivo zip. Consulte el comentario sobre las opciones 'TreatTargetFileNameAsDirectory' para ver las reglas de denominación de archivos svg de páginas para documentos de origen de varias páginas, que también se aplican al conjunto comprimido de archivos de salida. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving) | Este campo puede contener una estrategia de guardado que se debe usar (si está presente) durante la conversión para el manejo personalizado de imágenes externas referenciadas creadas archivos (como BMP o JPEG incrustados) incrustados en SVG guardado. Esa estrategia debe procesar recursos y devolver una cadena que representa el URI deseable del recurso guardado en el SVG generado. Si el procesamiento de este o aquel archivo por algún motivo debe realizarse mediante el propio código del convertidor, no en el código personalizado, establezca en el indicador de código personalizado 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo' Le indica al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no hubiera ningún código personalizado externo . |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels) | Especifica si escalar el documento de salida de puntos tipográficos a píxeles. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory) | Esta opción define si se creará el directorio de destino (si aún no existe) con el mismo nombre que el archivo de salida solicitado en lugar del archivo de salida solicitado. . Si no, los archivos de salida de las páginas que no sean la primera se crearán exactamente en el directorio solicitado como archivo de salida principal, pero contendrán en el nombre de archivo el sufijo _[2...n], que se define por el número de página, fe si Usted define el archivo de salida "C:\AsposeTests\output.svg" y la salida contendrá varios archivos svg de páginas, luego los archivos de páginas también se crearán en el directorio "C:\AsposeTests\" y tendrán nombres 'salida. svg', 'salida_2.svg', 'salida_3.svg' etc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | A veces, los archivos PDF contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico juntas colocadas una cerca de otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo , causa que sus técnicas de suavizado de bordes de imagen (anti-aliasing) sean diferentes de Acrobat Reader. Si parece que el documento exportado contiene límites tan visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de de eso efecto no deseado ¡ATENCIÓN! Esta optimización de la calidad suele ralentizar esencialmente la conversión, así que, utilice esta opción solo cuando sea realmente necesario. |

### Ver también

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
