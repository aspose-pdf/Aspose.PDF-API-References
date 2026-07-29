---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa anotação de widget."
type: docs
weight: 5540
url: /pt/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Classe que representa anotação de widget.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Criar anotação (usado para Gerador) |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita visitante. |
| [getAnnotationActions](#getAnnotationActions--) | Obtém as ações da anotação. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getCheckedStateName](#getCheckedStateName--) | Retorna o nome do estado "checked" de acordo com os nomes de estado existentes. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtém a aparência padrão do campo. |
| [getExportable](#getExportable--) | Obtém a bandeira exportável do campo. |
| [getHighlighting](#getHighlighting--) | Modo de realce da anotação. |
| [getOnActivated](#getOnActivated--) | Obtenha uma ação que deverá ser executada quando a anotação for ativada. |
| [getParent](#getParent--) | Obtém o elemento pai da anotação. |
| [getReadOnly](#getReadOnly--) | Obtém o status somente leitura do campo. |
| [getRequired](#getRequired--) | Obtém o status obrigatório do campo. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Define a aparência padrão do campo. |
| [setExportable](#setExportable-boolean-) | Define o status somente leitura do campo. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Modo de realce da anotação. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Defina uma ação que deverá ser executada quando a anotação for ativada. |
| [setReadOnly](#setReadOnly-boolean-) | Define o status somente leitura do campo. |
| [setRequired](#setRequired-boolean-) | Define o status somente leitura do campo. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Criar anotação (usado para Gerador)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita visitante.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Obtém as ações da anotação.

**Returns:**
Objeto AnnotationActionCollection

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Retorna o nome do estado "checked" de acordo com os nomes de estado existentes.

**Returns:**
O nome do estado "checked" para esta anotação.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Obtém a aparência padrão do campo.

**Returns:**
objeto DefaultAppearance

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Obtém a bandeira exportável do campo.

**Returns:**
valor booleano

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Modo de realce da anotação.

**Returns:**
Valor HighlightingMode @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Obtenha uma ação que deverá ser executada quando a anotação for ativada.

**Returns:**
Objeto PdfAction

### getParent {#getParent--}
```
public Field getParent()
```

Obtém o elemento pai da anotação.

**Returns:**
Objeto Field

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Obtém o status somente leitura do campo.

**Returns:**
valor booleano

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Obtém o status obrigatório do campo.

**Returns:**
valor booleano

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Define a aparência padrão do campo.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Define o status somente leitura do campo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Modo de realce da anotação.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Defina uma ação que deverá ser executada quando a anotação for ativada.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Define o status somente leitura do campo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Define o status somente leitura do campo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
