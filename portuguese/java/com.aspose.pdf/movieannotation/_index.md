---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma anotação de filme que contém gráficos animados e som a serem apresentados na tela do computador e pelos alto-falantes. Quando a anotação é ativada, o."
type: docs
weight: 3090
url: /pt/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Representa uma anotação de filme que contém gráficos animados e som a serem apresentados na tela do computador e pelos alto-falantes. Quando a anotação é ativada, o filme é reproduzido.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Construtor para uso com Generator. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Cria nova anotação Sound na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getAspect](#getAspect--) | Obtém ou define a largura e a altura da caixa delimitadora do filme, em pixels. |
| [getFile](#getFile--) | Obtém uma especificação de arquivo que identifica um arquivo de filme auto‑descritivo. |
| [getPoster](#getPoster--) | Obtém ou define uma bandeira ou fluxo que especifica se e como uma imagem de pôster representando o filme deve ser exibida. Se verdadeiro, a imagem de pôster será obtida do arquivo de filme; se for falso, nenhum pôster será exibido. |
| [getRotate](#getRotate--) | Obtém ou define o número de graus pelos quais o filme deve ser girado no sentido horário em relação à página. O valor deve ser múltiplo de 90. |
| [getTitle](#getTitle--) | Obtém o título da anotação do filme. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Obtém ou define a largura e a altura da caixa delimitadora do filme, em pixels. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Define uma especificação de arquivo que identifica um arquivo de filme auto‑descritivo. |
| [setPoster](#setPoster-boolean-) | Obtém ou define uma bandeira ou fluxo que especifica se e como uma imagem de pôster representando o filme deve ser exibida. Se verdadeiro, a imagem de pôster será obtida do arquivo de filme; se for falso, nenhum pôster será exibido. |
| [setRotate](#setRotate-int-) | Obtém ou define o número de graus pelos quais o filme deve ser girado no sentido horário em relação à página. O valor deve ser múltiplo de 90. |
| [setTitle](#setTitle-java.lang.String-) | Define o título da anotação do filme. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Construtor para uso com Generator.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Cria nova anotação Sound na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType como valor int @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Obtém ou define a largura e a altura da caixa delimitadora do filme, em pixels.

**Returns:**
Instância de Point

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Obtém uma especificação de arquivo que identifica um arquivo de filme auto‑descritivo.

**Returns:**
Valor FileSpecification

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Obtém ou define uma bandeira ou fluxo que especifica se e como uma imagem de pôster representando o filme deve ser exibida. Se verdadeiro, a imagem de pôster será obtida do arquivo de filme; se for falso, nenhum pôster será exibido.

**Returns:**
valor booleano

### getRotate {#getRotate--}
```
public final int getRotate()
```

Obtém ou define o número de graus pelos quais o filme deve ser girado no sentido horário em relação à página. O valor deve ser múltiplo de 90.

**Returns:**
valor int

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtém o título da anotação do filme.

**Returns:**
valor String

### setAspect {#setAspect-com.aspose.pdf.Point-}
Obtém ou define a largura e a altura da caixa delimitadora do filme, em pixels.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Define uma especificação de arquivo que identifica um arquivo de filme auto‑descritivo.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Obtém ou define uma bandeira ou fluxo que especifica se e como uma imagem de pôster representando o filme deve ser exibida. Se verdadeiro, a imagem de pôster será obtida do arquivo de filme; se for falso, nenhum pôster será exibido.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Obtém ou define o número de graus pelos quais o filme deve ser girado no sentido horário em relação à página. O valor deve ser múltiplo de 90.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setTitle {#setTitle-java.lang.String-}
Define o título da anotação do filme.
