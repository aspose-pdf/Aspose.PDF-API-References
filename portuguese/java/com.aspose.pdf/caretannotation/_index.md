---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a anotação Caret."
type: docs
weight: 470
url: /pt/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Classe que representa a anotação Caret.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Construtor para uso em Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Cria nova anotação Caret na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getFrame](#getFrame--) | Obtém retângulo do caret. |
| [getSymbol](#getSymbol--) | Obtém símbolo associado ao caret. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Define retângulo do caret. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | Define o tamanho da página de saída para importação. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Construtor para uso em Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Cria nova anotação Caret na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Obtém retângulo do caret.

**Returns:**
retângulo do caret.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Obtém símbolo associado ao caret. {@code CaretSymbol}

**Returns:**
Elemento CaretSymbol @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Define retângulo do caret.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
Define o tamanho da página de saída para importação.
