---
title: PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Referencia de API de Aspose.PDF para .NET
description: Algunos documentos tienen un tamaño grande después de la conversión a formato PDF/A. Para reducir el tamaño de archivo de estos documentos es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que se pueden usar para optimizar el uso de fuentes. Cada estrategia de esta enumeración tiene sentido solo cuando marcaOptimizeFileSize./pdfformatconversionoptions/optimizefilesize está configurado.
type: docs
weight: 6050
url: /es/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

Algunos documentos tienen un tamaño grande después de la conversión a formato PDF/A. Para reducir el tamaño de archivo de estos documentos es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que se pueden usar para optimizar el uso de fuentes. Cada estrategia de esta enumeración tiene sentido solo cuando marca[`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize) está configurado.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Esta estrategia elimina todas las fuentes que tienen duplicados en el documento. Si el documento contiene un grupo de fuentes duplicadas, solo se incrusta una fuente de este grupo en el documento. Todas las demás fuentes de este grupo se eliminan del documento, cada fuente eliminada se sustituye con el análogo ya incrustado. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Esta estrategia pareceRemoveDuplicatedFontspero no elimina completamente las fuentes duplicadas sino las fuentes que son similares entre sí y difieren solo por el parámetro "Ancho". Este parámetro contiene un conjunto de algunos anchos para símbolos de fuente específicos. Cada valor de ancho de este conjunto de "Anchos" no es el ancho real del símbolo (glifo), el ancho real para este símbolo ya está definido en los datos binarios de la fuente. El valor de ancho del conjunto "Anchos" significa el ancho visual para este símbolo : el ancho que el software de visualización de PDF debe establecer al mostrar el símbolo en lugar del ancho real definido en la fuente. La especificación más precisa dice: Acrobat 5.0 y los lectores posteriores usan los anchos de glifo almacenados en el diccionario de fuentes para anular los anchos de los glifos en el programa de fuentes en sí, lo que mejora la consistencia de la visualización y la impresión del documento. Esta estrategia es más eficaz queRemoveDuplicatedFontspero el uso de esta estrategia en algunos casos teóricamente podría dañar la presentación visual del documento convertido. Este defecto es posible debido a que los anchos declarados de las fuentes pueden ser diferentes para el mismo símbolo y, en este caso, el ancho de este símbolo se cambiará por uno nuevo después de la sustitución de la fuente ; cuando se elimine, la fuente se reemplazará en el documento con la ya incrustada one. Y si se cambiará el ancho visual del símbolo, se mostrará incorrectamente y esta distinción podría causar defectos visuales como superposición de texto u otros problemas. Pero el defecto visual descrito es un caso muy raro y esta estrategia reduce el tamaño del documento de manera más efectiva. |
| SubsetFonts | `2` | Esta es la estrategia más efectiva para reducir el tamaño del documento. Toma conjuntos de fuentes completamente incrustados y los recorta solo a los subconjuntos utilizados. Se recomienda utilizar esta estrategia en combinación conRemoveDuplicatedFonts oRemoveSimilarFontsWithDifferentWidths to obtiene un efecto de compresión múltiple para el tamaño del archivo. Usar las tres estrategias simultáneamente no tiene sentido y estrategiaRemoveSimilarFontsWithDifferentWidths no se usará en este caso. |

### Ver también

* class [PdfFormatConversionOptions](../pdfformatconversionoptions)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->