---
title: Class PsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PsSaveOptions. Opciones de guardado para exportar a formato PS PostScript o EPS
type: docs
weight: 9740
url: /es/net/aspose.pdf/pssaveoptions/
---
## Clase PsSaveOptions

Opciones de guardado para exportar a formato PS (PostScript) o EPS.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | Constructor. |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | Constructor. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtiene o establece un valor booleano que indica si se almacenarán en caché los glifos de fuente mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de pdf a otros formatos, pero aumenta el consumo de memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtiene o establece un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | Obtiene/establece un indicador que indica si las fuentes deben estar incrustadas en el documento PS resultante. |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | Obtiene/establece el tipo en el que las fuentes deben estar incrustadas en el documento PS resultante. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo activa la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de datos guardados. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de guardado continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de guardado debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Procesar páginas en varios hilos. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A veces, los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una cerca de la otra. En tal caso, los renderizadores de los formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti-aliasing) son diferentes de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión, así que, por favor, use esta opción solo cuando sea realmente necesario. |

### Véase También

* clase [UnifiedSaveOptions](../unifiedsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)