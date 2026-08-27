---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o campo de caixa de texto."
type: docs
weight: 4930
url: /pt/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

Classe que representa o campo de caixa de texto.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextBoxField](#TextBoxField--) | Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc) |

## Métodos

| Método | Descrição |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | Adiciona o código de barras 128 ao campo. O valor do campo será alterado para o código e o campo se tornará somente leitura. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Adiciona imagem aos recursos do campo e a desenha. |
| [getForceCombs](#getForceCombs--) | Obtém o indicador que indica se o campo está dividido em posições espaçadas. |
| [getMaxLen](#getMaxLen--) | Obtém o comprimento máximo do texto no campo. |
| [getMultiline](#getMultiline--) | Obtém o indicador multilinha do campo. Se Multiline for verdadeiro, o campo pode conter várias linhas de texto. |
| [getScrollable](#getScrollable--) | Obtém o indicador rolável do campo. Se verdadeiro, o campo pode ser rolado. |
| [getSpellCheck](#getSpellCheck--) | Obtém o indicador de verificação ortográfica para o campo. Se verdadeiro, o campo será verificado ortograficamente. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | Obtém ou define o alinhamento vertical do texto para a anotação. |
| [getValue](#getValue--) | Obtém o valor do campo. |
| [setForceCombs](#setForceCombs-boolean-) | Define a bandeira que indica se o campo está dividido em posições espaçadas. |
| [setJustification](#setJustification-boolean-) | Define a justificação |
| [setMaxLen](#setMaxLen-int-) | Define o comprimento máximo do texto no campo. |
| [setMultiline](#setMultiline-boolean-) | Define a bandeira multilinha do campo. Se Multiline for verdadeiro, o campo pode conter várias linhas de texto. |
| [setScrollable](#setScrollable-boolean-) | Define a bandeira rolável do campo. Se verdadeiro, o campo pode ser rolado. |
| [setSpellCheck](#setSpellCheck-boolean-) | Define a bandeira de verificação ortográfica para o campo. Se verdadeiro, o campo será verificado ortograficamente. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtém ou define o alinhamento vertical do texto para a anotação. |
| [setValue](#setValue-java.lang.String-) | Define o valor do campo. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
Crie uma instância de TextBoxField. @deprecated Para funcionalidade completa do campo, é necessário um vínculo ao documento - use TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
Adiciona o código de barras 128 ao campo. O valor do campo será alterado para o código e o campo se tornará somente leitura.

### addImage {#addImage-java.awt.image.BufferedImage-}
Adiciona imagem aos recursos do campo e a desenha.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

Obtém o indicador que indica se o campo está dividido em posições espaçadas.

**Returns:**
valor booleano

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

Obtém o comprimento máximo do texto no campo.

**Returns:**
valor int

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

Obtém o indicador multilinha do campo. Se Multiline for verdadeiro, o campo pode conter várias linhas de texto.

**Returns:**
valor booleano

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

Obtém o indicador rolável do campo. Se verdadeiro, o campo pode ser rolado.

**Returns:**
valor booleano

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

Obtém o indicador de verificação ortográfica para o campo. Se verdadeiro, o campo será verificado ortograficamente.

**Returns:**
valor booleano

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

Obtém ou define o alinhamento vertical do texto para a anotação.

**Returns:**
Elemento VerticalAlignment

### getValue {#getValue--}
```
public String getValue()
```

Obtém o valor do campo.

**Returns:**
valor String

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

Define a bandeira que indica se o campo está dividido em posições espaçadas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

Define a justificação

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

Define o comprimento máximo do texto no campo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

Define a bandeira multilinha do campo. Se Multiline for verdadeiro, o campo pode conter várias linhas de texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

Define a bandeira rolável do campo. Se verdadeiro, o campo pode ser rolado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

Define a bandeira de verificação ortográfica para o campo. Se verdadeiro, o campo será verificado ortograficamente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtém ou define o alinhamento vertical do texto para a anotação.

### setValue {#setValue-java.lang.String-}
Define o valor do campo.
