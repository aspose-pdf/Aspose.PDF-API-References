---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma anotação de texto livre que exibe texto diretamente na página. Ao contrário de uma anotação de texto comum, uma anotação de texto livre não possui estado aberto ou fechado; em vez disso."
type: docs
weight: 1790
url: /pt/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Representa uma anotação de texto livre que exibe texto diretamente na página. Ao contrário de uma anotação de texto comum, uma anotação de texto livre não tem estado aberto ou fechado; em vez de ser exibida em uma janela pop-up, o texto está sempre visível.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Construtor a ser usado com Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Cria uma nova anotação FreeText na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getCallout](#getCallout--) | Array de ponto que especifica a linha de chamada. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtém a string de aparência padrão a ser usada na formatação do texto. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | Objeto que representa a aparência padrão da anotação FreeText. |
| [getDefaultStyle](#getDefaultStyle--) | Obtém uma string de estilo padrão. |
| [getEndingStyle](#getEndingStyle--) | Obtém o estilo de terminação de linha para o ponto de terminação da linha. |
| [getIntent](#getIntent--) | Obtém a intenção da anotação de texto livre. |
| [getJustification](#getJustification--) | Obtém um código que especifica a forma de justificação (quadding) a ser usada na exibição do texto da anotação. |
| [getRotate](#getRotate--) | Ângulo da rotação da anotação. |
| [getStartingStyle](#getStartingStyle--) | Obtém ou define o estilo de terminação de linha para o ponto de terminação da linha. Esta propriedade está obsoleta, por favor use EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | Retângulo que descreve as diferenças numéricas entre dois retângulos: a entrada Rect da anotação e um retângulo contido dentro desse retângulo. O retângulo interno é onde o texto da anotação deve ser exibido. |
| [getTextStyle](#getTextStyle--) | Obtém ou define o estilo do texto na aparência. Quando o estilo do texto é alterado, a aparência do texto é atualizada. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Array de ponto que especifica a linha de chamada. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Define a string de aparência padrão a ser usada na formatação do texto. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Define uma string de estilo padrão. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Define o estilo de terminação de linha para o ponto de terminação da linha. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Define a intenção da anotação de texto livre. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Define um código que especifica a forma de justificação (quadding) a ser usada na exibição do texto da anotação. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Ângulo da rotação da anotação. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Obtém ou define o estilo de terminação de linha para o ponto de terminação da linha. Esta propriedade está obsoleta, por favor use EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Retângulo que descreve as diferenças numéricas entre dois retângulos: a entrada Rect da anotação e um retângulo contido dentro desse retângulo. O retângulo interno é onde o texto da anotação deve ser exibido. |
| [setTextStyle](#setTextStyle-int-int-int-) | Define a formatação determinada pelo parâmetro textStyle para um fragmento de texto do índice fromInd ao índice toInd. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | Define a formatação determinada pelo parâmetro textStyle para todo o texto da anotação. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Define o estilo do texto na aparência. Quando o estilo do texto é alterado, a aparência do texto é atualizada. |
| [updateAppearance](#updateAppearance--) | Atualiza a Aparência, após o texto ter sido alterado/movido. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Construtor a ser usado com Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Cria uma nova anotação FreeText na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
valor int

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Array de ponto que especifica a linha de chamada.

**Returns:**
array de Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Obtém a string de aparência padrão a ser usada na formatação do texto.

**Returns:**
valor String

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

Objeto que representa a aparência padrão da anotação FreeText.

**Returns:**
objeto DefaultAppearance

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Obtém uma string de estilo padrão.

**Returns:**
valor String

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtém o estilo de terminação de linha para o ponto de terminação da linha.

**Returns:**
valor LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Obtém a intenção da anotação de texto livre.

**Returns:**
valor int @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Obtém um código que especifica a forma de justificação (quadding) a ser usada na exibição do texto da anotação.

**Returns:**
valor int @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Ângulo da rotação da anotação.

**Returns:**
elemento Rotation @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Obtém ou define o estilo de terminação de linha para o ponto de terminação da linha. Esta propriedade está obsoleta, por favor use EndingStyle.

**Returns:**
elemento LineEnding

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Retângulo que descreve as diferenças numéricas entre dois retângulos: a entrada Rect da anotação e um retângulo contido dentro desse retângulo. O retângulo interno é onde o texto da anotação deve ser exibido.

**Returns:**
Instância de Rectangle

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Obtém ou define o estilo do texto na aparência. Quando o estilo do texto é alterado, a aparência do texto é atualizada.

**Returns:**
valor TextStyle

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Array de ponto que especifica a linha de chamada.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Define a string de aparência padrão a ser usada na formatação do texto.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Define uma string de estilo padrão.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Define o estilo de terminação de linha para o ponto de terminação da linha.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Define a intenção da anotação de texto livre.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Define um código que especifica a forma de justificação (quadding) a ser usada na exibição do texto da anotação.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Ângulo da rotação da anotação.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Obtém ou define o estilo de terminação de linha para o ponto de terminação da linha. Esta propriedade está obsoleta, por favor use EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Retângulo que descreve as diferenças numéricas entre dois retângulos: a entrada Rect da anotação e um retângulo contido dentro desse retângulo. O retângulo interno é onde o texto da anotação deve ser exibido.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

Define a formatação determinada pelo parâmetro textStyle para um fragmento de texto do índice fromInd ao índice toInd.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fromInd |  | Índice inicial do fragmento de texto (a partir de 0). |
| toInd |  | Índice final do fragmento de texto (contando a partir de 0, este não está incluído). |
| textStyles |  | Estilo(s) aplicados ao fragmento de texto. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
Define a formatação determinada pelo parâmetro textStyle para todo o texto da anotação.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Define o estilo do texto na aparência. Quando o estilo do texto é alterado, a aparência do texto é atualizada.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Atualiza a Aparência, após o texto ter sido alterado/movido.
