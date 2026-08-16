---
title: "StructureTextState"
linktitle: "StructureTextState"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la configuración del estado de texto para Elementos de Estructura de Texto y TaggedContent (ITextElement, ITaggedContent)"
type: docs
weight: 120
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState

```
public class StructureTextState extends Object
```

Representa la configuración del estado de texto para Elementos de Estructura de Texto y TaggedContent (ITextElement, ITaggedContent)

## Constructores

| Constructor | Descripción |
| --- | --- |
| [StructureTextState](#StructureTextState--) | Constructor predeterminado |

## Métodos

| Método | Descripción |
| --- | --- |
| [createTextState](#createTextState--) | Crear estado de texto |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene o establece el color de fondo del texto. Puede ser nulo. Use null para heredar la propiedad {@code BackgroundColor} del elemento estructural padre. |
| [getCharacterSpacing](#getCharacterSpacing--) | Obtiene o establece el espaciado de caracteres del texto. Puede ser nulo. Use null para heredar la propiedad {@code CharacterSpacing} del elemento estructural padre. |
| [getFont](#getFont--) | Obtiene o establece la fuente del texto. Puede ser nulo. Use null para heredar la propiedad {@code Font} del elemento estructural padre. |
| [getFontSize](#getFontSize--) | Obtiene o establece el tamaño de fuente del texto. Puede ser nulo. Use null para heredar la propiedad {@code FontSize} del elemento estructural padre. |
| [getFontStyle](#getFontStyle--) | Obtiene o establece el estilo de fuente del texto. Puede ser nulo. Use null para heredar la propiedad {@code FontStyle} del elemento estructural padre. |
| [getForegroundColor](#getForegroundColor--) | Obtiene o establece el color de primer plano del texto. Puede ser nulo. Use null para heredar la propiedad {@code ForegroundColor} del elemento estructural padre. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtiene o establece una alineación horizontal del párrafo |
| [getHorizontalScaling](#getHorizontalScaling--) | Obtiene o establece la escala horizontal del texto. Puede ser nulo. Use null para heredar la propiedad {@code HorizontalScaling} del elemento estructural padre. |
| [getLineSpacing](#getLineSpacing--) | Obtiene o establece el interlineado del texto. Puede ser nulo. Use null para heredar la propiedad {@code LineSpacing} del elemento estructural padre. |
| [getMarginInfo](#getMarginInfo--) | Obtiene o establece el margen para el elemento estructural de bloque. |
| [getStrikeOut](#getStrikeOut--) | Obtiene o establece el tachado del texto. Puede ser nulo. Use null para heredar la propiedad {@code StrikeOut} del elemento estructural padre. |
| [getSubscript](#getSubscript--) | Obtiene o establece el subíndice del texto. Puede ser nulo. Use null para heredar la propiedad {@code Subscript} del elemento estructural padre. |
| [getSuperscript](#getSuperscript--) | Obtiene o establece el superíndice del texto. Puede ser nulo. Use null para heredar la propiedad {@code Superscript} del elemento estructural padre. |
| [getUnderline](#getUnderline--) | Obtiene o establece el subrayado del texto. Puede ser nulo. Use null para heredar la propiedad {@code Underline} del elemento estructural padre. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene o establece una alineación vertical del párrafo |
| [getWordSpacing](#getWordSpacing--) | Obtiene o establece el espaciado de palabras del texto. Puede ser nulo. Use null para heredar la propiedad {@code WordSpacing} del elemento estructural padre. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. |
| [isInLineParagraph](#isInLineParagraph--) | Obtiene o establece si un párrafo está en línea. El valor predeterminado es falso. |
| [isInNewPage](#isInNewPage--) | Obtiene o establece un valor booleano que fuerza que este párrafo se genere en una nueva página. El valor predeterminado es falso. |
| [isKeptWithNext](#isKeptWithNext--) | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtiene o establece el color de fondo del texto. Puede ser nulo. Use null para heredar la propiedad {@code BackgroundColor} del elemento estructural padre. |
| [setCharacterSpacing](#setCharacterSpacing-com.aspose.ms.System.Nullable-) | Obtiene o establece el espaciado de caracteres del texto. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Obtiene o establece la fuente del texto. Puede ser nulo. Use null para heredar la propiedad {@code Font} del elemento estructural padre. |
| [setFontSize](#setFontSize-com.aspose.ms.System.Nullable-) | Obtiene o establece el tamaño de fuente del texto. |
| [setFontStyle](#setFontStyle-com.aspose.ms.System.Nullable-) | Obtiene o establece el estilo de fuente del texto. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Obtiene o establece el color de primer plano del texto. Puede ser nulo. Use null para heredar la propiedad {@code ForegroundColor} del elemento estructural padre. |
| [setHorizontalScaling](#setHorizontalScaling-com.aspose.ms.System.Nullable-) | Obtiene o establece la escala horizontal del texto. |
| [setLineSpacing](#setLineSpacing-com.aspose.ms.System.Nullable-) | Obtiene o establece el interlineado del texto. |
| [setMarginInfo](#setMarginInfo-com.aspose.pdf.MarginInfo-) | Obtiene o establece el margen para el elemento estructural de bloque. |
| [setStrikeOut](#setStrikeOut-com.aspose.ms.System.Nullable-) | Obtiene o establece el tachado del texto. |
| [setSubscript](#setSubscript-com.aspose.ms.System.Nullable-) | Obtiene o establece el subíndice del texto. |
| [setSuperscript](#setSuperscript-com.aspose.ms.System.Nullable-) | Obtiene o establece el superíndice del texto. |
| [setUnderline](#setUnderline-com.aspose.ms.System.Nullable-) | Obtiene o establece el subrayado del texto. |
| [setWordSpacing](#setWordSpacing-com.aspose.ms.System.Nullable-) | Obtiene o establece el espaciado de palabras del texto. |
| [update](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | Actualizar elementos |

### StructureTextState {#StructureTextState--}
```
public StructureTextState()
```

Constructor predeterminado

### createTextState {#createTextState--}
```
public final TextState createTextState()
```

Crear estado de texto

**Returns:**
instancia TextState

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtiene o establece el color de fondo del texto. Puede ser nulo. Use null para heredar la propiedad {@code BackgroundColor} del elemento estructural padre.

**Returns:**
Instancia de Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getCharacterSpacing()
```

Obtiene o establece el espaciado de caracteres del texto. Puede ser nulo. Use null para heredar la propiedad {@code CharacterSpacing} del elemento estructural padre.

**Returns:**
Matriz de flotantes

### getFont {#getFont--}
```
public final Font getFont()
```

Obtiene o establece la fuente del texto. Puede ser nulo. Use null para heredar la propiedad {@code Font} del elemento estructural padre.

**Returns:**
Instancia de Font

### getFontSize {#getFontSize--}
```
public final com.aspose.ms.System.Nullable< Float > getFontSize()
```

Obtiene o establece el tamaño de fuente del texto. Puede ser nulo. Use null para heredar la propiedad {@code FontSize} del elemento estructural padre.

**Returns:**
Matriz de flotantes

### getFontStyle {#getFontStyle--}
```
public final com.aspose.ms.System.Nullable< Integer > getFontStyle()
```

Obtiene o establece el estilo de fuente del texto. Puede ser nulo. Use null para heredar la propiedad {@code FontStyle} del elemento estructural padre.

**Returns:**
Matriz de enteros

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Obtiene o establece el color de primer plano del texto. Puede ser nulo. Use null para heredar la propiedad {@code ForegroundColor} del elemento estructural padre.

**Returns:**
Instancia de Color

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public final com.aspose.ms.System.Nullable< HorizontalAlignment > getHorizontalAlignment()
```

Obtiene o establece una alineación horizontal del párrafo

**Returns:**
Elemento HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public final com.aspose.ms.System.Nullable< Float > getHorizontalScaling()
```

Obtiene o establece la escala horizontal del texto. Puede ser nulo. Use null para heredar la propiedad {@code HorizontalScaling} del elemento estructural padre.

**Returns:**
Matriz de flotantes

### getLineSpacing {#getLineSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getLineSpacing()
```

Obtiene o establece el interlineado del texto. Puede ser nulo. Use null para heredar la propiedad {@code LineSpacing} del elemento estructural padre.

**Returns:**
Matriz de flotantes

### getMarginInfo {#getMarginInfo--}
```
@Deprecated public final MarginInfo getMarginInfo()
```

Obtiene o establece el margen para el elemento estructural de bloque.

**Returns:**
Instancia de MarginInfo @deprecated Utilice el método IAdjustPosition.AdjustPosition(PositionSettings positionSettings) para establecer la configuración de posición

### getStrikeOut {#getStrikeOut--}
```
public final com.aspose.ms.System.Nullable< Boolean > getStrikeOut()
```

Obtiene o establece el tachado del texto. Puede ser nulo. Use null para heredar la propiedad {@code StrikeOut} del elemento estructural padre.

**Returns:**
Matriz de booleanos

### getSubscript {#getSubscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSubscript()
```

Obtiene o establece el subíndice del texto. Puede ser nulo. Use null para heredar la propiedad {@code Subscript} del elemento estructural padre.

**Returns:**
Matriz de booleanos

### getSuperscript {#getSuperscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSuperscript()
```

Obtiene o establece el superíndice del texto. Puede ser nulo. Use null para heredar la propiedad {@code Superscript} del elemento estructural padre.

**Returns:**
Matriz de booleanos

### getUnderline {#getUnderline--}
```
public final com.aspose.ms.System.Nullable< Boolean > getUnderline()
```

Obtiene o establece el subrayado del texto. Puede ser nulo. Use null para heredar la propiedad {@code Underline} del elemento estructural padre.

**Returns:**
Matriz de booleanos

### getVerticalAlignment {#getVerticalAlignment--}
```
public final com.aspose.ms.System.Nullable< VerticalAlignment > getVerticalAlignment()
```

Obtiene o establece una alineación vertical del párrafo

**Returns:**
Elemento VerticalAlignment

### getWordSpacing {#getWordSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getWordSpacing()
```

Obtiene o establece el espaciado de palabras del texto. Puede ser nulo. Use null para heredar la propiedad {@code WordSpacing} del elemento estructural padre.

**Returns:**
Matriz de flotantes

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public final com.aspose.ms.System.Nullable< Boolean > isFirstParagraphInColumn()
```

Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso.

**Returns:**
Valor booleano

### isInLineParagraph {#isInLineParagraph--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInLineParagraph()
```

Obtiene o establece si un párrafo está en línea. El valor predeterminado es falso.

**Returns:**
Valor booleano

### isInNewPage {#isInNewPage--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInNewPage()
```

Obtiene o establece un valor booleano que fuerza que este párrafo se genere en una nueva página. El valor predeterminado es falso.

**Returns:**
Valor booleano

### isKeptWithNext {#isKeptWithNext--}
```
public final com.aspose.ms.System.Nullable< Boolean > isKeptWithNext()
```

Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso.

**Returns:**
Valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtiene o establece el color de fondo del texto. Puede ser nulo. Use null para heredar la propiedad {@code BackgroundColor} del elemento estructural padre.

### setCharacterSpacing {#setCharacterSpacing-com.aspose.ms.System.Nullable-}
Obtiene o establece el espaciado de caracteres del texto.

### setFont {#setFont-com.aspose.pdf.Font-}
Obtiene o establece la fuente del texto. Puede ser nulo. Use null para heredar la propiedad {@code Font} del elemento estructural padre.

### setFontSize {#setFontSize-com.aspose.ms.System.Nullable-}
Obtiene o establece el tamaño de fuente del texto.

### setFontStyle {#setFontStyle-com.aspose.ms.System.Nullable-}
Obtiene o establece el estilo de fuente del texto.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Obtiene o establece el color de primer plano del texto. Puede ser nulo. Use null para heredar la propiedad {@code ForegroundColor} del elemento estructural padre.

### setHorizontalScaling {#setHorizontalScaling-com.aspose.ms.System.Nullable-}
Obtiene o establece la escala horizontal del texto.

### setLineSpacing {#setLineSpacing-com.aspose.ms.System.Nullable-}
Obtiene o establece el interlineado del texto.

### setMarginInfo {#setMarginInfo-com.aspose.pdf.MarginInfo-}
Obtiene o establece el margen para el elemento estructural de bloque.

### setStrikeOut {#setStrikeOut-com.aspose.ms.System.Nullable-}
Obtiene o establece el tachado del texto.

### setSubscript {#setSubscript-com.aspose.ms.System.Nullable-}
Obtiene o establece el subíndice del texto.

### setSuperscript {#setSuperscript-com.aspose.ms.System.Nullable-}
Obtiene o establece el superíndice del texto.

### setUnderline {#setUnderline-com.aspose.ms.System.Nullable-}
Obtiene o establece el subrayado del texto.

### setWordSpacing {#setWordSpacing-com.aspose.ms.System.Nullable-}
Obtiene o establece el espaciado de palabras del texto.

### update {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
Actualizar elementos
