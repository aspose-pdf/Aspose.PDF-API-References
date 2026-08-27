---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa anotação de linha."
type: docs
weight: 2710
url: /pt/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Classe que representa anotação de linha.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Construtor para uso com Generator. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Cria uma nova anotação de linha na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um visitante para o processamento de anotação. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Atualiza os pontos de início e fim, de acordo com a transformação da matriz. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getCaptionOffset](#getCaptionOffset--) | Obtém o deslocamento do texto da legenda a partir de sua posição normal. |
| [getCaptionPosition](#getCaptionPosition--) | Obtém a posição da legenda da anotação. |
| [getEnding](#getEnding--) | Obtém o ponto final da linha. |
| [getEndingStyle](#getEndingStyle--) | Obtém o estilo de terminação para o ponto final da linha. |
| [getIntent](#getIntent--) | Obtém a intenção da anotação de linha. |
| [getInteriorColor](#getInteriorColor--) | Obtém a cor interna da anotação. |
| [getLeaderLine](#getLeaderLine--) | Obtém o comprimento da linha guia. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Obtém o comprimento da extensão da linha guia. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Obtém o deslocamento da linha guia. |
| [getMeasure](#getMeasure--) | Unidades de medida especificadas para esta anotação. |
| [getShowCaption](#getShowCaption--) | Obtém a bandeira booleana que determina se o conteúdo deve ser exibido como legenda. |
| [getStarting](#getStarting--) | Obtém o ponto inicial da linha. |
| [getStartingStyle](#getStartingStyle--) | Obtém o estilo de terminação da linha para o ponto inicial da linha. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Define o deslocamento do texto da legenda a partir de sua posição normal. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Define a posição da legenda da anotação. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Define o ponto final da linha. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Define o estilo de terminação para o ponto final da linha. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Define a intenção da anotação de linha. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Define a cor interna da anotação. |
| [setLeaderLine](#setLeaderLine-double-) | Define o comprimento da linha guia. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Define o comprimento da extensão da linha guia. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Define o deslocamento da linha guia. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Unidades de medida especificadas para esta anotação. |
| [setShowCaption](#setShowCaption-boolean-) | Define a bandeira booleana que determina se o conteúdo deve ser exibido como legenda. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Define o ponto inicial da linha. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Define o estilo de término da linha para o ponto inicial da linha. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Construtor para uso com Generator.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Cria uma nova anotação de linha na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um visitante para o processamento de anotação.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Atualiza os pontos de início e fim, de acordo com a transformação da matriz.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Obtém o deslocamento do texto da legenda a partir de sua posição normal.

**Returns:**
Objeto Point

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Obtém a posição da legenda da anotação.

**Returns:**
Elemento CaptionPosition @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Obtém o ponto final da linha.

**Returns:**
Valor do ponto

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtém o estilo de terminação para o ponto final da linha.

**Returns:**
Elemento LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Obtém a intenção da anotação de linha.

**Returns:**
Elemento LineIntent @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Obtém a cor interna da anotação.

**Returns:**
Objeto Color

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Obtém o comprimento da linha guia.

**Returns:**
valor double

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Obtém o comprimento da extensão da linha guia.

**Returns:**
valor double

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Obtém o deslocamento da linha guia.

**Returns:**
valor double

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Unidades de medida especificadas para esta anotação.

**Returns:**
Objeto Measure

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

Obtém a bandeira booleana que determina se o conteúdo deve ser exibido como legenda.

**Returns:**
valor booleano

### getStarting {#getStarting--}
```
public Point getStarting()
```

Obtém o ponto inicial da linha.

**Returns:**
Valor do ponto

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Obtém o estilo de terminação da linha para o ponto inicial da linha.

**Returns:**
Elemento LineEnding @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Define o deslocamento do texto da legenda a partir de sua posição normal.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Define a posição da legenda da anotação.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Define o ponto final da linha.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Define o estilo de terminação para o ponto final da linha.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Define a intenção da anotação de linha.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Define a cor interna da anotação.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Define o comprimento da linha guia.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Define o comprimento da extensão da linha guia.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Define o deslocamento da linha guia.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Unidades de medida especificadas para esta anotação.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

Define a bandeira booleana que determina se o conteúdo deve ser exibido como legenda.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Define o ponto inicial da linha.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Define o estilo de término da linha para o ponto inicial da linha.
