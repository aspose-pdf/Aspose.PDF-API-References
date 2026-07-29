---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Descreve opções de operações de edição de texto."
type: docs
weight: 4970
url: /pt/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Descreve opções de operações de edição de texto.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Inicializa nova instância do objeto {@code TextEditOptions} para o modo de reorganização de texto especificado. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Obtém o valor que permite o uso de transformação de idioma durante a adição ou edição de texto. true - a transformação de idioma será aplicada se necessário (valor padrão). false - a transformação de idioma NÃO será aplicada. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Obtém o modo de processamento do caminho de recorte do texto editado. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Obtém o modo que define o comportamento para cenários de substituição de fontes. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Obtém o modo que define o comportamento para cenários de transformação de idioma. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Obtém o modo que define o comportamento caso as fontes não contenham os caracteres solicitados. |
| [getReplacementFont](#getReplacementFont--) | Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Obtém ou define o valor que permite a busca por sublinhado de texto na página do documento de origem. <p> (Obsoleto) Por favor, use TextSearchOptions.SearchForTextRelatedGraphics em vez disso. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Define o valor que permite o uso de transformação de idioma durante a adição ou edição de texto. true - a transformação de idioma será aplicada se necessário (valor padrão). false - a transformação de idioma NÃO será aplicada. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Obtém o modo de processamento do caminho de recorte do texto editado. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Define o modo que determina o comportamento para cenários de substituição de fontes. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Define o modo que determina o comportamento para cenários de transformação de idioma. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Define o modo que determina o comportamento caso as fontes não contenham os caracteres solicitados. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Obtém ou define o valor que permite a busca por sublinhado de texto na página do documento de origem. <p> (Obsoleto) Por favor, use TextSearchOptions.SearchForTextRelatedGraphics em vez disso. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Inicializa nova instância do objeto {@code TextEditOptions} para o modo de reorganização de texto especificado. / * / *

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Inicializa nova instância do objeto {@code TextEditOptions} com opções padrão. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Obtém o valor que permite o uso de transformação de idioma durante a adição ou edição de texto. true - a transformação de idioma será aplicada se necessário (valor padrão). false - a transformação de idioma NÃO será aplicada.

**Returns:**
valor booleano

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Obtém o modo de processamento do caminho de recorte do texto editado.

**Returns:**
Elemento ClippingPathsProcessingMode

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Obtém o modo que define o comportamento para cenários de substituição de fontes.

**Returns:**
FontReplace valor @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Obtém o modo que define o comportamento para cenários de transformação de idioma.

**Returns:**
LanguageTransformation valor @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Obtém o modo que define o comportamento caso as fontes não contenham os caracteres solicitados.

**Returns:**
NoCharacterAction valor @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário

**Returns:**
Instância Font

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Obtém ou define o valor que permite a busca por sublinhado de texto na página do documento de origem. <p> (Obsoleto) Por favor, use TextSearchOptions.SearchForTextRelatedGraphics em vez disso. </p>

**Returns:**
valor booleano

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Define o valor que permite o uso de transformação de idioma durante a adição ou edição de texto. true - a transformação de idioma será aplicada se necessário (valor padrão). false - a transformação de idioma NÃO será aplicada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Obtém o modo de processamento do caminho de recorte do texto editado.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Define o modo que determina o comportamento para cenários de substituição de fontes.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Define o modo que determina o comportamento para cenários de transformação de idioma.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Define o modo que determina o comportamento caso as fontes não contenham os caracteres solicitados.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Obtém ou define o valor que permite a busca por sublinhado de texto na página do documento de origem. <p> (Obsoleto) Por favor, use TextSearchOptions.SearchForTextRelatedGraphics em vez disso. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
