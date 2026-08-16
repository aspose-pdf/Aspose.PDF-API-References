---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Algunos documentos tienen un tamaño grande después de la conversión al formato PDF/A. Para reducir el tamaño de archivo de estos documentos es necesario definir una estrategia de eliminación de fuentes. Esta enumeración."
type: docs
weight: 3760
url: /es/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

Algunos documentos tienen un tamaño grande después de la conversión al formato PDF/A. Para reducir el tamaño de archivo de estos documentos es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que pueden usarse para optimizar el uso de fuentes. Cada estrategia de esta enumeración tiene sentido solo cuando la bandera {@code OptimizeFileSize} está establecida.

## Campos

| Campo | Descripción |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | Esta estrategia elimina todas las fuentes que tienen duplicados en el documento. Si el documento contiene un grupo de fuentes duplicadas, solo una fuente de ese grupo se incrusta en el documento. Todas las demás fuentes de ese grupo se eliminan del documento, y cada fuente eliminada se sustituye por el análogo ya incrustado. |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | Estrategia parece similar a {@code RemoveDuplicatedFonts} pero elimina no fuentes totalmente duplicadas sino fuentes que son similares entre sí y difieren solo por el parámetro "Widths". Este parámetro contiene un conjunto de anchuras para símbolos específicos de la fuente. Cada valor de anchura del conjunto "Widths" no es la anchura real del símbolo (glifo), la anchura real de este símbolo ya está definida en los datos binarios de la fuente. El valor de anchura del conjunto "Widths" representa la anchura visual para este símbolo, la anchura que el software visor de PDF debe aplicar al mostrar el símbolo en lugar de la anchura real definida en la fuente. Más precisamente, la especificación indica: los visores Acrobat 5.0 y posteriores utilizan las anchuras de glifos almacenadas en el diccionario de fuentes para sobrescribir las anchuras de los glifos en el propio programa de fuentes, lo que mejora la consistencia de la visualización e impresión del documento. Esta estrategia es más eficaz que {@code RemoveDuplicatedFonts} pero su uso en algunos casos podría dañar teóricamente la presentación visual del documento convertido. Este defecto es posible porque las anchuras declaradas de las fuentes pueden ser diferentes para el mismo símbolo y, en ese caso, la anchura de ese símbolo se cambiará a una nueva tras la sustitución de la fuente, cuando la fuente eliminada sea reemplazada en el documento por una ya incrustada. Y si la anchura visual del símbolo cambia, se mostrará incorrectamente y esta diferencia podría causar defectos visuales como superposición de texto u otros problemas. Sin embargo, el defecto visual descrito es un caso muy raro y esta estrategia reduce el tamaño del documento de forma más eficaz. |
| [SubsetFonts](#SubsetFonts) | Esta es la estrategia más eficaz para reducir el tamaño del documento. Toma conjuntos de fuentes totalmente incrustados y los recorta a solo los subconjuntos utilizados. Se recomienda usar esta estrategia en combinación con {@code RemoveDuplicatedFonts} o {@code RemoveSimilarFontsWithDifferentWidths} para obtener un efecto de compresión múltiple del tamaño del archivo. Utilizar las tres estrategias simultáneamente no tiene sentido y la estrategia {@code RemoveSimilarFontsWithDifferentWidths} no se usará en este caso. |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

Esta estrategia elimina todas las fuentes que tienen duplicados en el documento. Si el documento contiene un grupo de fuentes duplicadas, solo una fuente de ese grupo se incrusta en el documento. Todas las demás fuentes de ese grupo se eliminan del documento, y cada fuente eliminada se sustituye por el análogo ya incrustado.

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

Estrategia parece similar a {@code RemoveDuplicatedFonts} pero elimina no fuentes totalmente duplicadas sino fuentes que son similares entre sí y difieren solo por el parámetro "Widths". Este parámetro contiene un conjunto de anchuras para símbolos específicos de la fuente. Cada valor de anchura del conjunto "Widths" no es la anchura real del símbolo (glifo), la anchura real de este símbolo ya está definida en los datos binarios de la fuente. El valor de anchura del conjunto "Widths" representa la anchura visual para este símbolo, la anchura que el software visor de PDF debe aplicar al mostrar el símbolo en lugar de la anchura real definida en la fuente. Más precisamente, la especificación indica: los visores Acrobat 5.0 y posteriores utilizan las anchuras de glifos almacenadas en el diccionario de fuentes para sobrescribir las anchuras de los glifos en el propio programa de fuentes, lo que mejora la consistencia de la visualización e impresión del documento. Esta estrategia es más eficaz que {@code RemoveDuplicatedFonts} pero su uso en algunos casos podría dañar teóricamente la presentación visual del documento convertido. Este defecto es posible porque las anchuras declaradas de las fuentes pueden ser diferentes para el mismo símbolo y, en ese caso, la anchura de ese símbolo se cambiará a una nueva tras la sustitución de la fuente, cuando la fuente eliminada sea reemplazada en el documento por una ya incrustada. Y si la anchura visual del símbolo cambia, se mostrará incorrectamente y esta diferencia podría causar defectos visuales como superposición de texto u otros problemas. Sin embargo, el defecto visual descrito es un caso muy raro y esta estrategia reduce el tamaño del documento de forma más eficaz.

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

Esta es la estrategia más eficaz para reducir el tamaño del documento. Toma conjuntos de fuentes totalmente incrustados y los recorta a solo los subconjuntos utilizados. Se recomienda usar esta estrategia en combinación con {@code RemoveDuplicatedFonts} o {@code RemoveSimilarFontsWithDifferentWidths} para obtener un efecto de compresión múltiple del tamaño del archivo. Utilizar las tres estrategias simultáneamente no tiene sentido y la estrategia {@code RemoveSimilarFontsWithDifferentWidths} no se usará en este caso.
