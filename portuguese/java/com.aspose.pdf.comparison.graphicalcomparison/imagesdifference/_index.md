---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe de resultado da comparação de duas páginas PDF."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Representa a classe de resultado da comparação de duas páginas PDF.

## Métodos

| Método | Descrição |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Converte o array de diferenças em uma imagem bitmap usando as cores especificadas. |
| [dispose](#dispose--) | Executa quaisquer operações de limpeza necessárias antes que o objeto seja destruído. |
| [getDestinationImage](#getDestinationImage--) | Retorna um novo bitmap que representa a imagem de destino ao aplicar o array de diferenças na imagem de origem. |
| [getDifference](#getDifference--) | Obtém o array de diferenças. Este array é semelhante ao array de dados da imagem original obtido como resultado do método LockBits. |
| [getHeight](#getHeight--) | A altura da diferença. |
| [getSourceImage](#getSourceImage--) | Obtém a imagem da primeira página comparada. A imagem tem um formato de pixel de 24bpp. |
| [getStride](#getStride--) | O stride dos dados da imagem de diferença. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Converte o array de diferenças em uma imagem bitmap usando as cores especificadas.

### dispose {#dispose--}
```
public final void dispose()
```

Executa quaisquer operações de limpeza necessárias antes que o objeto seja destruído.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Retorna um novo bitmap que representa a imagem de destino ao aplicar o array de diferenças na imagem de origem.

**Returns:**
Uma imagem de destino.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Obtém o array de diferenças. Este array é semelhante ao array de dados da imagem original obtido como resultado do método LockBits.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

A altura da diferença.

**Returns:**
valor int

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Obtém a imagem da primeira página comparada. A imagem tem um formato de pixel de 24bpp.

**Returns:**
BufferedImage instance

### getStride {#getStride--}
```
public final int getStride()
```

O stride dos dados da imagem de diferença.

**Returns:**
valor int
