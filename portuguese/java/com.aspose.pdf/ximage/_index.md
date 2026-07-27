---
title: "XImage"
linktitle: "XImage"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o objeto de imagem X-Object."
type: docs
weight: 5610
url: /pt/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

Classe que representa o objeto de imagem X-Object.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | apenas para uso interno |

## Métodos

| Método | Descrição |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | Adiciona uma máscara de estêncil ao XImage. |
| [containsTransparency](#containsTransparency--) | Se a imagem contém transparência, retorna true; caso contrário, false. |
| [delete](#delete--) | Exclui a imagem da coleção pai. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Retorna o tipo de cor da imagem. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | Retorna uma lista de strings com Texto Alternativo para um XImage. |
| [getColorType](#getColorType--) | Retorna o tipo de cor da imagem. |
| [getEngineImg](#getEngineImg--) | Objeto IPdfImage que descreve a imagem. Apenas interno |
| [getFilterType](#getFilterType--) | Obtém o tipo de filtro da imagem. |
| [getGrayscaled](#getGrayscaled--) | Obtém a versão em tons de cinza da imagem. |
| [getHeight](#getHeight--) | Obtém a altura da imagem. |
| [getImage](#getImage--) | Apenas para uso interno |
| [getMetadata](#getMetadata--) | Metadados da imagem. |
| [getName](#getName--) | Obtém o nome da imagem. Observe que se você alterar o nome da imagem que tem referências no conteúdo da página, o documento pode ficar incorreto. Por favor, use o método XImage.Rename neste caso. |
| [getNameInCollection](#getNameInCollection--) | Retorna o nome da imagem em sua coleção. |
| [getRawBytes](#getRawBytes--) | Retorna bytes brutos da imagem sem decodificação. |
| [getRawImageData](#getRawImageData--) | Recupera os dados brutos da imagem da imagem de origem. |
| [getRawParameters](#getRawParameters--) | Obtém parâmetros brutos da imagem |
| [getWidth](#getWidth--) | Obtém a largura da imagem. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Retorna verdadeiro se o primitivo for uma imagem. |
| [isImageMask](#isImageMask--) | Obtém um sinalizador que indica se a imagem deve ser tratada como uma máscara de imagem (veja 8.9.6, "Masked Images"). Se esse sinalizador for verdadeiro, o valor de BitsPerComponent deverá ser 1 e Mask e ColorSpace não deverão ser especificados; áreas não mascaradas deverão ser pintadas usando a cor de preenchimento atual. Valor padrão: false. Valor: True indica que a imagem é máscara de imagem. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Retorna verdadeiro se ambas as imagens referenciam o mesmo objeto. |
| [rename](#rename-java.lang.String-) | Renomeia a imagem e substitui todas as referências à imagem pelo novo nome |
| [replace](#replace-java.io.InputStream-) | Substitui a imagem no fluxo especificado em {@code image}. * |
| [save](#save-java.io.OutputStream-) | Salva os dados da imagem no fluxo como imagem JPEG. |
| [save](#save-java.io.OutputStream-float-float-) | Salva a imagem no fluxo com o formato solicitado. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Salva a imagem no fluxo com o formato solicitado. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Salva a imagem no fluxo com o formato solicitado. |
| [save](#save-java.io.OutputStream-int-) | Salva a imagem no fluxo com o formato solicitado e resolução especificada. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Salva a imagem no fluxo com o formato solicitado. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Salva os dados da imagem no fluxo como imagem JPEG com resolução especificada. |
| [setName](#setName-java.lang.String-) | Define o nome da imagem. Observe que se você alterar o nome da imagem que tem referências no conteúdo da página, o documento pode ficar incorreto. Use o método XImage.Rename neste caso. |
| [toStream](#toStream--) | Retorna o fluxo original da imagem. |
| [toString](#toString--) | Retorna uma representação em string das propriedades do objeto XImage. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Define o texto alternativo para um XImage na página. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
apenas para uso interno

### addStencilMask {#addStencilMask-java.io.InputStream-}
Adiciona uma máscara de estêncil ao XImage.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

Se a imagem contém transparência, retorna true; caso contrário, false.

**Returns:**
valor booleano

### delete {#delete--}
```
public void delete()
```

Exclui a imagem da coleção pai.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Retorna o tipo de cor da imagem.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
Retorna uma lista de strings com Texto Alternativo para um XImage.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Retorna o tipo de cor da imagem.

**Returns:**
O valor do tipo de cor.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

Objeto IPdfImage que descreve a imagem. Apenas interno

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Obtém o tipo de filtro da imagem.

**Returns:**
Elemento ImageFilterType

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Obtém a versão em tons de cinza da imagem.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtém a altura da imagem.

**Returns:**
valor int

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

Apenas para uso interno

**Returns:**
Image

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Metadados da imagem.

**Returns:**
Instância de Metadata

### getName {#getName--}
```
public String getName()
```

Obtém o nome da imagem. Observe que se você alterar o nome da imagem que tem referências no conteúdo da página, o documento pode ficar incorreto. Por favor, use o método XImage.Rename neste caso.

**Returns:**
String

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Retorna o nome da imagem em sua coleção.

**Returns:**
Chave da imagem (nome).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Retorna bytes brutos da imagem sem decodificação.

**Returns:**
array de bytes

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Recupera os dados brutos da imagem da imagem de origem.

**Returns:**
Um {@link byte[]} contendo os dados originais da imagem.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Obtém parâmetros brutos da imagem

**Returns:**
Instância de RawParameters

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtém a largura da imagem.

**Returns:**
valor int

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
Retorna verdadeiro se o primitivo for uma imagem.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Obtém um sinalizador que indica se a imagem deve ser tratada como uma máscara de imagem (veja 8.9.6, "Masked Images"). Se esse sinalizador for verdadeiro, o valor de BitsPerComponent deverá ser 1 e Mask e ColorSpace não deverão ser especificados; áreas não mascaradas deverão ser pintadas usando a cor de preenchimento atual. Valor padrão: false. Valor: True indica que a imagem é máscara de imagem.

**Returns:**
valor booleano

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Retorna verdadeiro se ambas as imagens referenciam o mesmo objeto.

### rename {#rename-java.lang.String-}
Renomeia a imagem e substitui todas as referências à imagem pelo novo nome

### replace {#replace-java.io.InputStream-}
Substitui a imagem no fluxo especificado em {@code image}. *

### save {#save-java.io.OutputStream-}
Salva os dados da imagem no fluxo como imagem JPEG.

### save {#save-java.io.OutputStream-float-float-}
Salva a imagem no fluxo com o formato solicitado.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Salva a imagem no fluxo com o formato solicitado.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Salva a imagem no fluxo com o formato solicitado.

### save {#save-java.io.OutputStream-int-}
Salva a imagem no fluxo com o formato solicitado e resolução especificada.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Salva a imagem no fluxo com o formato solicitado.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Salva os dados da imagem no fluxo como imagem JPEG com resolução especificada.

### setName {#setName-java.lang.String-}
Define o nome da imagem. Observe que se você alterar o nome da imagem que tem referências no conteúdo da página, o documento pode ficar incorreto. Use o método XImage.Rename neste caso.

### toStream {#toStream--}
```
public InputStream toStream()
```

Retorna o fluxo original da imagem.

**Returns:**
O fluxo de imagem original.

### toString {#toString--}
```
public String toString()
```

Retorna uma representação em string das propriedades do objeto XImage.

**Returns:**
Instância de String

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Define o texto alternativo para um XImage na página.
