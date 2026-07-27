---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa características de uma imagem colocada na página de documento Pdf. </p> <hr> <pre> O exemplo demonstra como encontrar imagens na primeira página do documento PDF e obter imagens."
type: docs
weight: 2330
url: /pt/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
<p> Representa características de uma imagem colocada na página de documento Pdf. </p> <hr> <pre> O exemplo demonstra como encontrar imagens na primeira página do documento PDF e obter imagens como bitmaps com dimensões visíveis. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Quando uma imagem é colocada em uma página, ela pode ter dimensões diferentes das dimensões físicas definidas em {@code Resources}. O objeto {@code ImagePlacement} tem a finalidade de fornecer essas informações, como dimensões, resolução e assim por diante. </p>

```
public final class ImagePlacement extends Object
```

java.lang.Object, com.aspose.pdf.ImagePlacement

## Métodos

| Método | Descrição |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Obtém parâmetros de composição do estado gráfico ativo para a imagem colocada na página. |
| [getImage](#getImage--) | Obtém o objeto de recurso XImage relacionado. |
| [getMatrix](#getMatrix--) | Matriz de transformação atual para esta imagem. |
| [getOperator](#getOperator--) | Operador usado para exibir a imagem. |
| [getPage](#getPage--) | Obtém a página que contém a imagem. |
| [getRectangle](#getRectangle--) | Obtém o retângulo da Imagem. |
| [getResolution](#getResolution--) | Obtém a resolução da Imagem. |
| [getRotation](#getRotation--) | Obtém o ângulo de rotação da Imagem. |
| [hide](#hide--) | Excluir imagem da página. |
| [replace](#replace-java.io.InputStream-) | Substituir imagem na coleção por outra imagem. |
| [save](#save-java.io.OutputStream-) | Salva a imagem com as transformações correspondentes: dimensionamento, rotação e resolução. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Salva a imagem com as transformações correspondentes: dimensionamento, rotação e resolução. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Obtém parâmetros de composição do estado gráfico ativo para a imagem colocada na página.

**Returns:**
Objeto CompositingParameters

### getImage {#getImage--}
```
public XImage getImage()
```

Obtém o objeto de recurso XImage relacionado.

**Returns:**
objeto XImage

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Matriz de transformação atual para esta imagem.

**Returns:**
Objeto Matrix

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Operador usado para exibir a imagem.

**Returns:**
Instância de Operator

### getPage {#getPage--}
```
public Page getPage()
```

Obtém a página que contém a imagem.

**Returns:**
objeto Page

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo da Imagem.

**Returns:**
objeto Rectangle

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtém a resolução da Imagem.

**Returns:**
Objeto Resolution

### getRotation {#getRotation--}
```
public float getRotation()
```

Obtém o ângulo de rotação da Imagem.

**Returns:**
valor int

### hide {#hide--}
```
public final void hide()
```

Excluir imagem da página.

### replace {#replace-java.io.InputStream-}
Substituir imagem na coleção por outra imagem.

### save {#save-java.io.OutputStream-}
Salva a imagem com as transformações correspondentes: dimensionamento, rotação e resolução.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Salva a imagem com as transformações correspondentes: dimensionamento, rotação e resolução.
