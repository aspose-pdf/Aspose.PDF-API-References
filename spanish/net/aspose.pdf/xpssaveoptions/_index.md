---
title: XpsSaveOptions
second_title: Referencia de API de Aspose.PDF para .NET
description: Guardar opciones para exportar a formato Xps
type: docs
weight: 7570
url: /es/net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class

Guardar opciones para exportar a formato Xps

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize) { get; set; } | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Obtiene o establece un valor booleano que indica que el objeto de respuesta se cerrará después de que el documento se guarde en la respuesta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Este atributo activó la funcionalidad para extraer imágenes o texto para documentos PDF con subcapa OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Formato de guardado de datos. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts) { get; set; } | Indica si se debe conservar el texto transparente (OCR). |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Devolución de llamada para manejar cualquier advertencia generada. WarningHandler devuelve el elemento de enumeración ReturnAction especificando Continuar o Anular. Continuar es la acción predeterminada y la operación Guardar continúa; sin embargo, el usuario también puede devolver Anular, en cuyo caso la operación Guardar debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | A veces, los archivos PDF contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico juntas colocadas una cerca de otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo , causa que sus técnicas de suavizado de bordes de imagen (anti-aliasing) sean diferentes de Acrobat Reader. Si parece que el documento exportado contiene límites tan visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de de eso efecto no deseado ¡ATENCIÓN! Esta optimización de la calidad suele ralentizar esencialmente la conversión, así que, utilice esta opción solo cuando sea realmente necesario. |

### Ver también

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->