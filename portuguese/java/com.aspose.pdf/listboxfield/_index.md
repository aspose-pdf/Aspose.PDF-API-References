---
title: "ListBoxField"
linktitle: "ListBoxField"
second_title: "Referência da API Aspose.PDF para Java"
description: "A classe representa o campo ListBox."
type: docs
weight: 2770
url: /pt/java/com.aspose.pdf/listboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.ChoiceField, com.aspose.pdf.ListBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class ListBoxField extends ChoiceField
```

A classe representa o campo ListBox.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ListBoxField](#ListBoxField--) | Construtor para ListBoxField a ser usado no Generator. |
| [ListBoxField](#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Construtor para ListBoxField a ser usado no Generator. |
| [ListBoxField](#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Construtor para ListBoxField a ser usado no Generator. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getTopIndex](#getTopIndex--) | Obtém o índice do elemento visível superior da lista. |
| [setSelected](#setSelected-int-) | Obtém o índice do item selecionado. Os itens são numerados a partir de 1. |
| [setSelectedItems](#setSelectedItems-int:A-) | Define o array dos itens selecionados na lista de múltipla seleção. Para lista de seleção única retorna um array com um único item. |
| [setTopIndex](#setTopIndex-int-) | Define o índice do elemento visível superior da lista. |

### ListBoxField {#ListBoxField--}
```
public ListBoxField()
```

Construtor para ListBoxField a ser usado no Generator.

### ListBoxField {#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Construtor para ListBoxField a ser usado no Generator.

### ListBoxField {#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Construtor para ListBoxField a ser usado no Generator.

### getTopIndex {#getTopIndex--}
```
public int getTopIndex()
```

Obtém o índice do elemento visível superior da lista.

**Returns:**
valor int

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Obtém o índice do item selecionado. Os itens são numerados a partir de 1.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Define o array dos itens selecionados na lista de múltipla seleção. Para lista de seleção única retorna um array com um único item.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | array de valores int |

### setTopIndex {#setTopIndex-int-}
```
public void setTopIndex(int value)
```

Define o índice do elemento visível superior da lista.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
