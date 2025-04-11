---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum PdfFormatConversionOptionsRemoveFontsStrategy de Aspose.Pdf. Algunos documentos tienen un tamaño grande después de la conversión al formato PDF/A. Para reducir el tamaño del archivo de estos documentos, es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que se pueden utilizar para optimizar el uso de fuentes. Cada estrategia de esta enumeración tiene sentido solo cuando la bandera OptimizeFileSize está activada.
type: docs
weight: 8400
url: /es/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## Enumeración PdfFormatConversionOptions.RemoveFontsStrategy

Algunos documentos tienen un tamaño grande después de la conversión al formato PDF/A. Para reducir el tamaño del archivo de estos documentos, es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que se pueden utilizar para optimizar el uso de fuentes. Cada estrategia de esta enumeración tiene sentido solo cuando la bandera [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) está activada.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Esta estrategia elimina todas las fuentes que tienen duplicados en el documento. Si el documento contiene un grupo de fuentes duplicadas, solo una fuente de este grupo se incrusta en el documento. Todas las demás fuentes de este grupo se eliminan del documento, cada fuente eliminada se sustituye por el análogo ya incrustado. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Esta estrategia es similar a RemoveDuplicatedFonts, pero elimina no solo fuentes completamente duplicadas, sino fuentes que son similares entre sí y difieren solo por el parámetro "Widths". Este parámetro contiene un conjunto de algunos anchos para símbolos específicos de la fuente. Cada valor de ancho de este conjunto de "Widths" no es el ancho real del símbolo (glifo), el ancho real para este símbolo ya está definido en los datos binarios de la fuente. El valor de ancho del conjunto de "Widths" significa el ancho visual para este símbolo: el ancho que el software de visualización de PDF debe establecer al mostrar el símbolo en lugar del ancho real definido en la fuente. Más precisamente, la especificación dice: los visores Acrobat 5.0 y posteriores utilizan los anchos de glifos almacenados en el diccionario de fuentes para anular los anchos de los glifos en el programa de la fuente, lo que mejora la consistencia de la visualización y la impresión del documento. Esta estrategia es más efectiva que RemoveDuplicatedFonts, pero el uso de esta estrategia en algunos casos podría teóricamente dañar la presentación visual del documento convertido. Este defecto es posible debido a que los anchos declarados de las fuentes podrían ser diferentes para el mismo símbolo y, en este caso, el ancho de este símbolo se cambiará a uno nuevo después de la sustitución de la fuente: cuando la fuente eliminada sea reemplazada en el documento por una ya incrustada. Y si el ancho visual del símbolo se cambia, se mostrará incorrectamente y esta distinción podría causar defectos visuales como superposición de texto u otros problemas. Pero el defecto visual descrito es un caso muy raro y esta estrategia reduce el tamaño del documento de manera más efectiva. |
| SubsetFonts | `2` | Esta es la estrategia más efectiva para reducir el tamaño del documento. Toma conjuntos de fuentes completamente incrustadas y los recorta solo a los subconjuntos utilizados. Se recomienda utilizar esta estrategia en combinación con RemoveDuplicatedFonts o RemoveSimilarFontsWithDifferentWidths para obtener un efecto de compresión múltiple para el tamaño del archivo. Usar las tres estrategias simultáneamente no tiene sentido y la estrategia RemoveSimilarFontsWithDifferentWidths no se utilizará en este caso. |

### Ver También

* clase [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)