---
title: "Enumeración Aspose::Pdf::PdfFormatConversionOptions::RemoveFontsStrategy"
linktitle: "RemoveFontsStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PdfFormatConversionOptions::RemoveFontsStrategy enum. Algunos documentos tienen un tamaño grande después de la conversión al formato PDF/A. Para reducir el tamaño del archivo de estos documentos es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que pueden usarse para optimizar el uso de fuentes. Cada estrategia de esta enumeración tiene sentido solo cuando la bandera OptimizeFileSize está establecida en C++."
type: docs
weight: 4300
url: /es/cpp/aspose.pdf/pdfformatconversionoptions/removefontsstrategy/
---
## RemoveFontsStrategy enum


Algunos documentos tienen un tamaño grande después de la conversión al formato PDF/A. Para reducir el tamaño de archivo de estos documentos es necesario definir una estrategia de eliminación de fuentes. Esta enumeración declara estrategias que pueden usarse para optimizar el uso de fuentes. Cada estrategia de esta enumeración solo tiene sentido cuando la bandera [OptimizeFileSize](../) está activada.

```cpp
enum class RemoveFontsStrategy : uint8_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RemoveDuplicatedFonts | 4 | Esta estrategia elimina todas las fuentes que tienen duplicados en el documento. Si el documento contiene un grupo de fuentes duplicadas, solo una fuente de ese grupo se incrusta en el documento. Todas las demás fuentes de ese grupo se eliminan del documento, cada fuente eliminada se sustituye por el análogo ya incrustado. |
| RemoveSimilarFontsWithDifferentWidths | 1 | Esta estrategia se parece a [RemoveDuplicatedFonts](./) pero elimina no fuentes totalmente duplicadas sino fuentes que son similares entre sí y difieren solo por el parámetro "Widths". Este parámetro contiene un conjunto de anchuras para símbolos específicos de la fuente. Cada valor de anchura de este conjunto "Widths" no es la anchura real del símbolo (glifo), la anchura real de este símbolo ya está definida en los datos binarios de la fuente. El valor de anchura del conjunto "Widths" representa la anchura visual de este símbolo, la anchura que el visor de PDF debe usar al mostrar el símbolo en lugar de la anchura real definida en la fuente. Más precisamente, la especificación indica: los visores Acrobat 5.0 y posteriores usan las anchuras de glifos almacenadas en el diccionario de la fuente para sobrescribir las anchuras de los glifos en el propio programa de la fuente, lo que mejora la consistencia de la visualización e impresión del documento. Esta estrategia es más eficaz que [RemoveDuplicatedFonts](./) pero su uso en algunos casos podría dañar teóricamente la presentación visual del documento convertido. Este defecto es posible porque las anchuras declaradas de las fuentes podrían ser diferentes para el mismo símbolo y, en ese caso, la anchura de ese símbolo se cambiará a una nueva después de la sustitución de la fuente, cuando la fuente eliminada sea reemplazada en el documento por una ya incrustada. Y si la anchura visual del símbolo cambia, se mostrará incorrectamente y esta diferencia podría causar defectos visuales como superposición de texto u otros problemas. Sin embargo, el defecto visual descrito es un caso muy raro y esta estrategia reduce el tamaño del documento de manera más eficaz. |
| SubsetFonts | 2 | Esta es la estrategia más eficaz para reducir el tamaño del documento. Toma conjuntos de fuentes totalmente incrustadas y los recorta a solo los subconjuntos utilizados. Se recomienda usar esta estrategia en combinación con [RemoveDuplicatedFonts](./) o [RemoveSimilarFontsWithDifferentWidths](./) para obtener un efecto de compresión múltiple del tamaño del archivo. El uso simultáneo de las tres estrategias no tiene sentido y la estrategia [RemoveSimilarFontsWithDifferentWidths](./) no se utilizará en este caso. |

## Ver también

* Class [PdfFormatConversionOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
