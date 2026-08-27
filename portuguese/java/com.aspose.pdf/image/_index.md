---
title: "Image"
linktitle: "Image"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma imagem."
type: docs
weight: 2280
url: /pt/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Representa uma imagem.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Image](#Image--) | construtor padrão |

## Métodos

| Método | Descrição |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | Tente converter para stream com imagem bmp/png/gif/tiff para stream com imagem no formato JPG. |
| [deepClone](#deepClone--) | Clone a imagem. |
| [getBitmapInfo](#getBitmapInfo--) | Obtém ou define os bytes da imagem descompactados. |
| [getBitmapSize](#getBitmapSize--) | Obtém o tamanho do bitmap da imagem. |
| [getBufferedImage](#getBufferedImage--) | Obtém a imagem java awt. |
| [getFile](#getFile--) | Obtém o arquivo da imagem. |
| [getFileType](#getFileType--) | Obtém o tipo de arquivo da imagem. |
| [getFixHeight](#getFixHeight--) | Obtém a altura da imagem. |
| [getFixWidth](#getFixWidth--) | Obtém a largura da imagem. |
| [getImageScale](#getImageScale--) | Obtém a escala da imagem. |
| [getImageStream](#getImageStream--) | Obtém o stream da imagem. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Retorna o tipo MIME da imagem. |
| [getTitle](#getTitle--) | Obtém um valor string que indica o título da imagem. |
| [isApplyResolution](#isApplyResolution--) | Obtém ou define um valor booleano que indica se a imagem usa resolução durante a geração. |
| [isBlackWhite](#isBlackWhite--) | Obtém um valor booleano que indica se a imagem é forçada a ser preto-e-branco. Se for usada uma imagem TIFF do subformato CCITT, esta propriedade deve ser definida como true. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Tenta detectar e usar codificação 1bpp para imagens em escala de cinza. Valor padrão == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | Obtém ou define um valor booleano que indica se a imagem usa resolução durante a geração. |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Obtém ou define os bytes da imagem descompactados. |
| [setBlackWhite](#setBlackWhite-boolean-) | Define um valor booleano que indica se a imagem é forçada a ser preto-e-branco. Se for usada uma imagem TIFF do subformato CCITT, esta propriedade deve ser definida como true. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Tenta detectar e usar codificação 1bpp para imagens em escala de cinza. Valor padrão == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Define a imagem java awt. |
| [setFile](#setFile-java.lang.String-) | Define o arquivo de imagem. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Define o tipo de arquivo de imagem. |
| [setFixHeight](#setFixHeight-double-) | Define a altura da imagem. |
| [setFixWidth](#setFixWidth-double-) | Define a largura da imagem. |
| [setImageScale](#setImageScale-double-) | Define a escala da imagem. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Define o fluxo da imagem. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Define um valor string que indica o título da imagem. |

### Image {#Image--}
```
public Image()
```

construtor padrão

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
Tente converter para stream com imagem bmp/png/gif/tiff para stream com imagem no formato JPG.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone a imagem.

**Returns:**
O objeto clonado

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Obtém ou define os bytes da imagem descompactados.

**Returns:**
instância BitmapInfo

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Obtém o tamanho do bitmap da imagem.

**Returns:**
Instância de Rectangle

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

Obtém a imagem java awt.

**Returns:**
objeto BufferedImage

### getFile {#getFile--}
```
public String getFile()
```

Obtém o arquivo da imagem.

**Returns:**
valor String

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Obtém o tipo de arquivo da imagem.

**Returns:**
valor int @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Obtém a altura da imagem.

**Returns:**
valor double

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Obtém a largura da imagem.

**Returns:**
valor double

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Obtém a escala da imagem.

**Returns:**
valor double

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Obtém o stream da imagem.

**Returns:**
objeto InputStream

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Retorna o tipo MIME da imagem.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Obtém um valor string que indica o título da imagem.

**Returns:**
valor TextFragment

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Obtém ou define um valor booleano que indica se a imagem usa resolução durante a geração.

**Returns:**
valor booleano

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Obtém um valor booleano que indica se a imagem é forçada a ser preto-e-branco. Se for usada uma imagem TIFF do subformato CCITT, esta propriedade deve ser definida como true.

**Returns:**
valor booleano

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Tenta detectar e usar codificação 1bpp para imagens em escala de cinza. Valor padrão == FALSE

**Returns:**
valor booleano

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Obtém ou define um valor booleano que indica se a imagem usa resolução durante a geração.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Obtém ou define os bytes da imagem descompactados.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Define um valor booleano que indica se a imagem é forçada a ser preto-e-branco. Se for usada uma imagem TIFF do subformato CCITT, esta propriedade deve ser definida como true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Tenta detectar e usar codificação 1bpp para imagens em escala de cinza. Valor padrão == FALSE

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| blackWhiteForGrayScale |  | valor booleano |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Define a imagem java awt.

### setFile {#setFile-java.lang.String-}
Define o arquivo de imagem.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Define o tipo de arquivo de imagem.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Define a altura da imagem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Define a largura da imagem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Define a escala da imagem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setImageStream {#setImageStream-java.io.InputStream-}
Define o fluxo da imagem.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Define um valor string que indica o título da imagem.
