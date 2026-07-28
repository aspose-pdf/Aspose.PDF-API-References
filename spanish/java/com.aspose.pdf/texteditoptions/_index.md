---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Describe opciones de operaciones de edición de texto."
type: docs
weight: 4970
url: /es/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Describe opciones de operaciones de edición de texto.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Inicializa una nueva instancia del objeto {@code TextEditOptions} para el modo de reorganización de texto especificado. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Obtiene el valor que permite el uso de la transformación de lenguaje durante la adición o edición de texto. true - la transformación de lenguaje se aplicará si es necesario (valor predeterminado). false - la transformación de lenguaje NO se aplicará. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Obtiene el modo para procesar la ruta de recorte del texto editado. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Obtiene el modo que define el comportamiento para escenarios de reemplazo de fuentes. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Obtiene el modo que define el comportamiento para escenarios de transformación de lenguaje. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Obtiene el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [getReplacementFont](#getReplacementFont--) | Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Obtiene o establece el valor que permite buscar subrayado de texto en la página del documento fuente. <p> (Obsoleto) Por favor use TextSearchOptions.SearchForTextRelatedGraphics en su lugar. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Establece el valor que permite el uso de la transformación de lenguaje durante la adición o edición de texto. true - la transformación de lenguaje se aplicará si es necesario (valor predeterminado). false - la transformación de lenguaje NO se aplicará. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Obtiene el modo para procesar la ruta de recorte del texto editado. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Establece el modo que define el comportamiento para escenarios de reemplazo de fuentes. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Establece el modo que define el comportamiento para escenarios de transformación de lenguaje. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Obtiene o establece el valor que permite buscar subrayado de texto en la página del documento fuente. <p> (Obsoleto) Por favor use TextSearchOptions.SearchForTextRelatedGraphics en su lugar. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Inicializa una nueva instancia del objeto {@code TextEditOptions} para el modo de reorganización de texto especificado. / * / *

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Inicializa una nueva instancia del objeto {@code TextEditOptions} con opciones predeterminadas. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Obtiene el valor que permite el uso de la transformación de lenguaje durante la adición o edición de texto. true - la transformación de lenguaje se aplicará si es necesario (valor predeterminado). false - la transformación de lenguaje NO se aplicará.

**Returns:**
valor booleano

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Obtiene el modo para procesar la ruta de recorte del texto editado.

**Returns:**
Elemento ClippingPathsProcessingMode

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Obtiene el modo que define el comportamiento para escenarios de reemplazo de fuentes.

**Returns:**
Valor de FontReplace @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Obtiene el modo que define el comportamiento para escenarios de transformación de lenguaje.

**Returns:**
Valor de LanguageTransformation @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Obtiene el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados.

**Returns:**
Valor de NoCharacterAction @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido

**Returns:**
Instancia de Font

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Obtiene o establece el valor que permite buscar subrayado de texto en la página del documento fuente. <p> (Obsoleto) Por favor use TextSearchOptions.SearchForTextRelatedGraphics en su lugar. </p>

**Returns:**
valor booleano

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Establece el valor que permite el uso de la transformación de lenguaje durante la adición o edición de texto. true - la transformación de lenguaje se aplicará si es necesario (valor predeterminado). false - la transformación de lenguaje NO se aplicará.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Obtiene el modo para procesar la ruta de recorte del texto editado.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Establece el modo que define el comportamiento para escenarios de reemplazo de fuentes.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Establece el modo que define el comportamiento para escenarios de transformación de lenguaje.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Obtiene o establece el valor que permite buscar subrayado de texto en la página del documento fuente. <p> (Obsoleto) Por favor use TextSearchOptions.SearchForTextRelatedGraphics en su lugar. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
