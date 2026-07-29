---
title: "Annotation"
linktitle: "Annotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa um objeto de anotação."
type: docs
weight: 60
url: /pt/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Classe que representa um objeto de anotação.

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita visitante para processamento de anotações. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Atualiza parâmetros e aparência, de acordo com a transformação de matriz. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Somente para uso interno |
| [flatten](#flatten--) | Coloca o conteúdo da anotação diretamente na página, o objeto de anotação será removido. |
| [getActiveState](#getActiveState--) | Obtém o estado atual de aparência da anotação. |
| [getAlignment](#getAlignment--) | ff / * / * Retorna o nome do estado "checked" de acordo com os nomes de estado existentes. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getAppearance](#getAppearance--) | Obtém o dicionário de aparência da anotação. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Obtém o índice da página (baseado em 1) onde a anotação deve aparecer. |
| [getBorder](#getBorder--) | Obtém as características da borda da anotação. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Obtém as características da anotação. |
| [getColor](#getColor--) | Obtém a cor da anotação. |
| [getContents](#getContents--) | Obtém o texto da anotação. |
| [getEngineDict](#getEngineDict--) | Somente interno |
| [getEngineObj](#getEngineObj--) | Somente para uso interno |
| [getFlags](#getFlags--) | Obtém os sinalizadores da anotação. |
| [getFullName](#getFullName--) | Obtém o nome totalmente qualificado da anotação. |
| [getHeight](#getHeight--) | Obtém a altura da anotação. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Obtém ou define o alinhamento de texto para a anotação. |
| [getModified](#getModified--) | Obtém a data e hora em que a anotação foi modificada recentemente. |
| [getModifiedInternal](#getModifiedInternal--) | Obtém a data e hora em que a anotação foi modificada recentemente. |
| [getName](#getName--) | Obtém o nome da anotação na página. |
| [getNormalAppearance](#getNormalAppearance--) | Obtém a aparência normal. |
| [getPage](#getPage--) | Obtém o objeto de página ao qual esta anotação está associada. |
| [getPageIndex](#getPageIndex--) | Obtém o índice da página que contém a anotação. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Obtém o índice da página que contém a anotação. |
| [getPdfActions](#getPdfActions--) | Obtém a lista de ações da anotação. |
| [getRect](#getRect--) | Obtém o retângulo da anotação. |
| [getRectangle](#getRectangle-boolean-) | Retorna o retângulo da anotação levando em consideração a rotação da página. |
| [getStates](#getStates--) | Obtém o dicionário de aparência da anotação. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Obtém o alinhamento de texto para a anotação. |
| [getWidth](#getWidth--) | Obtém a largura da anotação. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Inicialização da instância |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | Se verdadeiro, a aparência da anotação será atualizada antes de converter o documento PDF em imagem. Isso permite converter os campos corretamente, mas provavelmente exigirá mais tempo. |
| [isUseFontSubset](#isUseFontSubset--) | Se esta propriedade for definida como verdadeira, as fontes serão adicionadas ao documento como subconjuntos. O valor padrão é verdadeiro. |
| [setActiveState](#setActiveState-java.lang.String-) | Define o estado atual da aparência da anotação. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Alinhamento da anotação. Esta propriedade está obsoleta. Use getHorizontalAlignment_Annotation_New em vez disso. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Define o índice da página (baseado em 1) onde a anotação deve aparecer. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Define as características da borda da anotação. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Define a cor da anotação. |
| [setContents](#setContents-java.lang.String-) | Define o texto da anotação. |
| [setFlags](#setFlags-int-) | Define os sinalizadores da anotação. |
| [setHeight](#setHeight-double-) | Define a altura da anotação. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Obtém ou define o alinhamento de texto para a anotação. |
| [setModified](#setModified-java.util.Date-) | Define a data e hora em que a anotação foi modificada recentemente. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Define a data e hora em que a anotação foi modificada recentemente. |
| [setName](#setName-java.lang.String-) | Define o nome da anotação na página. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Define o retângulo da anotação. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Define o alinhamento de texto da anotação. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | Se verdadeiro, a aparência da anotação será atualizada antes de converter o documento PDF em imagem. Isso permite converter os campos corretamente, mas provavelmente exigirá mais tempo. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | Se esta propriedade for definida como verdadeira, as fontes serão adicionadas ao documento como subconjuntos. O valor padrão é verdadeiro. |
| [setWidth](#setWidth-double-) | Define a largura da anotação. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita visitante para processamento de anotações.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Atualiza parâmetros e aparência, de acordo com a transformação de matriz.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
Somente para uso interno

### flatten {#flatten--}
```
public void flatten()
```

Coloca o conteúdo da anotação diretamente na página, o objeto de anotação será removido.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Obtém o estado atual de aparência da anotação.

**Returns:**
valor String

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Retorna o nome do estado "checked" de acordo com os nomes de estado existentes. / * / * / *

**Returns:**
Valor de string /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
valor int @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Obtém o dicionário de aparência da anotação.

**Returns:**
Objeto AppearanceDictionary

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Obtém o índice da página (baseado em 1) onde a anotação deve aparecer.

**Returns:**
o índice da página (baseado em 1) onde a anotação deve aparecer.

### getBorder {#getBorder--}
```
public Border getBorder()
```

Obtém as características da borda da anotação. {@code Border}

**Returns:**
Objeto Border

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Obtém as características da anotação.

**Returns:**
Objeto Characteristics

### getColor {#getColor--}
```
public Color getColor()
```

Obtém a cor da anotação.

**Returns:**
Objeto Color

### getContents {#getContents--}
```
public String getContents()
```

Obtém o texto da anotação.

**Returns:**
valor String

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Somente interno

**Returns:**
Objeto IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Somente para uso interno

**Returns:**
Objeto interno

### getFlags {#getFlags--}
```
public int getFlags()
```

Obtém os sinalizadores da anotação.

**Returns:**
Flags da anotação @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Obtém o nome totalmente qualificado da anotação.

**Returns:**
valor String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtém a altura da anotação.

**Returns:**
altura da anotação

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Obtém ou define o alinhamento de texto para a anotação.

**Returns:**
alinhamento de texto da anotação. @see HorizontalAlignment @deprecated Use TextHorizontalAlignment property

### getModified {#getModified--}
```
public Date getModified()
```

Obtém a data e hora em que a anotação foi modificada recentemente.

**Returns:**
data e hora em que a anotação foi modificada recentemente.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Obtém a data e hora em que a anotação foi modificada recentemente.

**Returns:**
objeto DateTime

### getName {#getName--}
```
public String getName()
```

Obtém o nome da anotação na página.

**Returns:**
valor String

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Obtém a aparência normal.

**Returns:**
objeto XForm

### getPage {#getPage--}
```
public Page getPage()
```

Obtém o objeto de página ao qual esta anotação está associada.

**Returns:**
objeto Page

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtém o índice da página que contém a anotação.

**Returns:**
valor int

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Obtém o índice da página que contém a anotação.

**Returns:**
valor int

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Obtém a lista de ações da anotação.

**Returns:**
instância PdfActionCollection

### getRect {#getRect--}
```
public Rectangle getRect()
```

Obtém o retângulo da anotação.

**Returns:**
objeto Rectangle

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Retorna o retângulo da anotação levando em consideração a rotação da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| considerRotation |  | Se true, a rotação da página é considerada. |

**Returns:**
objeto Rectangle

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Obtém o dicionário de aparência da anotação.

**Returns:**
Objeto AppearanceDictionary

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Obtém o alinhamento de texto para a anotação.

**Returns:**
alinhamento de texto da anotação. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém a largura da anotação.

**Returns:**
valor double, largura da anotação.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Inicialização da instância

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

Se verdadeiro, a aparência da anotação será atualizada antes de converter o documento PDF em imagem. Isso permite converter os campos corretamente, mas provavelmente exigirá mais tempo.

**Returns:**
valor booleano

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

Se esta propriedade for definida como verdadeira, as fontes serão adicionadas ao documento como subconjuntos. O valor padrão é verdadeiro.

**Returns:**
valor booleano

### setActiveState {#setActiveState-java.lang.String-}
Define o estado atual da aparência da anotação.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Alinhamento da anotação. Esta propriedade está obsoleta. Use getHorizontalAlignment_Annotation_New em vez disso.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Define o índice da página (baseado em 1) onde a anotação deve aparecer.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Define as características da borda da anotação. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Define a cor da anotação.

### setContents {#setContents-java.lang.String-}
Define o texto da anotação.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Define os sinalizadores da anotação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | flags da anotação @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Define a altura da anotação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | altura da anotação |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Obtém ou define o alinhamento de texto para a anotação.

### setModified {#setModified-java.util.Date-}
Define a data e hora em que a anotação foi modificada recentemente.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Define a data e hora em que a anotação foi modificada recentemente.

### setName {#setName-java.lang.String-}
Define o nome da anotação na página.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Define o retângulo da anotação.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Define o alinhamento de texto da anotação.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

Se verdadeiro, a aparência da anotação será atualizada antes de converter o documento PDF em imagem. Isso permite converter os campos corretamente, mas provavelmente exigirá mais tempo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

Se esta propriedade for definida como verdadeira, as fontes serão adicionadas ao documento como subconjuntos. O valor padrão é verdadeiro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Define a largura da anotação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | largura da anotação. |
