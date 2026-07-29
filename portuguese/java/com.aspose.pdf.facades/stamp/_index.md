---
title: "Carimbo"
linktitle: "Carimbo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe representando carimbo."
type: docs
weight: 700
url: /pt/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Classe representando carimbo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Stamp](#Stamp--) | Construtor para o objeto Stamp. |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Define a imagem que será usada como selo. |
| [bindImage](#bindImage-java.lang.String-) | <p> Define a imagem como um selo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Define o texto como selo. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> Define o arquivo PDF e o número da página que será usado como selo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> Define o arquivo PDF e o número da página que será usado como selo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Define o estado do texto do selo. |
| [close](#close--) | Fecha esta instância |
| [getBlendingSpace](#getBlendingSpace--) | Obtém um valor BlendingColorSpace que define um espaço de cor usado para executar operações de transparência e mesclagem na página. |
| [getOpacity](#getOpacity--) | Obtém a opacidade do selo. |
| [getPageNumber](#getPageNumber--) | Obtém o número da página. |
| [getPages](#getPages--) | Obtém um array com os números das páginas que serão afetadas pelo selo. |
| [getQuality](#getQuality--) | Obtém a qualidade do selo de imagem em porcentagem. Valores válidos 0..100%. |
| [getRotation](#getRotation--) | Obtém a rotação do selo em graus. |
| [getStampId](#getStampId--) | Obtém o identificador do selo. |
| [isBackground](#isBackground--) | Obtém o status de plano de fundo. Se verdadeiro, o selo será colocado como plano de fundo da página carimbada. Por padrão, está definido como falso. |
| [setBackground](#setBackground-boolean-) | Define o status de plano de fundo. Se verdadeiro, o selo será colocado como plano de fundo da página carimbada. Por padrão, está definido como falso. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Define um valor BlendingColorSpace que define um espaço de cor usado para executar operações de transparência e mesclagem na página. |
| [setImageSize](#setImageSize-float-float-) | Define o tamanho do selo de imagem. A imagem será dimensionada de acordo com os valores especificados. |
| [setOpacity](#setOpacity-float-) | Define a opacidade do selo. |
| [setOrigin](#setOrigin-float-float-) | Define a posição na página onde o selo será colocado. |
| [setPageNumber](#setPageNumber-int-) | Define o número da página. |
| [setPages](#setPages-int:A-) | <p> Define um array com os números das páginas que serão afetadas pelo selo. Se Pages = null, todas as páginas do documento são afetadas. </p> |
| [setQuality](#setQuality-int-) | Define a qualidade do selo de imagem em porcentagem. Valores válidos 0..100%. |
| [setRotation](#setRotation-float-) | <p> Obtém ou define a rotação do selo em graus. </p> |
| [setStampId](#setStampId-int-) | Define o identificador do selo. |

### Stamp {#Stamp--}
```
public Stamp()
```

Construtor para o objeto Stamp.

### bindImage {#bindImage-java.io.InputStream-}
Define a imagem que será usada como selo.

### bindImage {#bindImage-java.lang.String-}
<p> Define a imagem como um selo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Define o texto como selo.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> Define o arquivo PDF e o número da página que será usado como selo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> Define o arquivo PDF e o número da página que será usado como selo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Define o estado do texto do selo.

### close {#close--}
```
public void close()
```

Fecha esta instância

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Obtém um valor BlendingColorSpace que define um espaço de cor usado para executar operações de transparência e mesclagem na página.

**Returns:**
int valor @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Obtém a opacidade do selo.

**Returns:**
valor float

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Obtém o número da página.

**Returns:**
valor int

### getPages {#getPages--}
```
public int[] getPages()
```

Obtém um array com os números das páginas que serão afetadas pelo selo.

**Returns:**
array de int

### getQuality {#getQuality--}
```
public int getQuality()
```

Obtém a qualidade do selo de imagem em porcentagem. Valores válidos 0..100%.

**Returns:**
valor int

### getRotation {#getRotation--}
```
public float getRotation()
```

Obtém a rotação do selo em graus.

**Returns:**
valor float

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtém o identificador do selo.

**Returns:**
valor int

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Obtém o status de plano de fundo. Se verdadeiro, o selo será colocado como plano de fundo da página carimbada. Por padrão, está definido como falso.

**Returns:**
valor booleano

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Define o status de plano de fundo. Se verdadeiro, o selo será colocado como plano de fundo da página carimbada. Por padrão, está definido como falso.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Define um valor BlendingColorSpace que define um espaço de cor usado para executar operações de transparência e mesclagem na página.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Define o tamanho do selo de imagem. A imagem será dimensionada de acordo com os valores especificados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Largura da imagem. |
| altura |  | Altura da imagem. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Define a opacidade do selo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Define a posição na página onde o selo será colocado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| originX |  | Coordenada X do selo. |
| originY |  | Coordenada Y do selo. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Define o número da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Define um array com os números das páginas que serão afetadas pelo selo. Se Pages = null, todas as páginas do documento são afetadas. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | array de int <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Define a qualidade do selo de imagem em porcentagem. Valores válidos 0..100%.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Obtém ou define a rotação do selo em graus. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Define o identificador do selo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
