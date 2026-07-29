---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase de opciones para extraer gráficos vectoriales de la página del documento pdf."
type: docs
weight: 30
url: /es/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Representa una clase de opciones para extraer gráficos vectoriales de la página del documento pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Crea una instancia de la clase SvgExtractionOptions. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Obtiene y establece la opción para agrupar automáticamente subtrazos en imágenes. Esta opción excluye la opción {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Obtiene y establece la opción para extraer cada subtrazo de un documento PDF a imágenes SVG separadas. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Obtiene y establece el rectángulo delimitador que define el área de extracción para la extracción de SVG. |
| [getGroupStrength](#getGroupStrength--) | Obtiene y establece una opción: la fuerza de agrupamiento de subtrazos en imágenes. Permite configurar el grado de agrupamiento de los subtrazos. El rango de valores es de 0 a 1. Un valor de 0 corresponde a que la opción {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) esté habilitada. Un valor de 1 creará una única imagen para todos los trazos vectoriales en la página. La opción tiene efecto cuando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) es false. El valor predeterminado es {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Obtiene o establece el ancho de trazo mínimo que se utilizará en el SVG resultante. Si el PDF usa un ancho de trazo más delgado, será reemplazado por este ancho. El valor predeterminado es 0.5. El valor se expresa en unidades de espacio de usuario transformado de la página PDF convertida. Por defecto, 1 unidad de espacio de usuario equivale a 1/72 de pulgada (0,35 mm), pero esto puede ser sobrescrito por el documento PDF. Las transformaciones pueden afectar el ancho mínimo real en el SVG generado. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Obtiene y establece una opción para definir estrictamente si los subtrazos están dentro del rectángulo especificado en {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Si se establece en false, los subtrazos que no estén completamente incluidos en {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) serán extraídos. El valor predeterminado es {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Obtiene y establece una bandera que determina si los XFrom encontrados en las páginas deben desempaquetarse o no. Los elementos XFrom pueden terminar en diferentes archivos SVG. Sólo los XForms que son renderizados por sentencias Do del contenido de la página se desempaquetan. Los XForms anidados no se desempaquetan. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Obtiene y establece la opción para desempaquetar sólo el XForm correspondiente al predicado especificado. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Obtiene y establece la opción para agrupar automáticamente subtrazos en imágenes. Esta opción excluye la opción {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Obtiene y establece la opción para extraer cada subtrazo de un documento PDF a imágenes SVG separadas. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Obtiene y establece el rectángulo delimitador que define el área de extracción para la extracción de SVG. |
| [setGroupStrength](#setGroupStrength-double-) | Obtiene y establece una opción: la fuerza de agrupamiento de subtrazos en imágenes. Permite configurar el grado de agrupamiento de los subtrazos. El rango de valores es de 0 a 1. Un valor de 0 corresponde a que la opción {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) esté habilitada. Un valor de 1 creará una única imagen para todos los trazos vectoriales en la página. La opción tiene efecto cuando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) es false. El valor predeterminado es {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Obtiene o establece el ancho de trazo mínimo que se utilizará en el SVG resultante. Si el PDF usa un ancho de trazo más delgado, será reemplazado por este ancho. El valor predeterminado es 0.5. El valor se expresa en unidades de espacio de usuario transformado de la página PDF convertida. Por defecto, 1 unidad de espacio de usuario equivale a 1/72 de pulgada (0,35 mm), pero esto puede ser sobrescrito por el documento PDF. Las transformaciones pueden afectar el ancho mínimo real en el SVG generado. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Obtiene y establece una opción para definir estrictamente si los subtrazos están dentro del rectángulo especificado en {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Si se establece en false, los subtrazos que no estén completamente incluidos en {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) serán extraídos. El valor predeterminado es {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Obtiene y establece una bandera que determina si los XFrom encontrados en las páginas deben desempaquetarse o no. Los elementos XFrom pueden terminar en diferentes archivos SVG. Sólo los XForms que son renderizados por sentencias Do del contenido de la página se desempaquetan. Los XForms anidados no se desempaquetan. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Obtiene y establece la opción para desempaquetar sólo el XForm correspondiente al predicado especificado. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Crea una instancia de la clase SvgExtractionOptions.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Obtiene y establece la opción para agrupar automáticamente subtrazos en imágenes. Esta opción excluye la opción {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Returns:**
valor booleano

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Obtiene y establece la opción para extraer cada subtrazo de un documento PDF a imágenes SVG separadas.

**Returns:**
valor booleano

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Obtiene y establece el rectángulo delimitador que define el área de extracción para la extracción de SVG.

**Returns:**
Instancia de Rectangle

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Obtiene y establece una opción: la fuerza de agrupamiento de subtrazos en imágenes. Permite configurar el grado de agrupamiento de los subtrazos. El rango de valores es de 0 a 1. Un valor de 0 corresponde a que la opción {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) esté habilitada. Un valor de 1 creará una única imagen para todos los trazos vectoriales en la página. La opción tiene efecto cuando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) es false. El valor predeterminado es {@code 0.8}.

**Returns:**
valor double

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Obtiene o establece el ancho de trazo mínimo que se utilizará en el SVG resultante. Si el PDF usa un ancho de trazo más delgado, será reemplazado por este ancho. El valor predeterminado es 0.5. El valor se expresa en unidades de espacio de usuario transformado de la página PDF convertida. Por defecto, 1 unidad de espacio de usuario equivale a 1/72 de pulgada (0,35 mm), pero esto puede ser sobrescrito por el documento PDF. Las transformaciones pueden afectar el ancho mínimo real en el SVG generado.

**Returns:**
valor double

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Obtiene y establece una opción para definir estrictamente si los subtrazos están dentro del rectángulo especificado en {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Si se establece en false, los subtrazos que no estén completamente incluidos en {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) serán extraídos. El valor predeterminado es {@code True}.

**Returns:**
valor booleano

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Obtiene y establece una bandera que determina si los XFrom encontrados en las páginas deben desempaquetarse o no. Los elementos XFrom pueden terminar en diferentes archivos SVG. Sólo los XForms que son renderizados por sentencias Do del contenido de la página se desempaquetan. Los XForms anidados no se desempaquetan.

**Returns:**
valor booleano

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Obtiene y establece la opción para desempaquetar sólo el XForm correspondiente al predicado especificado.

**Returns:**
Instancia interna de Predicate de la instancia XFormPlacement

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Obtiene y establece la opción para agrupar automáticamente subtrazos en imágenes. Esta opción excluye la opción {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Obtiene y establece la opción para extraer cada subtrazo de un documento PDF a imágenes SVG separadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Obtiene y establece el rectángulo delimitador que define el área de extracción para la extracción de SVG.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Obtiene y establece una opción: la fuerza de agrupamiento de subtrazos en imágenes. Permite configurar el grado de agrupamiento de los subtrazos. El rango de valores es de 0 a 1. Un valor de 0 corresponde a que la opción {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) esté habilitada. Un valor de 1 creará una única imagen para todos los trazos vectoriales en la página. La opción tiene efecto cuando {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) es false. El valor predeterminado es {@code 0.8}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Obtiene o establece el ancho de trazo mínimo que se utilizará en el SVG resultante. Si el PDF usa un ancho de trazo más delgado, será reemplazado por este ancho. El valor predeterminado es 0.5. El valor se expresa en unidades de espacio de usuario transformado de la página PDF convertida. Por defecto, 1 unidad de espacio de usuario equivale a 1/72 de pulgada (0,35 mm), pero esto puede ser sobrescrito por el documento PDF. Las transformaciones pueden afectar el ancho mínimo real en el SVG generado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Obtiene y establece una opción para definir estrictamente si los subtrazos están dentro del rectángulo especificado en {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Si se establece en false, los subtrazos que no estén completamente incluidos en {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) serán extraídos. El valor predeterminado es {@code True}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Obtiene y establece una bandera que determina si los XFrom encontrados en las páginas deben desempaquetarse o no. Los elementos XFrom pueden terminar en diferentes archivos SVG. Sólo los XForms que son renderizados por sentencias Do del contenido de la página se desempaquetan. Los XForms anidados no se desempaquetan.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Obtiene y establece la opción para desempaquetar sólo el XForm correspondiente al predicado especificado.
