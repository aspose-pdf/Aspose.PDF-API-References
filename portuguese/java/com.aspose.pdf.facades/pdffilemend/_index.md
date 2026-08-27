---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para adicionar textos e imagens nas páginas de um documento PDF existente."
type: docs
weight: 500
url: /pt/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Representa uma classe para adicionar textos e imagens nas páginas de um documento PDF existente.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Construtor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Construtor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Construtor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Construtor. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Construtor. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Construtor. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Construtor. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | Não implementado. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Não implementado. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Não implementado. |
| [close](#close--) | Fecha o objeto PdfFileMend. |
| [dispose](#dispose--) | Fecha o objeto PdfFileMend. Este método está obsoleto, use close() em vez disso. |
| [getDocument](#getDocument--) | Obtém o documento {@code PdfFileMend} em que está trabalhando. |
| [getInputFile](#getInputFile--) | Obtém o arquivo de entrada. |
| [getInputStream](#getInputStream--) | Obtém o fluxo de entrada. |
| [getOutputFile](#getOutputFile--) | Obtém o arquivo de saída. |
| [getOutputStream](#getOutputStream--) | Obtém o fluxo de saída. |
| [getTextPositioningMode](#getTextPositioningMode--) | Obtém a estratégia de posicionamento de texto. {@code PositioningMode} O modo padrão é Legacy. |
| [getWrapMode](#getWrapMode--) | Obtém o algoritmo de quebra de linha. |
| [save](#save-java.io.OutputStream-) | Salva o documento PDF no arquivo especificado. |
| [save](#save-java.lang.String-) | Salva o documento PDF no arquivo especificado. |
| [setInputFile](#setInputFile-java.lang.String-) | Obsoleto. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Define o fluxo de entrada. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Define o arquivo de saída. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Este método está obsoleto. Use o método Save(outputStream) para obter resultados da fachada. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Define a estratégia de posicionamento de texto. {@code PositioningMode} O modo padrão é Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | Define um valor booleano que indica quebra de linha nos métodos AddText. Se o valor for true, o texto em FormattedText será quebrado em linhas. Por padrão, o valor é false. |
| [setWrapMode](#setWrapMode-int-) | Define o algoritmo de quebra de linha. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

Construtor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
Construtor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Construtor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
Construtor.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
Construtor.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
Construtor.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
Construtor.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Adiciona imagem às páginas especificadas do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Adiciona imagem à página especificada do documento PDF nas coordenadas especificadas. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
Não implementado.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
Não implementado.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Não implementado.

### close {#close--}
```
public void close()
```

Fecha o objeto PdfFileMend.

### dispose {#dispose--}
```
public void dispose()
```

Fecha o objeto PdfFileMend. Este método está obsoleto, use close() em vez disso.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtém o documento {@code PdfFileMend} em que está trabalhando.

**Returns:**
objeto IDocument

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Obtém o arquivo de entrada.

**Returns:**
valor String

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Obtém o fluxo de entrada.

**Returns:**
fluxo de entrada.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Obtém o arquivo de saída.

**Returns:**
valor String

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Obtém o fluxo de saída.

**Returns:**
fluxo de saída.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Obtém a estratégia de posicionamento de texto. {@code PositioningMode} O modo padrão é Legacy.

**Returns:**
Elemento PositioningMode @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Obtém o algoritmo de quebra de linha.

**Returns:**
valor WordWrapMode @see WordWrapMode

### save {#save-java.io.OutputStream-}
Salva o documento PDF no arquivo especificado.

### save {#save-java.lang.String-}
Salva o documento PDF no arquivo especificado.

### setInputFile {#setInputFile-java.lang.String-}
Obsoleto.

### setInputStream {#setInputStream-java.io.InputStream-}
Define o fluxo de entrada.

### setOutputFile {#setOutputFile-java.lang.String-}
Define o arquivo de saída.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Este método está obsoleto. Use o método Save(outputStream) para obter resultados da fachada.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Define a estratégia de posicionamento de texto. {@code PositioningMode} O modo padrão é Legacy.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento PositioningMode @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

Define um valor booleano que indica quebra de linha nos métodos AddText. Se o valor for true, o texto em FormattedText será quebrado em linhas. Por padrão, o valor é false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Define o algoritmo de quebra de linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento WordWrapMode @see WordWrapMode |
