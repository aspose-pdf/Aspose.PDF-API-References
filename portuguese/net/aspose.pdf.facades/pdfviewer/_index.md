---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfViewer. Representa uma classe para visualizar ou imprimir um pdf
type: docs
weight: 4630
url: /pt/net/aspose.pdf.facades/pdfviewer/
---
## Classe PdfViewer

Representa uma classe para visualizar ou imprimir um pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Inicializa um novo objeto `PdfViewer`. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Inicializa um novo objeto `PdfViewer`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Obtém ou define um valor bool que indica se o arquivo deve ser impresso com tamanho otimizado. Se falso, imprime a página sem escalonamento. Se verdadeiro, imprime a página com escalonamento para caber na área imprimível. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Obtém ou define um valor bool que indica se o arquivo deve ser impresso com rotação automática. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Obtém ou define um valor AutoRotateMode que indica a direção da rotação. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Obtém ou define o modo de apresentação do formulário. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Obtém ou define um valor que indica o alinhamento horizontal. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Obtém a contagem de páginas do arquivo Pdf atual. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Obtém ou define a senha do documento de entrada. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Obtém ou define um valor bool que indica se a página está sendo impressa em escala de cinza. Por padrão, é falso. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Define ou obtém um modo para o PdfViewer imprimir como imagem. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Obtém ou define o nome do documento na fila da impressora quando o documento é impresso. O valor padrão é o nome do arquivo. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Obtém ou define um valor bool que indica se deve ser gerado o diálogo de número da página ao imprimir. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Obtém o resultado do trabalho de impressão. Se for sucesso, então nulo; caso contrário, objeto de exceção. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Obtém ou define opções de renderização. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Obtém ou define a resolução durante a visualização e impressão. Quanto maior a resolução, mais lenta a velocidade. O valor padrão é 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Obtém ou define um valor de ponto flutuante que indica o fator de escala. O valor padrão é 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Obtém/define o uso da conversão da página pdf em um arquivo png intermediário durante a impressão em modo de arquivo. Use-o quando o tamanho do arquivo de saída for importante. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Obtém ou define um valor que indica o alinhamento vertical. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Inicializa a fachada. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Inicializa a fachada. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Inicializa a fachada. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Fecha a fachada. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Obtém as páginas do arquivo pdf atual. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Decodifica uma página de um arquivo Pdf. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Descarte os recursos da fachada. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Obtém as configurações de página padrão. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Obtém as configurações de impressora padrão. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Imprime o documento Pdf usando a impressora padrão. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Imprime o documento Pdf com configurações da impressora. O tamanho da página de saída se ajustará ao tamanho da primeira página do documento. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Imprime o documento Pdf com configurações. Se o tamanho do documento não corresponder ao tamanho da página, ele será estendido para caber no tamanho da página. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Imprime o documento Pdf com um diálogo de configuração. Escolha uma impressora usando o diálogo. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Abre e imprime um grande fluxo Pdf. Se seu arquivo Pdf tiver centenas de páginas ou mais ou seu tamanho for superior a 3 MB, este método é recomendado para obter melhor desempenho. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Abre e imprime um grande arquivo Pdf. Se seu arquivo Pdf tiver centenas de páginas ou mais ou seu tamanho for superior a 3 MB, este método é recomendado para obter melhor desempenho. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Abre e imprime um grande fluxo Pdf com as configurações da impressora especificadas. Se seu arquivo Pdf tiver centenas de páginas ou mais ou seu tamanho for superior a 3 MB, este método é recomendado para obter melhor desempenho. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Abre e imprime um grande arquivo Pdf com as configurações da impressora especificadas. Se seu arquivo Pdf tiver centenas de páginas ou mais ou seu tamanho for superior a 3 MB, este método é recomendado para obter melhor desempenho. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Abre e imprime um grande fluxo Pdf com as configurações de página e impressora especificadas. Se seu arquivo Pdf tiver centenas de páginas ou mais ou seu tamanho for superior a 3 MB, este método é recomendado para obter melhor desempenho. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Abre e imprime um grande arquivo Pdf com as configurações de página e impressora especificadas. Se seu arquivo Pdf tiver centenas de páginas ou mais ou seu tamanho for superior a 3 MB, este método é recomendado para obter melhor desempenho. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Salva o documento PDF resultante no fluxo. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Salva o documento PDF resultante no arquivo. |

## Eventos

| Nome | Descrição |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Ocorre antes do início da impressão e permite fornecer manipuladores de impressão personalizados em vez do padrão. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Ocorre quando a impressão de uma página termina no PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Adiciona/remove a assinatura no evento de impressão da última página. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Adiciona/remove a assinatura no evento de impressão da última página. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Ocorre antes de uma página começar a ser impressa. |

### Veja Também

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)