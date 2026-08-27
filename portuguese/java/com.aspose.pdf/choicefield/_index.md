---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe base para campos de escolha."
type: docs
weight: 590
url: /pt/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Representa a classe base para campos de escolha.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Cria campo de escolha (para Generator) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Construtor para ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Construtor para ChoiceField. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Adiciona nova opção com o nome especificado. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Adiciona nova opção com o valor de exportação e nome especificados. |
| [deleteOption](#deleteOption-java.lang.String-) | Exclui a opção pelo seu nome. |
| [getCommitImmediately](#getCommitImmediately--) | Obtém o indicador de commit ao mudar a seleção. |
| [getMultiSelect](#getMultiSelect--) | Obtém o indicador de multiseleção. |
| [getOptions](#getOptions--) | Obtém a coleção de opções de escolha. |
| [getSelected](#getSelected--) | Obtém o índice da opção selecionada. Esta propriedade permite alterar a seleção. |
| [getSelectedItems](#getSelectedItems--) | Define o array de itens selecionados. Para lista de múltipla seleção, o array contém mais de um item. Para lista de seleção única, contém um único item. |
| [getValue](#getValue--) | Obtém o valor do campo. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Define o indicador de commit ao mudar a seleção. |
| [setMultiSelect](#setMultiSelect-boolean-) | Define o indicador de multiseleção. |
| [setOptions](#setOptions-java.util.List-) | Substitui as opções disponíveis por aquelas cujos nomes são fornecidos no parâmetro options. |
| [setSelected](#setSelected-int-) | Define o índice da opção selecionada. Esta propriedade permite alterar a seleção. |
| [setSelectedItems](#setSelectedItems-int:A-) | Define o array de itens selecionados. Para lista de múltipla seleção, o array contém mais de um item. Para lista de seleção única, contém um único item. |
| [setValue](#setValue-java.lang.String-) | Define o valor do campo. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Cria campo de escolha (para Generator)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Construtor para ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Construtor para ChoiceField.

### addOption {#addOption-java.lang.String-}
Adiciona nova opção com o nome especificado.

### addOption {#addOption-java.lang.String-java.lang.String-}
Adiciona nova opção com o valor de exportação e nome especificados.

### deleteOption {#deleteOption-java.lang.String-}
Exclui a opção pelo seu nome.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Obtém o indicador de commit ao mudar a seleção.

**Returns:**
valor booleano

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Obtém o indicador de multiseleção.

**Returns:**
valor booleano

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Obtém a coleção de opções de escolha.

**Returns:**
Objeto OptionCollection

### getSelected {#getSelected--}
```
public int getSelected()
```

Obtém o índice da opção selecionada. Esta propriedade permite alterar a seleção.

**Returns:**
valor int

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Define o array de itens selecionados. Para lista de múltipla seleção, o array contém mais de um item. Para lista de seleção única, contém um único item.

**Returns:**
array de valores int

### getValue {#getValue--}
```
public String getValue()
```

Obtém o valor do campo.

**Returns:**
valor String

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Define o indicador de commit ao mudar a seleção.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Define o indicador de multiseleção.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOptions {#setOptions-java.util.List-}
Substitui as opções disponíveis por aquelas cujos nomes são fornecidos no parâmetro options.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Define o índice da opção selecionada. Esta propriedade permite alterar a seleção.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Define o array de itens selecionados. Para lista de múltipla seleção, o array contém mais de um item. Para lista de seleção única, contém um único item.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | array de valores int |

### setValue {#setValue-java.lang.String-}
Define o valor do campo.
