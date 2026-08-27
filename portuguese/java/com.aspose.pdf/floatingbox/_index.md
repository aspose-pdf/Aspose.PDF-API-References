---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um FloatingBox em um documento PDF. O FloatingBox tem posição personalizada."
type: docs
weight: 1610
url: /pt/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Representa um FloatingBox em um documento PDF. O FloatingBox tem posição personalizada.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Inicializa uma nova instância da classe {@code FloatingBox}. |
| [FloatingBox](#FloatingBox-float-float-) | Inicializa uma nova instância da classe {@code FloatingBox} com largura e altura especificadas. |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Clona um novo objeto {@code FloatingBox}. Parágrafos na caixa flutuante não são clonados. |
| [getBackgroundColor](#getBackgroundColor--) | Obtém um objeto que indica a cor de fundo da caixa flutuante. |
| [getBackgroundImage](#getBackgroundImage--) | Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchido ao ler o documento). |
| [getBorder](#getBorder--) | Obtém um objeto que indica as informações da borda da caixa flutuante. |
| [getColumnInfo](#getColumnInfo--) | Obtém informações de coluna |
| [getHeight](#getHeight--) | Obtém um valor float que indica a altura da caixa flutuante. |
| [getLeft](#getLeft--) | Obtém a coordenada esquerda da tabela. |
| [getPadding](#getPadding--) | Obtém um objeto que indica o preenchimento da caixa flutuante. |
| [getParagraphs](#getParagraphs--) | Obtém uma coleção que indica todos os parágrafos na célula. |
| [getPositioningMode](#getPositioningMode--) | Especifica a variante para determinar a localização da FloatingBox na página. |
| [getTop](#getTop--) | Obtém a coordenada superior da tabela. |
| [getWidth](#getWidth--) | Obtém um valor float que indica a largura da caixa flutuante. |
| [isNeedRepeating](#isNeedRepeating--) | Obtém um valor booleano que indica se o parágrafo precisa ser repetido na próxima página. O valor padrão é true. O atributo é válido somente quando o próprio parágrafo e o objeto ao qual seu ReferenceParagraphID se refere estão ambos incluídos em RepeatingRows. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Define um objeto que indica a cor de fundo da caixa flutuante. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchido ao ler o documento). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Define um objeto que indica as informações da borda da caixa flutuante. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Define informações de coluna |
| [setHeight](#setHeight-double-) | Define um valor float que indica a altura da caixa flutuante. |
| [setLeft](#setLeft-double-) | Define a coordenada esquerda da tabela. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Define um valor booleano que indica se o parágrafo precisa ser repetido na próxima página. O valor padrão é true. O atributo é válido somente quando o próprio parágrafo e o objeto ao qual seu ReferenceParagraphID se refere estão ambos incluídos em RepeatingRows. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Define um objeto que indica o preenchimento da caixa flutuante. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Define uma coleção que indica todos os parágrafos na célula. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Especifica a variante para determinar a localização da FloatingBox na página. |
| [setTop](#setTop-double-) | Define a coordenada superior da tabela. |
| [setWidth](#setWidth-double-) | Define um valor float que indica a largura da caixa flutuante. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Inicializa uma nova instância da classe {@code FloatingBox}.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Inicializa uma nova instância da classe {@code FloatingBox} com largura e altura especificadas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | A largura da caixa. |
| altura |  | A altura da caixa. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona um novo objeto {@code FloatingBox}. Parágrafos na caixa flutuante não são clonados.

**Returns:**
O novo objeto {@code FloatingBox}.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtém um objeto que indica a cor de fundo da caixa flutuante.

**Returns:**
objeto que indica a cor de fundo.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchido ao ler o documento).

**Returns:**
Instância de imagem

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtém um objeto que indica as informações da borda da caixa flutuante.

**Returns:**
objeto que indica as informações da borda.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Obtém informações de coluna

**Returns:**
objeto ColumnInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtém um valor float que indica a altura da caixa flutuante.

**Returns:**
valor que indica a altura.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtém a coordenada esquerda da tabela.

**Returns:**
coordenada esquerda da tabela.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Obtém um objeto que indica o preenchimento da caixa flutuante.

**Returns:**
objeto que indica o preenchimento.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtém uma coleção que indica todos os parágrafos na célula.

**Returns:**
coleção que indica todos os parágrafos.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Especifica a variante para determinar a localização da FloatingBox na página.

**Returns:**
elemento ParagraphPositioningMode

### getTop {#getTop--}
```
public double getTop()
```

Obtém a coordenada superior da tabela.

**Returns:**
coordenada superior da tabela.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém um valor float que indica a largura da caixa flutuante.

**Returns:**
valor double

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Obtém um valor booleano que indica se o parágrafo precisa ser repetido na próxima página. O valor padrão é true. O atributo é válido somente quando o próprio parágrafo e o objeto ao qual seu ReferenceParagraphID se refere estão ambos incluídos em RepeatingRows.

**Returns:**
valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Define um objeto que indica a cor de fundo da caixa flutuante.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchido ao ler o documento).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Define um objeto que indica as informações da borda da caixa flutuante.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Define informações de coluna

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Define um valor float que indica a altura da caixa flutuante.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor que indica a altura. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Define a coordenada esquerda da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | coordenada esquerda da tabela. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Define um valor booleano que indica se o parágrafo precisa ser repetido na próxima página. O valor padrão é true. O atributo é válido somente quando o próprio parágrafo e o objeto ao qual seu ReferenceParagraphID se refere estão ambos incluídos em RepeatingRows.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Define um objeto que indica o preenchimento da caixa flutuante.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Define uma coleção que indica todos os parágrafos na célula.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Especifica a variante para determinar a localização da FloatingBox na página.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Define a coordenada superior da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | coordenada superior da tabela. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Define um valor float que indica a largura da caixa flutuante.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |
