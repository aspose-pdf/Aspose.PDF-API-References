---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um link hipertexto para um destino em outra parte do documento ou uma ação a ser executada."
type: docs
weight: 2760
url: /pt/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Representa um link hipertexto para um destino em outra parte do documento ou uma ação a ser executada.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Cria uma nova anotação de link na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [getAction](#getAction--) | Obtém uma ação a ser executada quando a anotação de link for ativada. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getDestination](#getDestination--) | Obtém um destino a ser exibido quando a anotação for ativada. |
| [getHighlighting](#getHighlighting--) | Obtém o efeito visual a ser usado quando o botão do mouse é pressionado ou mantido pressionado dentro de sua área ativa. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Define uma ação a ser executada quando a anotação de link for ativada. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Define um destino a ser exibido quando a anotação for ativada. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Define o efeito visual a ser usado quando o botão do mouse é pressionado ou mantido pressionado dentro de sua área ativa. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Cria uma nova anotação de link na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Obtém uma ação a ser executada quando a anotação de link for ativada.

**Returns:**
Valor PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Obtém um destino a ser exibido quando a anotação for ativada.

**Returns:**
valor IAppointment

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Obtém o efeito visual a ser usado quando o botão do mouse é pressionado ou mantido pressionado dentro de sua área ativa.

**Returns:**
Elemento HighlightingMode @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Define uma ação a ser executada quando a anotação de link for ativada.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Define um destino a ser exibido quando a anotação for ativada.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Define o efeito visual a ser usado quando o botão do mouse é pressionado ou mantido pressionado dentro de sua área ativa.
