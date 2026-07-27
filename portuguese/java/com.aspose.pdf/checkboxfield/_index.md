---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa um campo de caixa de seleção."
type: docs
weight: 580
url: /pt/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Classe que representa um campo de caixa de seleção.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [CheckboxField](#CheckboxField--) | Crie uma instância de CheckboxField. @deprecated Para funcionalidade completa do campo, é necessário vincular ao documento - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | Crie uma instância de CheckboxField. @deprecated Para funcionalidade completa do campo, é necessário vincular ao documento - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Crie uma instância de CheckboxField. @deprecated Para funcionalidade completa do campo, é necessário vincular ao documento - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crie uma instância de CheckboxField. @deprecated Para funcionalidade completa do campo, é necessário vincular ao documento - use CheckboxField(Document doc) |

## Métodos

| Método | Descrição |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Adiciona uma nova caixa de seleção a um grupo de caixas de seleção, no qual no máximo uma das caixas pode estar marcada a qualquer momento. A nova caixa de seleção é adicionada ao final do grupo. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Adiciona uma nova caixa de seleção a um grupo de caixas de seleção, no qual no máximo uma das caixas pode estar marcada a qualquer momento. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Adiciona uma nova caixa de seleção a um grupo de caixas de seleção, no qual no máximo uma das caixas pode estar marcada a qualquer momento. |
| [deepClone](#deepClone--) | Clone a caixa de seleção. |
| [getActiveState](#getActiveState--) | Obtém o estado atual de aparência da anotação. |
| [getAllowedStates](#getAllowedStates--) | Retorna a lista de estados permitidos. |
| [getChecked](#getChecked--) | Obtém o estado da caixa de seleção. |
| [getExportValue](#getExportValue--) | Obtém ou define o valor de exportação do campo CheckBox. |
| [getNormalCaption](#getNormalCaption--) | Obtém a legenda normal do campo. |
| [getOnState](#getOnState--) | Retorna o nome do estado que corresponde ao estado "Checked" da caixa de seleção. É "Yes" se presente ou qualquer outro valor diferente de "Off" e "No"; |
| [getStyle](#getStyle--) | Obtém o estilo da caixa de seleção. |
| [getValue](#getValue--) | Obtém o valor do campo da caixa de seleção. |
| [setActiveState](#setActiveState-java.lang.String-) | Define o estado atual da aparência da anotação. |
| [setChecked](#setChecked-boolean-) | Define o estado da caixa de seleção. |
| [setExportValue](#setExportValue-java.lang.String-) | Obtém ou define o valor de exportação do campo CheckBox. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Define o estilo da caixa de seleção. |
| [setValue](#setValue-java.lang.String-) | Define o valor do campo da caixa de seleção. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

Crie uma instância de CheckboxField. @deprecated Para funcionalidade completa do campo, é necessário vincular ao documento - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
Crie uma instância de CheckboxField. @deprecated Para funcionalidade completa do campo, é necessário vincular ao documento - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Crie uma instância de CheckboxField. @deprecated Para funcionalidade completa do campo, é necessário vincular ao documento - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crie uma instância de CheckboxField. @deprecated Para funcionalidade completa do campo, é necessário vincular ao documento - use CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
Adiciona uma nova caixa de seleção a um grupo de caixas de seleção, no qual no máximo uma das caixas pode estar marcada a qualquer momento. A nova caixa de seleção é adicionada ao final do grupo.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Adiciona uma nova caixa de seleção a um grupo de caixas de seleção, no qual no máximo uma das caixas pode estar marcada a qualquer momento.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Adiciona uma nova caixa de seleção a um grupo de caixas de seleção, no qual no máximo uma das caixas pode estar marcada a qualquer momento.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone a caixa de seleção.

**Returns:**
O objeto clonado

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Obtém o estado atual de aparência da anotação.

**Returns:**
valor String

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

Retorna a lista de estados permitidos.

**Returns:**
lista de valores String

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Obtém o estado da caixa de seleção.

**Returns:**
valor booleano

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

Obtém ou define o valor de exportação do campo CheckBox.

**Returns:**
valor String

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Obtém a legenda normal do campo.

**Returns:**
valor String

### getOnState {#getOnState--}
```
public String getOnState()
```

Retorna o nome do estado que corresponde ao estado "Checked" da caixa de seleção. É "Yes" se presente ou qualquer outro valor diferente de "Off" e "No";

**Returns:**
valor String

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Obtém o estilo da caixa de seleção.

**Returns:**
estilo da caixa de seleção. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Obtém o valor do campo da caixa de seleção.

**Returns:**
valor String

### setActiveState {#setActiveState-java.lang.String-}
Define o estado atual da aparência da anotação.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Define o estado da caixa de seleção.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setExportValue {#setExportValue-java.lang.String-}
Obtém ou define o valor de exportação do campo CheckBox.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Define o estilo da caixa de seleção.

### setValue {#setValue-java.lang.String-}
Define o valor do campo da caixa de seleção.
