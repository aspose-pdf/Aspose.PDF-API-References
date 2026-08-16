---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un fragmento html."
type: docs
weight: 1950
url: /es/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

Representa un fragmento html.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | Inicializa una nueva instancia de la clase HtmlFragment. |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clona fragmento html. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Obtiene HtmlLoadOptions que se utilizarán para cargar (y renderizar) HTML en esta instancia de la clase. Por favor, úselo cuando sea necesario usar una configuración específica para la importación de HTML para esta u otra instancia (p. ej., cuando esta u otra instancia deba usar un BasePath específico para el HTML importado o deba usar un cargador específico de recursos externos). Si el parámetro es predeterminado (null), se utilizarán las opciones estándar de carga de HTML. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo del HtmlFragment |
| [getTextState](#getTextState--) | Obtiene o establece la fuente |
| [isBreakWords](#isBreakWords--) | Obtiene o establece la separación de palabras |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Obtiene o establece si el párrafo tiene margen predeterminado; de lo contrario, el margen es 0 |
| [setBreakWords](#setBreakWords-boolean-) | Obtiene o establece la separación de palabras |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Establece HtmlLoadOptions que se utilizarán para cargar (y renderizar) HTML en esta instancia de la clase. Por favor, úselo cuando sea necesario usar una configuración específica para la importación de HTML para esta u otra instancia (p. ej., cuando esta u otra instancia deba usar un BasePath específico para el HTML importado o deba usar un cargador específico de recursos externos). Si el parámetro es predeterminado (null), se utilizarán las opciones estándar de carga de HTML. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Obtiene o establece si el párrafo tiene margen predeterminado; de lo contrario, el margen es 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Obtiene o establece la fuente |

### HtmlFragment {#HtmlFragment-java.lang.String-}
Inicializa una nueva instancia de la clase HtmlFragment.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona fragmento html.

**Returns:**
Objeto de fragmento html clonado.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Obtiene HtmlLoadOptions que se utilizarán para cargar (y renderizar) HTML en esta instancia de la clase. Por favor, úselo cuando sea necesario usar una configuración específica para la importación de HTML para esta u otra instancia (p. ej., cuando esta u otra instancia deba usar un BasePath específico para el HTML importado o deba usar un cargador específico de recursos externos). Si el parámetro es predeterminado (null), se utilizarán las opciones estándar de carga de HTML.

**Returns:**
Valor de HtmlLoadOptions

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Obtiene el rectángulo del HtmlFragment

**Returns:**
Instancia de java.awt.geom.Rectangle2D.Float

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Obtiene o establece la fuente

**Returns:**
Objeto TextState

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Obtiene o establece la separación de palabras

**Returns:**
valor booleano

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Obtiene o establece si el párrafo tiene margen predeterminado; de lo contrario, el margen es 0

**Returns:**
valor booleano

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Obtiene o establece la separación de palabras

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Establece HtmlLoadOptions que se utilizarán para cargar (y renderizar) HTML en esta instancia de la clase. Por favor, úselo cuando sea necesario usar una configuración específica para la importación de HTML para esta u otra instancia (p. ej., cuando esta u otra instancia deba usar un BasePath específico para el HTML importado o deba usar un cargador específico de recursos externos). Si el parámetro es predeterminado (null), se utilizarán las opciones estándar de carga de HTML.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Obtiene o establece si el párrafo tiene margen predeterminado; de lo contrario, el margen es 0

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Obtiene o establece la fuente
