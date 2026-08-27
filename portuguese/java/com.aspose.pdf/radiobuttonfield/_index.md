---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa um campo de botão de opção."
type: docs
weight: 4080
url: /pt/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Classe que representa um campo de botão de opção.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | Construtor para RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | Construtor para RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Define o campo de botão de rádio. |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | Adiciona um novo campo de opção ao campo RadioButton. |
| [addOption](#addOption-java.lang.String-) | Adicionar opção ao botão de rádio. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Adicionar à opção do botão de rádio com retângulo especificado. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Obtém ou define o indicador que permite que o botão de rádio não tenha valor selecionado. Se {@code }, exatamente um botão de rádio deve estar selecionado o tempo todo; selecionar o botão atualmente selecionado não tem efeito. Se {@code }, clicar no botão selecionado o desmarca, deixando nenhum botão selecionado. </p> <hr> Alguns leitores de PDF (incluindo o Adobe Acrobat) podem ignorar o estado da bandeira. |
| [getOptions](#getOptions--) | Obtém a coleção de opções do botão de rádio. |
| [getPageIndex](#getPageIndex--) | Obtém o índice da página que contém este campo RadioButton. |
| [getSelected](#getSelected--) | Obtém o índice do item selecionado. A numeração dos itens começa em 1. |
| [getStyle](#getStyle--) | Estilo da caixa de campo. |
| [getValue](#getValue--) | Obtém o valor do campo. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Obtém ou define o indicador que permite que o botão de rádio não tenha valor selecionado. Se {@code }, exatamente um botão de rádio deve estar selecionado o tempo todo; selecionar o botão atualmente selecionado não tem efeito. Se {@code }, clicar no botão selecionado o desmarca, deixando nenhum botão selecionado. </p> <hr> Alguns leitores de PDF (incluindo o Adobe Acrobat) podem ignorar o estado da bandeira. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Move todos os subitens do botão de rádio para as posições especificadas na página. |
| [setSelected](#setSelected-int-) | Define o índice do item selecionado. A numeração dos itens começa a partir de 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Estilo da caixa de campo. |
| [setValue](#setValue-java.lang.String-) | Define o valor do campo. |
| [updateAppearances](#updateAppearances--) | Atualiza o valor das aparências. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
Construtor para RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
Construtor para RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Define o campo de botão de rádio.

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
Adiciona um novo campo de opção ao campo RadioButton.

### addOption {#addOption-java.lang.String-}
Adicionar opção ao botão de rádio.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Adicionar à opção do botão de rádio com retângulo especificado.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Obtém ou define o indicador que permite que o botão de rádio não tenha valor selecionado. Se {@code }, exatamente um botão de rádio deve estar selecionado o tempo todo; selecionar o botão atualmente selecionado não tem efeito. Se {@code }, clicar no botão selecionado o desmarca, deixando nenhum botão selecionado. </p> <hr> Alguns leitores de PDF (incluindo o Adobe Acrobat) podem ignorar o estado da bandeira.

**Returns:**
valor booleano

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Obtém a coleção de opções do botão de rádio.

**Returns:**
Objeto OptionCollection

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtém o índice da página que contém este campo RadioButton.

**Returns:**
valor int

### getSelected {#getSelected--}
```
public int getSelected()
```

Obtém o índice do item selecionado. A numeração dos itens começa em 1.

**Returns:**
valor int

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Estilo da caixa de campo.

**Returns:**
Valor BoxStyle @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Obtém o valor do campo.

**Returns:**
valor String

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Obtém ou define o indicador que permite que o botão de rádio não tenha valor selecionado. Se {@code }, exatamente um botão de rádio deve estar selecionado o tempo todo; selecionar o botão atualmente selecionado não tem efeito. Se {@code }, clicar no botão selecionado o desmarca, deixando nenhum botão selecionado. </p> <hr> Alguns leitores de PDF (incluindo o Adobe Acrobat) podem ignorar o estado da bandeira.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Move todos os subitens do botão de rádio para as posições especificadas na página.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Define o índice do item selecionado. A numeração dos itens começa a partir de 1.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Estilo da caixa de campo.

### setValue {#setValue-java.lang.String-}
Define o valor do campo.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Atualiza o valor das aparências.
