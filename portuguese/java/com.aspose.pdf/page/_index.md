---
title: "Page"
linktitle: "Page"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a página de um documento PDF."
type: docs
weight: 3310
url: /pt/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

Classe que representa a página de um documento PDF.

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita o objeto visitante {@code AnnotationSelector} que fornece funcionalidade para trabalhar com anotações. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Aceita o objeto visitante {@code ImagePlacementAbsorber} que fornece funcionalidade para trabalhar com objetos de posicionamento de imagem. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Aceita o objeto visitante {@code TextAbsorber} que fornece funcionalidade para trabalhar com objetos de texto. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Aceita o objeto visitante {@code TextFragmentAbsorber} que fornece funcionalidade para trabalhar com objetos de texto. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Adiciona gráficos à página. Funciona mais rápido do que adicionar elementos um a um com o método GraphicElement#addOnPage(Page). |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Adiciona gráficos à página. Funciona mais rápido do que adicionar elementos um a um com o método GraphicElement#addOnPage(Page). |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Insere um selo na página. O selo pode ser número de página, imagem ou texto simples, por exemplo, algum logotipo. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Converte a página atual em bitmap BMP e então retorna um array de bytes. |
| [asXml](#asXml--) | Converte a página atual em XML com codificação UTF-8. |
| [calculateContentBBox](#calculateContentBBox--) | Calcula o valor bbox – retângulo que contém o conteúdo sem margens visíveis. |
| [clearContents](#clearContents--) | Somente para uso interno |
| [close](#close--) | Fecha todos os recursos usados por este documento. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Converte a página para PNG para fluxo de imagem DSR, OMR, OCR. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Exclui gráficos da página. Funciona mais rápido do que excluir elementos um a um com o método {@link GraphicElement#remove}. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Libera memória. Este método está obsoleto, use close() em vez disso. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Retorna a lista de operadores que utilizam o recurso com o nome especificado. |
| [findReferences](#findReferences-java.lang.String-) | <p> Encontrar referências </p> |
| [flatten](#flatten--) | Remove todos os campos estáticos localizados na página e coloca seus valores no lugar. |
| [freeMemory](#freeMemory--) | Limpa os dados em cache |
| [getActions](#getActions--) | Obtém a coleção de propriedades da página. |
| [getAnnotations](#getAnnotations--) | Obtém a coleção de anotações da página. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Obtém a caixa de arte da página. </p> |
| [getArtifacts](#getArtifacts--) | Obtém a coleção de artefatos na página. |
| [getBackground](#getBackground--) | Obtém a cor de fundo da página. |
| [getBackgroundImage](#getBackgroundImage--) | Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchido ao ler o documento). |
| [getBleedBox](#getBleedBox--) | <p> Obtém a caixa de sangramento da página. </p> |
| [getColorType](#getColorType--) | Obtém o tipo de cor das páginas com base nas informações obtidas dos operadores SetColor, imagens e formulários. |
| [getContents](#getContents--) | <p> Obtém a coleção de operadores no fluxo de conteúdo da página. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Obtém o adicionador de conteúdo atual. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Obtém a caixa de corte da página. </p> |
| [getDocument](#getDocument--) | Obter documento |
| [getDuration](#getDuration--) | <p> Obtém a duração de exibição da página. Este é o tempo em segundos que a página deve ser exibida durante a apresentação. Retorna -1 se a duração não estiver definida. </p> <hr> Exemplo demonstra como obter a duração da página <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | Somente para uso interno |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Obtém a lista de objetos Field em ordem de tabulação nesta página. |
| [getFooter](#getFooter--) | Obtém o rodapé da página. |
| [getGroup](#getGroup--) | Obtém uma classe de atributos de grupo que especifica os atributos do grupo de páginas da página para uso no modelo de imagem transparente. |
| [getHeader](#getHeader--) | Obtém o cabeçalho da página. |
| [getLayers](#getLayers--) | Obtém a coleção de camadas. |
| [getMediaBox](#getMediaBox--) | <p> Obtém a caixa de mídia da página. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Obtém o estilo de linha para notas. (apenas para gerador, não preenchido ao ler o documento) |
| [getNotifications](#getNotifications--) | Retorna notificações sobre operações internas com o conteúdo da página. (Apenas notificações sobre eventos de parágrafo em cenários de adição de texto são suportadas atualmente.) |
| [getNumber](#getNumber--) | Obter número da página. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Evento para personalizar cabeçalho e rodapé. |
| [getPageInfo](#getPageInfo--) | Obtém as informações da página. (apenas para gerador, não preenchido ao ler o documento). |
| [getPageRect](#getPageRect-boolean-) | Retorna o retângulo da página de acordo com sua CropBox (ou MediaBox se CropBox for nula). |
| [getParagraphs](#getParagraphs--) | Obtém os parágrafos. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Retorna o retângulo da página de acordo com sua CropBox e MediaBox; </p> Internal |
| [getRect](#getRect--) | <p> Retorna o retângulo da página de acordo com sua CropBox e MediaBox; Para obter: a caixa de corte da página é retornada se especificada, caso contrário a caixa de mídia da página é retornada. Para definir: a caixa de mídia da página é sempre definida. </p> |
| [getResources](#getResources--) | Recupera os recursos associados à página. |
| [getResourcesField](#getResourcesField--) | <p> Obtém os recursos da página. O objeto Resources contém coleções de imagens, formulários e fontes. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Obtém a rotação da página. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Obtém a matriz de transformação da página. |
| [getTabOrder](#getTabOrder--) | Obtém a ordem de tabulação da página. Valores possíveis: Row, Column. Padrão, Manual |
| [getTocInfo](#getTocInfo--) | Obtém informações do índice. |
| [getTrimBox](#getTrimBox--) | <p> Obtém a caixa de corte da página. </p> |
| [getUserUnit](#getUserUnit--) | Obtém ou define o valor UserUnit. Um número positivo que indica o tamanho das unidades de espaço do usuário padrão, em múltiplos de 1/72 polegada. O valor padrão é 1. Defina zero ou um valor negativo para limpar esta entrada na página. |
| [getWatermark](#getWatermark--) | Obtém a marca d'água da página. |
| [hasVectorGraphics](#hasVectorGraphics--) | Detecta a presença de gráficos vetoriais, se estiver presente na página. |
| [intToRotation](#intToRotation-int-) | Traduz o valor inteiro para o membro correspondente da enumeração de rotação. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Obtém ou define a adição de parágrafos após o último parágrafo da página. Valor: O valor indica se os parágrafos serão adicionados após o último parágrafo da página. Os parágrafos serão adicionados após o último parágrafo da página se o valor for verdadeiro. |
| [isBlank](#isBlank-double-) | Obtém o sinalizador que indica se a página está em branco ou não. |
| [isBlank](#isBlank-double-boolean-) | Obtém o sinalizador que indica se a página está em branco ou não. |
| [makeGrayscale](#makeGrayscale--) | Converte a página para tons de cinza. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Mescla todas as camadas da página em uma única camada com o nome da nova camada especificado. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Mescla todas as camadas da página em uma única camada com o nome da nova camada especificado e o Id opcional do grupo de conteúdo. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Remover referências de objeto |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Remover referências ao XObject do conteúdo da página (ou seja, todos os operadores Do que utilizam o nome do objeto). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Redimensiona a página. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Traduz o membro da enumeração de rotação para um valor inteiro. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Envia a página para processamento com o dispositivo de página fornecido. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Envia a página para processamento com o dispositivo de página fornecido. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Obtém ou define a adição de parágrafos após o último parágrafo da página. Valor: O valor indica se os parágrafos serão adicionados após o último parágrafo da página. Os parágrafos serão adicionados após o último parágrafo da página se o valor for verdadeiro. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Define a caixa de arte da página. |
| [setBackground](#setBackground-java.awt.Color-) | Define a cor de fundo da página. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Define a cor de fundo da página. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchido ao ler o documento). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Define a caixa de sangria da página. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Define a caixa de corte da página. </p> <hr> <pre> Exemplo demonstra como obter a caixa de corte da página: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Define a duração de exibição da página. Este é o tempo em segundos que a página será exibida durante a apresentação. Retorna -1 se a duração não estiver definida. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Somente para uso interno |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Define o rodapé da página. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Define uma classe de atributos de grupo que especifica os atributos do grupo de página da página para uso no modelo de imagem transparente. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Define o cabeçalho da página. |
| [setLayers](#setLayers-java.util.ArrayList-) | Define a coleção de camadas. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Define a coleção de camadas. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Define a caixa de mídia da página. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Define o estilo de linha para notas.(apenas para gerador, não preenchido ao ler o documento) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Define as informações da página.(apenas para gerador, não preenchido ao ler o documento). |
| [setPageSize](#setPageSize-double-double-) | Define o tamanho da página. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Define os parágrafos. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Obtém ou define o retângulo da página. Para obter: a caixa de recorte da página é retornada se especificada, caso contrário a caixa de mídia da página é retornada. Para definir: a caixa de mídia da página é sempre definida. Note que esta propriedade não considera a rotação da página. Para obter o retângulo da página considerando a rotação, use ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Define a rotação da página. |
| [setTabOrder](#setTabOrder-int-) | Define a ordem de tabulação da página. Valores possíveis: Row, Column. Padrão, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | Define as informações do índice. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Definir transição |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Define a caixa de corte da página. |
| [setUserUnit](#setUserUnit-double-) | Obtém ou define o valor UserUnit. Um número positivo que indica o tamanho das unidades de espaço do usuário padrão, em múltiplos de 1/72 polegada. O valor padrão é 1. Defina zero ou um valor negativo para limpar esta entrada na página. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Define a marca d'água da página. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Tenta salvar gráficos vetoriais se estiverem presentes na página. O formato de salvamento é SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita o objeto visitante {@code AnnotationSelector} que fornece funcionalidade para trabalhar com anotações.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Aceita o objeto visitante {@code ImagePlacementAbsorber} que fornece funcionalidade para trabalhar com objetos de posicionamento de imagem.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Aceita o objeto visitante {@code TextAbsorber} que fornece funcionalidade para trabalhar com objetos de texto.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Aceita o objeto visitante {@code TextFragmentAbsorber} que fornece funcionalidade para trabalhar com objetos de texto.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Adiciona gráficos à página. Funciona mais rápido do que adicionar elementos um a um com o método GraphicElement#addOnPage(Page).

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Adiciona gráficos à página. Funciona mais rápido do que adicionar elementos um a um com o método GraphicElement#addOnPage(Page).

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Adiciona uma imagem pesquisável à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Adiciona uma imagem à página e a posiciona no centro do retângulo especificado, preservando a proporção da imagem.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Insere um selo na página. O selo pode ser número de página, imagem ou texto simples, por exemplo, algum logotipo.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Converte a página atual em bitmap BMP e então retorna um array de bytes.

### asXml {#asXml--}
```
public String asXml()
```

Converte a página atual em XML com codificação UTF-8.

**Returns:**
String XML convertida.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

Calcula o valor bbox – retângulo que contém o conteúdo sem margens visíveis.

**Returns:**
Valor Bbox - retângulo contendo o conteúdo sem margens visíveis

### clearContents {#clearContents--}
```
public void clearContents()
```

Somente para uso interno

### close {#close--}
```
public void close()
```

Fecha todos os recursos usados por este documento.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Converte a página para PNG para fluxo de imagem DSR, OMR, OCR.

**Returns:**
Fluxo de imagem em array byte[].

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Exclui gráficos da página. Funciona mais rápido do que excluir elementos um a um com o método {@link GraphicElement#remove}.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libera memória. Este método está obsoleto, use close() em vez disso.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Retorna a lista de operadores que utilizam o recurso com o nome especificado.

### findReferences {#findReferences-java.lang.String-}
<p> Encontrar referências </p>

### flatten {#flatten--}
```
public void flatten()
```

Remove todos os campos estáticos localizados na página e coloca seus valores no lugar.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Limpa os dados em cache

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Obtém a coleção de propriedades da página.

**Returns:**
Valor PageActionCollection

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Obtém a coleção de anotações da página. {@code Annotations}

**Returns:**
Valor AnnotationCollection

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Obtém a caixa de arte da página. </p>

**Returns:**
Valor Rectangle <hr> <pre> Exemplo demonstra como obter a caixa de arte da página: Document document = new Document(\"sample.pdf\"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Obtém a coleção de artefatos na página.

**Returns:**
Valor ArtifactCollection

### getBackground {#getBackground--}
```
public Color getBackground()
```

Obtém a cor de fundo da página.

**Returns:**
Valor da cor

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchido ao ler o documento).

**Returns:**
Instância de imagem

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Obtém a caixa de sangramento da página. </p>

**Returns:**
Valor Rectangle <hr> <pre> Exemplo demonstra como obter a caixa de sangria da página: Document document = new Document(\"sample.pdf\"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Obtém o tipo de cor das páginas com base nas informações obtidas dos operadores SetColor, imagens e formulários.

**Returns:**
Elemento ColorType @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Obtém a coleção de operadores no fluxo de conteúdo da página. {@code OperatorCollection} </p>

**Returns:**
Objeto OperatorCollection <hr> <pre> Exemplo demonstra como percorrer o fluxo de operadores da página. Document document = new Document(\"sample.pdf\"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Obtém o adicionador de conteúdo atual. {@code ContentsAppender}

**Returns:**
ContentsAppender valor

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Obtém a caixa de corte da página. </p>

**Returns:**
Rectangle valor <hr> <pre> Exemplo demonstra como obter a caixa de corte da página: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obter documento

**Returns:**
objeto IDocument

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Obtém a duração de exibição da página. Este é o tempo em segundos que a página deve ser exibida durante a apresentação. Retorna -1 se a duração não estiver definida. </p> <hr> Exemplo demonstra como obter a duração da página <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
valor double

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

Somente para uso interno

**Returns:**
instância interna

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Obtém a lista de objetos Field em ordem de tabulação nesta página.

**Returns:**
Lista de objetos de campo

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Obtém o rodapé da página.

**Returns:**
O Footer da página.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Obtém uma classe de atributos de grupo que especifica os atributos do grupo de páginas da página para uso no modelo de imagem transparente.

**Returns:**
Group valor

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Obtém o cabeçalho da página.

**Returns:**
O header da página.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Obtém a coleção de camadas.

**Returns:**
Valor: A coleção de layers.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Obtém a caixa de mídia da página. </p>

**Returns:**
Rectangle valor <hr> <pre> Exemplo demonstra como obter a caixa de mídia da página: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Obtém o estilo de linha para notas. (apenas para gerador, não preenchido ao ler o documento)

**Returns:**
GraphInfo valor

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Retorna notificações sobre operações internas com o conteúdo da página. (Apenas notificações sobre eventos de parágrafo em cenários de adição de texto são suportadas atualmente.)

**Returns:**
String representando notificações sobre operações internas com o conteúdo da página.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Obter número da página.

**Returns:**
valor int

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Evento para personalizar cabeçalho e rodapé.

**Returns:**
{@code PdfEvent<BeforePageGenerate> instância}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtém as informações da página. (apenas para gerador, não preenchido ao ler o documento).

**Returns:**
As informações da página.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Retorna o retângulo da página de acordo com sua CropBox (ou MediaBox se CropBox for nula).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| considerRotation |  | Se verdadeiro, então a rotação da página será considerada no cálculo do rect. |

**Returns:**
Rectangle da página.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtém os parágrafos.

**Returns:**
Os parágrafos.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Retorna o retângulo da página de acordo com sua CropBox e MediaBox; </p> Internal

**Returns:**
Rectangle valor <hr> <pre> Exemplo demonstra como obter o retângulo da página: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Retorna o retângulo da página de acordo com sua CropBox e MediaBox; Para obter: a caixa de corte da página é retornada se especificada, caso contrário a caixa de mídia da página é retornada. Para definir: a caixa de mídia da página é sempre definida. </p>

**Returns:**
Rectangle valor <hr> <pre> Exemplo demonstra como obter o retângulo da página: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Recupera os recursos associados à página.

**Returns:**
Um {@code Resources}({@link #getResources()}) objeto representando os recursos da página.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Obtém os recursos da página. O objeto Resources contém coleções de imagens, formulários e fontes. {@code Resources} </p>

**Returns:**
Resources valor <hr> <pre> Exemplo demonstra varredura das imagens da página: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Obtém a rotação da página. </p>

**Returns:**
Rotation elemento <hr> <pre> Exemplo demonstra como determinar a rotação da página. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Obtém a matriz de transformação da página.

**Returns:**
Matrix valor

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Obtém a ordem de tabulação da página. Valores possíveis: Row, Column. Padrão, Manual

**Returns:**
TabOrder valor @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

Obtém informações do índice.

**Returns:**
A informação do índice - padrão null. Se for definido, esta página conterá o índice.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Obtém a caixa de corte da página. </p>

**Returns:**
Rectangle valor <hr> <pre> Exemplo demonstra como obter a caixa de recorte da página: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

Obtém ou define o valor UserUnit. Um número positivo que indica o tamanho das unidades de espaço do usuário padrão, em múltiplos de 1/72 polegada. O valor padrão é 1. Defina zero ou um valor negativo para limpar esta entrada na página.

**Returns:**
valor double

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Obtém a marca d'água da página.

**Returns:**
Watermark valor

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Detecta a presença de gráficos vetoriais, se estiver presente na página.

**Returns:**
True se a página contém operadores de construção de caminho; caso contrário, False.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Traduz o valor inteiro para o membro correspondente da enumeração de rotação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rotação |  | Valor inteiro a converter |

**Returns:**
Membro da enumeração Rotation @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Obtém ou define a adição de parágrafos após o último parágrafo da página. Valor: O valor indica se os parágrafos serão adicionados após o último parágrafo da página. Os parágrafos serão adicionados após o último parágrafo da página se o valor for verdadeiro.

**Returns:**
valor booleano

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Obtém o sinalizador que indica se a página está em branco ou não.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fillThresholdFactor |  | O valor de limiar de preenchimento que controla a sensibilidade da detecção. Deve estar no intervalo [0..1). Para determinar se uma página está vazia ou não, a razão entre o espaço preenchido e o espaço total da página é calculada. Essa razão é comparada com o parâmetro fillThresholdFactor e, se for menor, a página é considerada vazia. |

**Returns:**
valor booleano True - se a página estiver em branco; caso contrário, false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Obtém o sinalizador que indica se a página está em branco ou não.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fillThresholdFactor |  | O valor de limiar de preenchimento que controla a sensibilidade da detecção. Deve ser igual ou maior que 0,01. |
| parseWhiteContent |  | True para varredura completa da página com análise de conteúdo branco, False (padrão) - algoritmo rápido, onde gráficos brancos são contados como página não em branco. |

**Returns:**
valor booleano True - se a página estiver em branco; caso contrário, false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Converte a página para tons de cinza.

### mergeLayers {#mergeLayers-java.lang.String-}
Mescla todas as camadas da página em uma única camada com o nome da nova camada especificado.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Mescla todas as camadas da página em uma única camada com o nome da nova camada especificado e o Id opcional do grupo de conteúdo.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Remover referências de objeto

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Remover referências ao XObject do conteúdo da página (ou seja, todos os operadores Do que utilizam o nome do objeto).

### resize {#resize-com.aspose.pdf.PageSize-}
Redimensiona a página.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Traduz o membro da enumeração de rotação para um valor inteiro.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Envia a página para processamento com o dispositivo de página fornecido.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Envia a página para processamento com o dispositivo de página fornecido.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Obtém ou define a adição de parágrafos após o último parágrafo da página. Valor: O valor indica se os parágrafos serão adicionados após o último parágrafo da página. Os parágrafos serão adicionados após o último parágrafo da página se o valor for verdadeiro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Define a caixa de arte da página.

### setBackground {#setBackground-java.awt.Color-}
Define a cor de fundo da página.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Define a cor de fundo da página.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtém ou define a imagem de fundo da página (apenas para gerador, não preenchido ao ler o documento).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Define a caixa de sangria da página.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Define a caixa de corte da página. </p> <hr> <pre> Exemplo demonstra como obter a caixa de corte da página: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Define a duração de exibição da página. Este é o tempo em segundos que a página será exibida durante a apresentação. Retorna -1 se a duração não estiver definida.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | duração da exibição da página. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
Somente para uso interno

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Define o rodapé da página.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Define uma classe de atributos de grupo que especifica os atributos do grupo de página da página para uso no modelo de imagem transparente.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Define o cabeçalho da página.

### setLayers {#setLayers-java.util.ArrayList-}
Define a coleção de camadas.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Define a coleção de camadas.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Define a caixa de mídia da página.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Define o estilo de linha para notas.(apenas para gerador, não preenchido ao ler o documento)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Define as informações da página.(apenas para gerador, não preenchido ao ler o documento).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Define o tamanho da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Largura da página. |
| altura |  | Tamanho da página. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Define os parágrafos.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Obtém ou define o retângulo da página. Para obter: a caixa de recorte da página é retornada se especificada, caso contrário a caixa de mídia da página é retornada. Para definir: a caixa de mídia da página é sempre definida. Note que esta propriedade não considera a rotação da página. Para obter o retângulo da página considerando a rotação, use ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Define a rotação da página.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Define a ordem de tabulação da página. Valores possíveis: Row, Column. Padrão, Manual

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Objeto TabOrder @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
Define as informações do índice.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Definir transição

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Define a caixa de corte da página.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

Obtém ou define o valor UserUnit. Um número positivo que indica o tamanho das unidades de espaço do usuário padrão, em múltiplos de 1/72 polegada. O valor padrão é 1. Defina zero ou um valor negativo para limpar esta entrada na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Define a marca d'água da página.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Tenta salvar gráficos vetoriais se estiverem presentes na página. O formato de salvamento é SVG.
