---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para visualizar ou imprimir um PDF."
type: docs
weight: 610
url: /pt/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

Representa uma classe para visualizar ou imprimir um PDF.

## Campos

| Campo | Descrição |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Adiciona/remove assinatura no evento de impressão da última página. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Adiciona/remove assinatura no evento de impressão da última página. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Inicializa um novo objeto {@code PdfViewer}. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Inicializa um novo objeto {@code PdfViewer}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.lang.String-) | Inicializa a fachada. |
| [close](#close--) | Fecha o arquivo PDF atual. |
| [closePdfFile](#closePdfFile--) | Fecha o arquivo PDF atual. |
| [decodeAllPages](#decodeAllPages--) | Obtém as páginas do arquivo PDF atual. |
| [decodePage](#decodePage-int-) | Decodifica uma página de um arquivo PDF. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Decodifica a página para BufferedImage |
| [dispose](#dispose--) | Libera os recursos da fachada. Este método está obsoleto, use close() em vez disso. |
| [getAutoResize](#getAutoResize--) | Define um valor booleano que indica se o arquivo deve ser impresso com tamanho otimizado. |
| [getAutoRotate](#getAutoRotate--) | Obtém um valor bool que indica se o arquivo deve ser impresso com rotação automática |
| [getAutoRotateMode](#getAutoRotateMode--) | Obtém um valor AutoRotateMode que indica a direção da rotação |
| [getCoordinateType](#getCoordinateType--) | Obtém o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [getCopiesPrinted](#getCopiesPrinted--) | Obtém cópias impressas |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Obtém as configurações de página padrão. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Obtém as configurações padrão da impressora. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtém o modo de apresentação do formulário. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtém um valor que indica o alinhamento horizontal |
| [getPageCount](#getPageCount--) | Obtém a contagem de páginas do arquivo Pdf atual. |
| [getPassword](#getPassword--) | Obtém a senha do documento de entrada. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Obtém ou define um valor bool que indica se a página está sendo impressa em escala de cinza. Por padrão, é false. </p> <hr> Padrão false é false. |
| [getPrintAsImage](#getPrintAsImage--) | <p> Obtém um modo para o PdfViewer imprimir como imagem. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Obtém o nome do documento na fila da impressora quando o documento é impresso. O valor padrão é o nome do arquivo. |
| [getPrintPageDialog](#getPrintPageDialog--) | Obtém um valor bool que indica se produz o diálogo de número de página ao imprimir. |
| [getPrintStatus](#getPrintStatus--) | Obtém o resultado da tarefa de impressão. Se for bem-sucedido, retorna null; caso contrário, um objeto de exceção. |
| [getRenderingOptions](#getRenderingOptions--) | Obtém as opções de renderização. |
| [getResolution](#getResolution--) | Obtém ou define a resolução durante a visualização e impressão. Quanto maior a resolução, mais lenta a velocidade. O valor padrão é 150. Esta propriedade altera a resolução da imagem nos fluxos de conversão de página para imagem: quando o {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) está definido como {@code }, ou quando o método {@link #decodePage(int)} ou {@link #decodeAllPages} é chamado. Para definir uma resolução de impressora para impressão direta em uma impressora, use a propriedade {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) na classe {@code PageSettings}. |
| [getScaleFactor](#getScaleFactor--) | Obtém um valor de ponto flutuante que indica o fator de escala. O valor padrão é 1.0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Obtém o uso da conversão de página pdf em arquivo png intermediário durante a impressão no modo de arquivo. Use isso quando o tamanho do arquivo de saída for importante. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém um valor que indica o alinhamento vertical |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Este método está obsoleto. Obtém a bandeira que controla a visibilidade das áreas ocultas na página. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Abre um fluxo de arquivo Pdf. Mas não decodifica realmente as páginas do arquivo Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Abre um arquivo Pdf, mas não decodifica realmente as páginas do arquivo Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Imprime o documento Pdf usando a impressora padrão. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //imprime o arquivo com tamanho ajustado viewer.setAutoRotate ( true); //imprime o arquivo com rotação ajustada viewer.setPrintPageDialog ( false); //não produz o diálogo de número de página ao imprimir viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Imprime o documento Pdf com configurações de impressora. O tamanho da página de saída se ajustará ao tamanho da primeira página do documento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //imprime o arquivo com tamanho ajustado viewer.setAutoRotate ( true); //imprime o arquivo com rotação ajustada viewer.setPrintPageDialog ( false); //não produz o diálogo de número de página ao imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Imprime o documento Pdf com configurações. Se o tamanho do documento não for compatível com o tamanho da página, pdf.kit o estenderá para caber no tamanho da página. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Abre e imprime um grande fluxo Pdf. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é superior a 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Abre e imprime um grande fluxo Pdf com configurações de impressora especificadas. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é superior a 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Abre e imprime um grande fluxo Pdf com configurações de página e de impressora especificadas. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é superior a 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Abre e imprime um grande arquivo Pdf. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é superior a 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Abre e imprime um arquivo Pdf grande com configurações de impressora especificadas. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é maior que 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente. |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Abre e imprime um arquivo Pdf grande com configurações de página e impressora especificadas. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é maior que 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente. |
| [save](#save-java.io.InputStream-) | Salva o documento PDF resultante em um fluxo. |
| [save](#save-java.lang.String-) | Salva o documento PDF resultante em um arquivo. |
| [setAutoResize](#setAutoResize-boolean-) | Define um valor booleano que indica se o arquivo deve ser impresso com tamanho otimizado. |
| [setAutoRotate](#setAutoRotate-boolean-) | Define um valor bool que indica se o arquivo deve ser impresso com rotação automática |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Define um valor AutoRotateMode que indica a direção da rotação |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Define o modo de apresentação do formulário. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Define um valor que indica o alinhamento horizontal |
| [setPassword](#setPassword-java.lang.String-) | Define a senha do documento de entrada. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Obtém ou define um valor bool que indica se a página está sendo impressa em escala de cinza. Por padrão, é false. </p> <hr> Padrão false é false. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> Define um modo para o PdfViewer imprimir como imagem. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Define o nome do documento na fila da impressora quando o documento é impresso. O valor padrão é o nome do arquivo. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Define um valor booleano que indica se deve produzir a caixa de diálogo de número de página ao imprimir. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Define as opções de renderização. |
| [setResolution](#setResolution-int-) | Define a resolução durante a visualização e impressão. Quanto maior a resolução, mais lenta a velocidade. O valor padrão é 150. Esta propriedade altera a resolução da imagem nos fluxos de conversão de página para imagem: quando o {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) está definido como {@code }, ou quando o método {@link #decodePage(int)} ou {@link #decodeAllPages} é chamado. Para definir a resolução da impressora para impressão direta em uma impressora, use a propriedade {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) na classe {@code PageSettings}. |
| [setScaleFactor](#setScaleFactor-float-) | Define um valor de ponto flutuante que indica o fator de escala. O valor padrão é 1.0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Obsoleto. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Define o uso da conversão de página pdf em arquivo png intermediário durante a impressão no modo de arquivo. Use isso quando o tamanho do arquivo de saída for importante. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Define um valor que indica o alinhamento vertical |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Adiciona/remove assinatura no evento de impressão da última página.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Adiciona/remove assinatura no evento de impressão da última página.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Inicializa um novo objeto {@code PdfViewer}.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Inicializa um novo objeto {@code PdfViewer}.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.io.InputStream-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.lang.String-}
Inicializa a fachada.

### close {#close--}
```
public void close()
```

Fecha o arquivo PDF atual.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Fecha o arquivo PDF atual.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Obtém as páginas do arquivo PDF atual.

**Returns:**
retorna o array de imagens de páginas Pdf.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Decodifica uma página de um arquivo PDF.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de um arquivo Pdf que deve estar entre 1 e PageCount. |

**Returns:**
retorna a imagem da página Pdf.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Decodifica a página para BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libera os recursos da fachada. Este método está obsoleto, use close() em vez disso.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Define um valor booleano que indica se o arquivo deve ser impresso com tamanho otimizado.

**Returns:**
valor booleano: Se false, imprime a página sem redimensionamento. Se true, imprime a página com redimensionamento para caber na área imprimível.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Obtém um valor bool que indica se o arquivo deve ser impresso com rotação automática

**Returns:**
valor booleano

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Obtém um valor AutoRotateMode que indica a direção da rotação

**Returns:**
Elemento AutoRotateMode @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtém o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão.

**Returns:**
Elemento PageCoordinateType @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Obtém cópias impressas

**Returns:**
valor int

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Obtém as configurações de página padrão.

**Returns:**
Objeto de configurações de página.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Obtém as configurações padrão da impressora.

**Returns:**
Objeto de configurações de página.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtém o modo de apresentação do formulário.

**Returns:**
Elemento FormPresentationMode @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtém um valor que indica o alinhamento horizontal

**Returns:**
Elemento HorizontalAlignment @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Obtém a contagem de páginas do arquivo Pdf atual.

**Returns:**
retorna a contagem de páginas.

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtém a senha do documento de entrada.

**Returns:**
valor String

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Obtém ou define um valor bool que indica se a página está sendo impressa em escala de cinza. Por padrão, é false. </p> <hr> Padrão false é false.

**Returns:**
valor booleano

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> Obtém um modo para o PdfViewer imprimir como imagem. </p>

**Returns:**
valor booleano <hr> Se true, sempre imprime como imagem (gera a imagem que é impressa). Se false, imprime diretamente no dispositivo se todos os recursos forem suportados. Caso o documento contenha recursos não suportados, o sistema pode decidir automaticamente imprimir como imagem. O valor padrão é false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Obtém o nome do documento na fila da impressora quando o documento é impresso. O valor padrão é o nome do arquivo.

**Returns:**
valor String

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Obtém um valor bool que indica se produz o diálogo de número de página ao imprimir.

**Returns:**
valor booleano

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Obtém o resultado da tarefa de impressão. Se for bem-sucedido, retorna null; caso contrário, um objeto de exceção.

**Returns:**
objeto de exceção ou null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Obtém as opções de renderização.

**Returns:**
Objeto RenderingOptions

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtém ou define a resolução durante a visualização e impressão. Quanto maior a resolução, mais lenta a velocidade. O valor padrão é 150. Esta propriedade altera a resolução da imagem nos fluxos de conversão de página para imagem: quando o {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) está definido como {@code }, ou quando o método {@link #decodePage(int)} ou {@link #decodeAllPages} é chamado. Para definir uma resolução de impressora para impressão direta em uma impressora, use a propriedade {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) na classe {@code PageSettings}.

**Returns:**
valor int

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Obtém um valor de ponto flutuante que indica o fator de escala. O valor padrão é 1.0.

**Returns:**
valor de ponto flutuante.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Obtém o uso da conversão de página pdf em arquivo png intermediário durante a impressão no modo de arquivo. Use isso quando o tamanho do arquivo de saída for importante.

**Returns:**
valor booleano.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtém um valor que indica o alinhamento vertical

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Este método está obsoleto. Obtém a bandeira que controla a visibilidade das áreas ocultas na página.

**Returns:**
valor booleano

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Abre um fluxo de arquivo Pdf. Mas não decodifica realmente as páginas do arquivo Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Abre um arquivo Pdf, mas não decodifica realmente as páginas do arquivo Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Imprime o documento Pdf usando a impressora padrão. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Imprime o documento Pdf com configurações de impressora. O tamanho da página de saída se ajustará ao tamanho da primeira página do documento. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Imprime o documento Pdf com configurações. Se o tamanho do documento não for compatível com o tamanho da página, o pdf.kit o estenderá para caber na página. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Abre e imprime um grande fluxo Pdf. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é superior a 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@\"d:\\test.pdf\"))); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Abre e imprime um grande fluxo Pdf com configurações de impressora especificadas. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é superior a 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Abre e imprime um grande fluxo Pdf com configurações de página e de impressora especificadas. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é maior que 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); // imprime o arquivo com tamanho ajustado viewer.setAutoRotate ( true); // imprime o arquivo com rotação ajustada viewer.setPrintPageDialog ( false); // não produz o diálogo de número de página ao imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Abre e imprime um grande arquivo Pdf. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é maior que 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // imprime o arquivo com tamanho ajustado viewer.setAutoRotate(true); // imprime o arquivo com rotação ajustada viewer.setPrintPageDialog(false); // não produz o diálogo de número de página ao // imprimir viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Abre e imprime um grande arquivo Pdf com configurações de impressora especificadas. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é maior que 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); // imprime o arquivo com tamanho ajustado viewer.setAutoRotate ( true); // imprime o arquivo com rotação ajustada viewer.setPrintPageDialog ( false); // não produz o diálogo de número de página ao imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente.

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Abre e imprime um grande arquivo Pdf com configurações de página e de impressora especificadas. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é maior que 3 MB, este método é recomendado para obter melhor desempenho. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // imprime o arquivo com tamanho ajustado viewer.setAutoRotate(true); // imprime o arquivo com rotação ajustada viewer.setPrintPageDialog(false); // não produz o diálogo de número de página ao // imprimir PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Este método integrou a abertura e a impressão do arquivo e você não precisa chamar o OpenPdfFile() explicitamente.

### save {#save-java.io.InputStream-}
Salva o documento PDF resultante em um fluxo.

### save {#save-java.lang.String-}
Salva o documento PDF resultante em um arquivo.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Define um valor booleano que indica se o arquivo deve ser impresso com tamanho otimizado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano: Se false, imprime a página sem redimensionamento. Se true, imprime a página com redimensionamento para caber na área imprimível. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Define um valor bool que indica se o arquivo deve ser impresso com rotação automática

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Define um valor AutoRotateMode que indica a direção da rotação

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento AutoRotateMode @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Define o modo de apresentação do formulário.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | FormPresentationMode elemento |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Define um valor que indica o alinhamento horizontal

### setPassword {#setPassword-java.lang.String-}
Define a senha do documento de entrada.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Obtém ou define um valor bool que indica se a página está sendo impressa em escala de cinza. Por padrão, é false. </p> <hr> Padrão false é false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> Define um modo para o PdfViewer imprimir como imagem. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano <hr> Se true, sempre imprime como imagem (gera a imagem que é impressa). Se false, imprime diretamente no dispositivo se todos os recursos forem suportados. Caso o documento contenha recursos não suportados, o sistema pode decidir automaticamente imprimir como imagem. O valor padrão é false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Define o nome do documento na fila da impressora quando o documento é impresso. O valor padrão é o nome do arquivo.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Define um valor booleano que indica se deve produzir a caixa de diálogo de número de página ao imprimir.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Define as opções de renderização.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Define a resolução durante a visualização e impressão. Quanto maior a resolução, mais lenta a velocidade. O valor padrão é 150. Esta propriedade altera a resolução da imagem nos fluxos de conversão de página para imagem: quando o {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) está definido como {@code }, ou quando o método {@link #decodePage(int)} ou {@link #decodeAllPages} é chamado. Para definir a resolução da impressora para impressão direta em uma impressora, use a propriedade {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) na classe {@code PageSettings}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Define um valor de ponto flutuante que indica o fator de escala. O valor padrão é 1.0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor de ponto flutuante. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Obsoleto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Define o uso da conversão de página pdf em arquivo png intermediário durante a impressão no modo de arquivo. Use isso quando o tamanho do arquivo de saída for importante.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Define um valor que indica o alinhamento vertical
