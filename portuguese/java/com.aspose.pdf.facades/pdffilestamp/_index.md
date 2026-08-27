---
title: "PdfFileStamp"
linktitle: "PdfFileStamp"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe para adicionar carimbos (marca d'água ou plano de fundo) a arquivos PDF."
type: docs
weight: 540
url: /pt/java/com.aspose.pdf.facades/pdffilestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStamp, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStamp

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStamp extends SaveableFacade implements IPdfFileStamp
```

Classe para adicionar carimbos (marca d'água ou plano de fundo) a arquivos PDF.

## Campos

| Campo | Descrição |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Posição inferior esquerda. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Posição inferior central. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Posição inferior direita. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Posição esquerda. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Posição direita. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Posição superior esquerda. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Posição central superior. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Posição superior direita. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFileStamp](#PdfFileStamp--) | <p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-) | <p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-) | <p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-) | <p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-) | <p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-) | <p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStamp](#PdfFileStamp-java.lang.String-java.lang.String-boolean-) | <p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |

## Métodos

| Método | Descrição |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Adiciona rodapé às páginas do documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Adiciona rodapé às páginas do documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Adiciona imagem como rodapé da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(new FileInputStream(\"image.jpg\"), 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Adiciona imagem como rodapé da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(new FileInputStream(\"image.jpg\"), 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Adiciona imagem como rodapé às páginas do documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(\"image.jpg\", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Adiciona imagem como rodapé das páginas. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Adiciona cabeçalho à página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addHeader(new FormattedText(\"Head of the page\"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Adiciona cabeçalho às páginas do arquivo. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addHeader(new FormattedText(\"Head of the page\"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Adiciona imagem como cabeçalho nas páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(new FileInputStream(\"image.jpg\"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Adiciona imagem no topo da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); IjnputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(new FileInputStream(\"image.jpg\"), 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Adiciona imagem como cabeçalho às páginas do arquivo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile(\"test.jpg\")); fileStamp.addHeader(\"image.jpg\", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Adiciona imagem como cabeçalho nas páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(TestSettings.GetInputFile(\"test.jpg\")); fileStamp.addHeader(\"image.jpg\", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Adiciona número de página à página. O número de página pode conter o sinal # que será substituído pelo número da página. O número de página é colocado na parte inferior da página, centralizado horizontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Adiciona número de página na posição especificada da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Adiciona número de página às páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Adiciona número de página às páginas do documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Adiciona número de página ao arquivo. O texto do número de página pode conter o sinal # que será substituído pelo número da página. O número de página é colocado na parte inferior da página, centralizado horizontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Adiciona número de página na posição especificada da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Adiciona número de página às páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Adiciona número de página às páginas do documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Adiciona selo ao arquivo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Fecha arquivos abertos e salva alterações. Aviso. Se fluxos de entrada ou saída forem especificados, eles não são fechados pelo método Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Obsoleto. |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [getContentDisposition](#getContentDisposition--) | Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline. |
| [getInputFile](#getInputFile--) | Obtém o nome e o caminho do arquivo de entrada. |
| [getInputStream](#getInputStream--) | Obtém fluxo de entrada. Obsoleto("Use bindPdf(inputFile) method for facade initialization.") |
| [getKeepSecurity](#getKeepSecurity--) | Mantém segurança se verdadeiro. (Este recurso será implementado nas próximas versões). |
| [getNumberingStyle](#getNumberingStyle--) | Obtém ou define o estilo de numeração de página. Valores possíveis: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [getOptimizeSize](#getOptimizeSize--) | Obtém ou define a bandeira de otimização. |
| [getOutputFile](#getOutputFile--) | Obtém nome e caminho do arquivo de saída. Obsoleto("Use Save(outputFile) method for getting facade results.") |
| [getOutputStream](#getOutputStream--) | Obtém o fluxo de saída. |
| [getPageHeight](#getPageHeight--) | <p> Obtém altura da primeira página no arquivo de origem. </p> |
| [getPageNumberRotation](#getPageNumberRotation--) | Obtém rotação do número da página. A rotação está em graus. O padrão é 0. |
| [getPageWidth](#getPageWidth--) | <p> Obtém largura da primeira página no arquivo de entrada. </p> |
| [getSaveOptions](#getSaveOptions--) | Obtém opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions. |
| [getStampId](#getStampId--) | ID do selo do próximo selo adicionado (incluindo cabeçalhos/rodapés/páginas de número). |
| [getStartingNumber](#getStartingNumber--) | Obtém ou define o número inicial para a primeira página no arquivo de entrada. As próximas páginas serão numeradas a partir desse valor. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão. |
| [setInputFile](#setInputFile-java.lang.String-) | Define nome e caminho do arquivo de entrada. Obsoleto("Use bindPdf(inputFile) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Define o fluxo de entrada. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Mantém segurança se verdadeiro. (Este recurso será implementado nas próximas versões). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Obtém ou define o estilo de numeração de página. Valores possíveis: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtém ou define a bandeira de otimização. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Define nome e caminho do arquivo de saída. Obsoleto("Use Save(outputFile) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Define ou define o fluxo de saída. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Define rotação do número da página. A rotação está em graus. O padrão é 0. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Defina as opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | ID do selo do próximo selo adicionado (incluindo cabeçalhos/rodapés/páginas de número). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Define número inicial para a primeira página no arquivo de entrada. As próximas páginas serão numeradas a partir desse valor. Por exemplo, se StartingNumber for definido como 100, as páginas do documento terão os números 100, 101, 102... </p> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Posição inferior esquerda.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Posição inferior central.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Posição inferior direita.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Posição esquerda.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Posição direita.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Posição superior esquerda.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Posição central superior.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Posição superior direita.

### PdfFileStamp {#PdfFileStamp--}
```
public PdfFileStamp()
```

<p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-}
<p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-}
<p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-}
<p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-}
<p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-}
<p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStamp {#PdfFileStamp-java.lang.String-java.lang.String-boolean-}
<p> Construtor do PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Adiciona rodapé às páginas do documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Adiciona rodapé às páginas do documento. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Adiciona imagem como rodapé da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(new FileInputStream(\"image.jpg\"), 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Adiciona imagem como rodapé da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(new FileInputStream(\"image.jpg\"), 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Adiciona imagem como rodapé às páginas do documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(\"image.jpg\", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Adiciona imagem como rodapé das páginas.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Adiciona cabeçalho à página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addHeader(new FormattedText(\"Head of the page\"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Adiciona cabeçalho às páginas do arquivo. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addHeader(new FormattedText(\"Head of the page\"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Adiciona imagem como cabeçalho nas páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(new FileInputStream(\"image.jpg\"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Adiciona imagem no topo da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); IjnputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(new FileInputStream(\"image.jpg\"), 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Adiciona imagem como cabeçalho às páginas do arquivo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InpetuStream input = new FileInputStream(TestSettings.GetInputFile(\"test.jpg\")); fileStamp.addHeader(\"image.jpg\", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Adiciona imagem como cabeçalho nas páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(TestSettings.GetInputFile(\"test.jpg\")); fileStamp.addHeader(\"image.jpg\", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Adiciona número de página à página. O número de página pode conter o sinal # que será substituído pelo número da página. O número de página é colocado na parte inferior da página, centralizado horizontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Adiciona número de página na posição especificada da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Adiciona número de página às páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Adiciona número de página às páginas do documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Adiciona número de página ao arquivo. O texto do número de página pode conter o sinal # que será substituído pelo número da página. O número de página é colocado na parte inferior da página, centralizado horizontalmente. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Adiciona número de página na posição especificada da página. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Adiciona número de página às páginas. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_UPPER_RIGHT); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Adiciona número de página às páginas do documento. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Adiciona selo ao arquivo. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity(0.8f); stamp.isBackground(true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Fecha arquivos abertos e salva alterações. Aviso. Se fluxos de entrada ou saída forem especificados, eles não são fechados pelo método Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

**Returns:**
valor String

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline.

**Returns:**
Elemento ContentDisposition @see com.aspose.pdf.ContentDisposition

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Obtém o nome e o caminho do arquivo de entrada.

**Returns:**
valor String

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Obtém fluxo de entrada. Obsoleto("Use bindPdf(inputFile) method for facade initialization.")

**Returns:**
objeto InputStream

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Mantém segurança se verdadeiro. (Este recurso será implementado nas próximas versões).

**Returns:**
valor booleano

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Obtém ou define o estilo de numeração de página. Valores possíveis: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

**Returns:**
Elemento NumberingStyle @see NumberingStyle

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtém ou define a bandeira de otimização.

**Returns:**
valor booleano

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Obtém nome e caminho do arquivo de saída. Obsoleto("Use Save(outputFile) method for getting facade results.")

**Returns:**
valor String

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Obtém o fluxo de saída.

**Returns:**
objeto OutputStream

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Obtém altura da primeira página no arquivo de origem. </p>

**Returns:**
valor float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre>

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Obtém rotação do número da página. A rotação está em graus. O padrão é 0.

**Returns:**
valor float

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Obtém largura da primeira página no arquivo de entrada. </p>

**Returns:**
valor float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtém opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions.

**Returns:**
Objeto SaveOptions

### getStampId {#getStampId--}
```
public int getStampId()
```

ID do selo do próximo selo adicionado (incluindo cabeçalhos/rodapés/páginas de número).

**Returns:**
valor int

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Obtém ou define o número inicial para a primeira página no arquivo de entrada. As próximas páginas serão numeradas a partir desse valor.

**Returns:**
valor int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpResponse como anexo.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpResponse. Valor possível: inline / attachment. Padrão: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão.

### setInputFile {#setInputFile-java.lang.String-}
Define nome e caminho do arquivo de entrada. Obsoleto("Use bindPdf(inputFile) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Define o fluxo de entrada.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Mantém segurança se verdadeiro. (Este recurso será implementado nas próximas versões).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Obtém ou define o estilo de numeração de página. Valores possíveis: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Obtém ou define a bandeira de otimização.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOutputFile {#setOutputFile-java.lang.String-}
Define nome e caminho do arquivo de saída. Obsoleto("Use Save(outputFile) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Define ou define o fluxo de saída.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

Define rotação do número da página. A rotação está em graus. O padrão é 0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Defina as opções de salvamento quando o resultado é armazenado como HttpResponse. Valor padrão: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

ID do selo do próximo selo adicionado (incluindo cabeçalhos/rodapés/páginas de número).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Define número inicial para a primeira página no arquivo de entrada. As próximas páginas serão numeradas a partir desse valor. Por exemplo, se StartingNumber for definido como 100, as páginas do documento terão os números 100, 101, 102... </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber(100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
