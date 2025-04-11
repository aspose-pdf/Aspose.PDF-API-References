---
title: UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages
second_title: Aspose.PDF for .NET API Reference
description: Campo UnifiedSaveOptions. A veces, los PDFs contienen imágenes de fondo de páginas o celdas de tabla construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una cerca de la otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de las imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (antialiasing) son diferentes de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza esencialmente la conversión, así que, por favor, use esta opción solo cuando sea realmente necesario.
type: docs
weight: 40
url: /es/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

A veces, los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una cerca de la otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de las imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (antialiasing) son diferentes de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza esencialmente la conversión, así que, por favor, use esta opción solo cuando sea realmente necesario.

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### See Also

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)