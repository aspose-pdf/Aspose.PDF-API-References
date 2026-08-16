---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase representa opciones de guardado que utilizan una forma de conversión unificada (con un modelo interno de documento unificado)"
type: docs
weight: 5420
url: /es/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

Esta clase representa opciones de guardado que utilizan una forma de conversión unificada (con un modelo interno de documento unificado)

## Campos

| Campo | Descripción |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Procesa páginas en unos pocos hilos. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Representa un procesador interno de eventos de progreso que funciona durante la conversión y traduce los eventos de conversión de las etapas internas de conversión en eventos externos de progreso total. Además, la clase transmite eventos que permiten liberar recursos que ya no son necesarios. Esta clase interna maneja los eventos de progreso de PDF a APS y de APS a [Other format] para calcular el progreso total e informar al código del cliente sobre ese progreso total. Esta clase utiliza dos tipos de eventos: conversión de modelo ApsToExternal y eventos de conversión de PDF a APS para generar eventos de progreso total. La exportación tiene tres etapas: 1) PDF a APS 2) Reconocimiento de APS 3) Exportación de APS al formato de destino. El constructor permite ajustar cuántas páginas se convierten y cuál es la parte aproximada de esta u otra etapa en el progreso total. |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | Este atributo habilita la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. Valor: {@code true} el texto se extraerá en el documento resultante; de lo contrario, {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | A veces los PDF contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo idénticas en mosaico colocadas una junto a otra. En ese caso, los renderizadores de los formatos de destino (p. ej., MsWord para el formato DOCS) a veces generan límites visibles entre partes de las imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti‑aliasing) difieren de las de Acrobat Reader. Si parece que el documento exportado contiene esos límites visibles entre partes de la misma imagen de fondo, intente usar esta configuración para eliminar ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad normalmente ralentiza considerablemente la conversión, por lo que, por favor, utilice esta opción solo cuando sea realmente necesario. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> Este atributo activó la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. </p>Valor: {@code true} el texto se extraerá en el documento resultante; de lo contrario, {@code false}. <hr> Valor predeterminado == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Representa un procesador interno de eventos de progreso que funciona durante la conversión y traduce los eventos de conversión de las etapas internas de conversión en eventos externos de progreso total. Además, la clase transmite eventos que permiten liberar recursos que ya no son necesarios. Esta clase interna maneja los eventos de progreso de PDF a APS y de APS a [Other format] para calcular el progreso total e informar al código del cliente sobre ese progreso total. Esta clase utiliza dos tipos de eventos: conversión de modelo ApsToExternal y eventos de conversión de PDF a APS para generar eventos de progreso total. La exportación tiene tres etapas: 1) PDF a APS 2) Reconocimiento de APS 3) Exportación de APS al formato de destino. El constructor permite ajustar cuántas páginas se convierten y cuál es la parte aproximada de esta u otra etapa en el progreso total. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | A veces los PDF contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo idénticas en mosaico colocadas una junto a otra. En ese caso, los renderizadores de los formatos de destino (p. ej., MsWord para el formato DOCS) a veces generan límites visibles entre partes de las imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti‑aliasing) difieren de las de Acrobat Reader. Si parece que el documento exportado contiene esos límites visibles entre partes de la misma imagen de fondo, intente usar esta configuración para eliminar ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad normalmente ralentiza considerablemente la conversión, por lo que, por favor, utilice esta opción solo cuando sea realmente necesario. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Procesa páginas en unos pocos hilos.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Representa un procesador interno de eventos de progreso que funciona durante la conversión y traduce los eventos de conversión de las etapas internas de conversión en eventos externos de progreso total. Además, la clase transmite eventos que permiten liberar recursos que ya no son necesarios. Esta clase interna maneja los eventos de progreso de PDF a APS y de APS a [Other format] para calcular el progreso total e informar al código del cliente sobre ese progreso total. Esta clase utiliza dos tipos de eventos: conversión de modelo ApsToExternal y eventos de conversión de PDF a APS para generar eventos de progreso total. La exportación tiene tres etapas: 1) PDF a APS 2) Reconocimiento de APS 3) Exportación de APS al formato de destino. El constructor permite ajustar cuántas páginas se convierten y cuál es la parte aproximada de esta u otra etapa en el progreso total.

**Returns:**
Instancia de ConversionProgressEventsTranslator

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

Este atributo habilita la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. Valor: {@code true} el texto se extraerá en el documento resultante; de lo contrario, {@code false}.

**Returns:**
valor booleano

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

A veces los PDF contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo idénticas en mosaico colocadas una junto a otra. En ese caso, los renderizadores de los formatos de destino (p. ej., MsWord para el formato DOCS) a veces generan límites visibles entre partes de las imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti‑aliasing) difieren de las de Acrobat Reader. Si parece que el documento exportado contiene esos límites visibles entre partes de la misma imagen de fondo, intente usar esta configuración para eliminar ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad normalmente ralentiza considerablemente la conversión, por lo que, por favor, utilice esta opción solo cuando sea realmente necesario.

**Returns:**
valor booleano

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> Este atributo activó la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. </p>Valor: {@code true} el texto se extraerá en el documento resultante; de lo contrario, {@code false}. <hr> Valor predeterminado == false

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Representa un procesador interno de eventos de progreso que funciona durante la conversión y traduce los eventos de conversión de las etapas internas de conversión en eventos externos de progreso total. Además, la clase transmite eventos que permiten liberar recursos que ya no son necesarios. Esta clase interna maneja los eventos de progreso de PDF a APS y de APS a [Other format] para calcular el progreso total e informar al código del cliente sobre ese progreso total. Esta clase utiliza dos tipos de eventos: conversión de modelo ApsToExternal y eventos de conversión de PDF a APS para generar eventos de progreso total. La exportación tiene tres etapas: 1) PDF a APS 2) Reconocimiento de APS 3) Exportación de APS al formato de destino. El constructor permite ajustar cuántas páginas se convierten y cuál es la parte aproximada de esta u otra etapa en el progreso total.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

A veces los PDF contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo idénticas en mosaico colocadas una junto a otra. En ese caso, los renderizadores de los formatos de destino (p. ej., MsWord para el formato DOCS) a veces generan límites visibles entre partes de las imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti‑aliasing) difieren de las de Acrobat Reader. Si parece que el documento exportado contiene esos límites visibles entre partes de la misma imagen de fondo, intente usar esta configuración para eliminar ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad normalmente ralentiza considerablemente la conversión, por lo que, por favor, utilice esta opción solo cuando sea realmente necesario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valor booleano |
