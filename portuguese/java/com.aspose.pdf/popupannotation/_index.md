---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a anotação pop‑up que exibe texto em uma janela pop‑up para inserção e edição."
type: docs
weight: 3930
url: /pt/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Representa a anotação pop‑up que exibe texto em uma janela pop‑up para inserção e edição.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Construtor. para uso no Gerador. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Cria nova anotação Popup na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getOpen](#getOpen--) | Obtém um sinalizador que especifica se a anotação pop-up deve ser exibida aberta inicialmente. |
| [getParent](#getParent--) | Obtém a anotação pai com a qual esta anotação pop-up deve ser associada. Se esta entrada estiver presente, as entradas Contents, M, C e T da anotação pai substituirão as da própria anotação pop-up. |
| [setOpen](#setOpen-boolean-) | Define um sinalizador que especifica se a anotação pop-up deve ser exibida aberta inicialmente. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Define a anotação pai com a qual esta anotação pop-up deve ser associada. Se esta entrada estiver presente, as entradas Contents, M, C e T da anotação pai substituirão as da própria anotação pop-up. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Construtor. para uso no Gerador.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Cria nova anotação Popup na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Obtém um sinalizador que especifica se a anotação pop-up deve ser exibida aberta inicialmente.

**Returns:**
valor booleano

### getParent {#getParent--}
```
public Annotation getParent()
```

Obtém a anotação pai com a qual esta anotação pop-up deve ser associada. Se esta entrada estiver presente, as entradas Contents, M, C e T da anotação pai substituirão as da própria anotação pop-up.

**Returns:**
Objeto MarkupAnnotation

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Define um sinalizador que especifica se a anotação pop-up deve ser exibida aberta inicialmente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Define a anotação pai com a qual esta anotação pop-up deve ser associada. Se esta entrada estiver presente, as entradas Contents, M, C e T da anotação pai substituirão as da própria anotação pop-up.
