---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a anotação Redact."
type: docs
weight: 4120
url: /pt/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Representa a anotação Redact.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Construtor para RedactionAnnotation. Para uso no Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Construtor para RedactAnnotation. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [flatten](#flatten--) | Achata a anotação, ou seja, remove a anotação e adiciona seu conteúdo |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getBorderColor](#getBorderColor--) | Obtém a cor da borda que é desenhada quando a redação não está ativa. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtém ou define a string de aparência padrão a ser usada na formatação do texto. |
| [getFillColor](#getFillColor--) | Obtém a cor para preencher a anotação. |
| [getFontSize](#getFontSize--) | Obtém o tamanho da fonte para OverlayText. |
| [getOverlayText](#getOverlayText--) | Obtém o texto a ser impresso na anotação de redação. |
| [getQuadPoint](#getQuadPoint--) | Um array de números 8xN especificando as coordenadas da região de conteúdo que se destina a ser removida. |
| [getQuadPoints](#getQuadPoints--) | Obtém um array de pontos que especifica as coordenadas de n quadriláteros. Cada quadrilátero abrange uma palavra ou um grupo de palavras contíguas no texto subjacente à anotação. |
| [getTextAlignment](#getTextAlignment--) | Obtém o alinhamento do Overlay Text. |
| [isRepeat](#isRepeat--) | Se verdadeiro, o texto sobreposto será repetido na anotação. |
| [redact](#redact--) | Achata a anotação e redige o conteúdo da página (ou seja, remove texto e conteúdo de imagem sob a anotação redigida). |
| [redactExact](#redactExact--) | Achata a anotação e redige o conteúdo da página (ou seja, remove texto e conteúdo de imagem exatamente sob a anotação redigida). |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Define a cor da borda que é desenhada quando a redação não está ativa. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Obtém ou define a string de aparência padrão a ser usada na formatação do texto. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Define a cor para preencher a anotação. |
| [setFontSize](#setFontSize-float-) | Define o tamanho da fonte para OverlayText. O valor padrão é 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Define o texto a ser impresso na anotação de redação. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | Um array de números 8xN especificando as coordenadas da região de conteúdo que se destina a ser removida. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Define um array de pontos que especifica as coordenadas de n quadriláteros. Cada quadrilátero abrange uma palavra ou um grupo de palavras contíguas no texto subjacente à anotação. |
| [setRepeat](#setRepeat-boolean-) | Se verdadeiro, o texto sobreposto será repetido na anotação. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Define o alinhamento do Overlay Text. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
Construtor para RedactionAnnotation. Para uso no Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Construtor para RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### flatten {#flatten--}
```
public void flatten()
```

Achata a anotação, ou seja, remove a anotação e adiciona seu conteúdo

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Obtém a cor da borda que é desenhada quando a redação não está ativa.

**Returns:**
Valor da cor

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Obtém ou define a string de aparência padrão a ser usada na formatação do texto.

**Returns:**
valor String

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Obtém a cor para preencher a anotação.

**Returns:**
valor da cor

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Obtém o tamanho da fonte para OverlayText.

**Returns:**
valor int

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Obtém o texto a ser impresso na anotação de redação.

**Returns:**
valor de string

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

Um array de números 8xN especificando as coordenadas da região de conteúdo que se destina a ser removida.

**Returns:**
array de ponto

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

Obtém um array de pontos que especifica as coordenadas de n quadriláteros. Cada quadrilátero abrange uma palavra ou um grupo de palavras contíguas no texto subjacente à anotação.

**Returns:**
array de valores Point

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Obtém o alinhamento do Overlay Text.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

Se verdadeiro, o texto sobreposto será repetido na anotação.

**Returns:**
valor booleano

### redact {#redact--}
```
public void redact()
```

Achata a anotação e redige o conteúdo da página (ou seja, remove texto e conteúdo de imagem sob a anotação redigida).

### redactExact {#redactExact--}
```
public void redactExact()
```

Achata a anotação e redige o conteúdo da página (ou seja, remove texto e conteúdo de imagem exatamente sob a anotação redigida).

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Define a cor da borda que é desenhada quando a redação não está ativa.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Obtém ou define a string de aparência padrão a ser usada na formatação do texto.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Define a cor para preencher a anotação.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Define o tamanho da fonte para OverlayText. O valor padrão é 10.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontSize |  | valor int |

### setOverlayText {#setOverlayText-java.lang.String-}
Define o texto a ser impresso na anotação de redação.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
Um array de números 8xN especificando as coordenadas da região de conteúdo que se destina a ser removida.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Define um array de pontos que especifica as coordenadas de n quadriláteros. Cada quadrilátero abrange uma palavra ou um grupo de palavras contíguas no texto subjacente à anotação.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

Se verdadeiro, o texto sobreposto será repetido na anotação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Define o alinhamento do Overlay Text.
