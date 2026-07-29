---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma anotação de texto que é um \\\"sticky note\\\" anexado a um ponto no documento PDF."
type: docs
weight: 4920
url: /pt/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

Representa uma anotação de texto que é um \"sticky note\" anexado a um ponto no documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | Criar instância de TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | Criar instância de TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Criar instância de TextAnnotation |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Substitui a definição na classe base com um corpo vazio. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getIcon](#getIcon--) | Obtém um ícone a ser usado na exibição da anotação. |
| [getOpen](#getOpen--) | Obtém um indicador que especifica se a anotação deve ser exibida aberta inicialmente. |
| [setIcon](#setIcon-int-) | Define um ícone a ser usado na exibição da anotação. |
| [setOpen](#setOpen-boolean-) | Define um indicador que especifica se a anotação deve ser exibida aberta inicialmente. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

Criar instância de TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
Criar instância de TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Criar instância de TextAnnotation

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Substitui a definição na classe base com um corpo vazio.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Valor AnnotationType @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Obtém um ícone a ser usado na exibição da anotação.

**Returns:**
Valor TextIcon @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Obtém um indicador que especifica se a anotação deve ser exibida aberta inicialmente.

**Returns:**
valor booleano

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Define um ícone a ser usado na exibição da anotação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor TextIcon @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Define um indicador que especifica se a anotação deve ser exibida aberta inicialmente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
