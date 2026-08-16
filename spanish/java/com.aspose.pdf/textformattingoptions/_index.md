---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones de formato de texto"
type: docs
weight: 5080
url: /es/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Representa opciones de formato de texto

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Inicializa una nueva instancia del objeto {@code TextFormattingOptions} con modo de ajuste de línea indefinido. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Inicializa una nueva instancia del objeto {@code TextFormattingOptions} para el modo de ajuste de línea especificado. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | Obtiene o establece el valor de sangría de la primera línea. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Obtiene o establece el símbolo de guión que se usa en el proceso de hiphenación. </p><hr> Para eliminar el dibujo del guión (manteniendo el procedimiento de ajuste), establezca una cadena vacía string.Empty para HyphenSymbol. |
| [getLineSpacing](#getLineSpacing--) | Obtiene el modo de interlineado. El valor predeterminado es LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Obtiene o establece el valor de sangría de líneas subsiguientes. |
| [getWrapMode](#getWrapMode--) | Obtiene el modo de ajuste de texto. El valor predeterminado es WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Obtiene o establece el valor de sangría de la primera línea. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Obtiene o establece el símbolo de guión que se usa en el proceso de hiphenación. </p><hr> Para eliminar el dibujo del guión (manteniendo el procedimiento de ajuste), establezca una cadena vacía string.Empty para HyphenSymbol. |
| [setLineSpacing](#setLineSpacing-int-) | Establece el modo de interlineado. El valor predeterminado es LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Obtiene o establece el valor de sangría de líneas subsiguientes. |
| [setWrapMode](#setWrapMode-int-) | Establece el modo de ajuste de texto. El valor predeterminado es WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Inicializa una nueva instancia del objeto {@code TextFormattingOptions} con modo de ajuste de línea indefinido.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Inicializa una nueva instancia del objeto {@code TextFormattingOptions} para el modo de ajuste de línea especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| wrapMode |  | Modo de ajuste de texto. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Obtiene o establece el valor de sangría de la primera línea.

**Returns:**
valor flotante

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Obtiene o establece el símbolo de guión que se usa en el proceso de hiphenación. </p><hr> Para eliminar el dibujo del guión (manteniendo el procedimiento de ajuste), establezca una cadena vacía string.Empty para HyphenSymbol.

**Returns:**
valor String

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Obtiene el modo de interlineado. El valor predeterminado es LineSpacingMode.FontSize

**Returns:**
valor int @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Obtiene o establece el valor de sangría de líneas subsiguientes.

**Returns:**
valor flotante

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Obtiene el modo de ajuste de texto. El valor predeterminado es WordWrapMode.NoWrap

**Returns:**
valor WordWrapMode @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Obtiene o establece el valor de sangría de la primera línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Obtiene o establece el símbolo de guión que se usa en el proceso de hiphenación. </p><hr> Para eliminar el dibujo del guión (manteniendo el procedimiento de ajuste), establezca una cadena vacía string.Empty para HyphenSymbol.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Establece el modo de interlineado. El valor predeterminado es LineSpacingMode.FontSize

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Obtiene o establece el valor de sangría de líneas subsiguientes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Establece el modo de ajuste de texto. El valor predeterminado es WordWrapMode.NoWrap

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor WordWrapMode @see WordWrapMode |
