---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones de reemplazo de texto"
type: docs
weight: 5250
url: /es/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Representa opciones de reemplazo de texto

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Inicializa una nueva instancia del objeto {@code TextReplaceOptions} para el ajuste predeterminado y el alcance : ReplaceAdjustment.None y Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Inicializa una nueva instancia del objeto {@code TextReplaceOptions} para la acción especificada después de reemplazar. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Inicializa una nueva instancia del objeto {@code TextReplaceOptions} para el ajuste predeterminado y el alcance : ReplaceAdjustment.None y Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Inicializa una nueva instancia del objeto {@code TextReplaceOptions} para el ajuste predeterminado y el alcance : ReplaceAdjustment.None y Scope.REPLACE_FIRST |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Obtiene o establece el valor del interlineado que se usa si el ajuste de reemplazo se fuerza a crear una nueva línea de texto. El valor esperado es un multiplicador del tamaño de fuente del texto reemplazado. El valor predeterminado es 1.2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | Obtiene o establece la política para ajustar el tamaño de fuente para que quepa dentro de los límites definidos por {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}). |
| [getLeftAdjustment](#getLeftAdjustment--) | Obtiene el ajuste de posición izquierda para el texto reemplazado al usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | Obtiene o establece el rectángulo para ajustar el texto después del reemplazo. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Obtiene una acción que se realizará después de reemplazar el fragmento de texto a una versión más corta. |
| [getReplaceScope](#getReplaceScope--) | Obtiene un alcance donde se aplica la operación de reemplazo de texto |
| [getRightAdjustment](#getRightAdjustment--) | Establece u obtiene el ajuste de posición derecha para el texto reemplazado al usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Obtiene o establece un valor que indica si se deben ignorar los párrafos distintos al ajustar el texto en la página después del reemplazo de texto. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Obtiene o establece el valor del interlineado que se usa si el ajuste de reemplazo se fuerza a crear una nueva línea de texto. El valor esperado es un multiplicador del tamaño de fuente del texto reemplazado. El valor predeterminado es 1.2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | Obtiene o establece la política para ajustar el tamaño de fuente para que quepa dentro de los límites definidos por TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Obtiene o establece un valor que indica si se deben ignorar los párrafos distintos al ajustar el texto en la página después del reemplazo de texto. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | Establece u obtiene el ajuste de posición izquierda para el texto reemplazado al usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Obtiene o establece el rectángulo para ajustar el texto después del reemplazo. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Establece una acción que se realizará después de reemplazar el fragmento de texto a una versión más corta. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Establece un alcance donde se aplica la operación de reemplazo de texto |
| [setRightAdjustment](#setRightAdjustment-double-) | Establece el ajuste de posición derecha para el texto reemplazado al usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Inicializa una nueva instancia del objeto {@code TextReplaceOptions} para el ajuste predeterminado y el alcance : ReplaceAdjustment.None y Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Inicializa una nueva instancia del objeto {@code TextReplaceOptions} para la acción especificada después de reemplazar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ajuste |  | Objeto ReplaceAdjustment. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Inicializa una nueva instancia del objeto {@code TextReplaceOptions} para el ajuste predeterminado y el alcance : ReplaceAdjustment.None y Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Inicializa una nueva instancia del objeto {@code TextReplaceOptions} para el ajuste predeterminado y el alcance : ReplaceAdjustment.None y Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Obtiene o establece el valor del interlineado que se usa si el ajuste de reemplazo se fuerza a crear una nueva línea de texto. El valor esperado es un multiplicador del tamaño de fuente del texto reemplazado. El valor predeterminado es 1.2.

**Returns:**
valor double

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

Obtiene o establece la política para ajustar el tamaño de fuente para que quepa dentro de los límites definidos por {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}).

**Returns:**
Elemento FontSizeAdjustment

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

Obtiene el ajuste de posición izquierda para el texto reemplazado al usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
valor double

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Obtiene o establece el rectángulo para ajustar el texto después del reemplazo.

**Returns:**
Instancia de Rectangle

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Obtiene una acción que se realizará después de reemplazar el fragmento de texto a una versión más corta.

**Returns:**
Elemento ReplaceAdjustment @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Obtiene un alcance donde se aplica la operación de reemplazo de texto

**Returns:**
valor int @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

Establece u obtiene el ajuste de posición derecha para el texto reemplazado al usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
valor double

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Obtiene o establece un valor que indica si se deben ignorar los párrafos distintos al ajustar el texto en la página después del reemplazo de texto.

**Returns:**
valor boolean

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Obtiene o establece el valor del interlineado que se usa si el ajuste de reemplazo se fuerza a crear una nueva línea de texto. El valor esperado es un multiplicador del tamaño de fuente del texto reemplazado. El valor predeterminado es 1.2.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
Obtiene o establece la política para ajustar el tamaño de fuente para que quepa dentro de los límites definidos por TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Obtiene o establece un valor que indica si se deben ignorar los párrafos distintos al ajustar el texto en la página después del reemplazo de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

Establece u obtiene el ajuste de posición izquierda para el texto reemplazado al usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Obtiene o establece el rectángulo para ajustar el texto después del reemplazo.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Establece una acción que se realizará después de reemplazar el fragmento de texto a una versión más corta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ReplaceAdjustment @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Establece un alcance donde se aplica la operación de reemplazo de texto

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

Establece el ajuste de posición derecha para el texto reemplazado al usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |
