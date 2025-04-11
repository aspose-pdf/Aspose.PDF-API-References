---
title: Aspose.Pdf.Facades
second_title: Aspose.PDF for .NET API Reference
description: O namespace Aspose.Pdf.Facades fornece classes que originalmente vieram do Aspose.Pdf.Kit. Essas classes são usadas para manipular documentos realizando operações como concatenar, carimbar, assinar, anotar etc., mas em um nível alto, sem acesso à estrutura interna dos documentos.
type: docs
weight: 100
url: /pt/net/aspose.pdf.facades/
---
O **namespace Aspose.Pdf.Facades** fornece classes que originalmente vieram do Aspose.Pdf.Kit. Essas classes são usadas para manipular documentos realizando operações como concatenar, carimbar, assinar, anotar etc., mas em um nível alto, sem acesso à estrutura interna de um documento.

## Classes

| Classe | Descrição |
| --- | --- |
| [AutoFiller](./autofiller/) | Representa uma classe para receber dados de um banco de dados ou outra fonte de dados, preenchê-los nos campos projetados do pdf modelo e, por fim, gerar um novo arquivo ou fluxo pdf. Possui dois modos de entrada de arquivo modelo: entrada como um fluxo ou um arquivo pdf. Possui quatro tipos de modos de saída: um fluxo mesclado, um arquivo mesclado, muitos pequenos fluxos, muitos pequenos arquivos. Pode receber dados literais contidos em um System.Data.DataTable. |
| [BDCProperties](./bdcproperties/) | Propriedades do operador BDC. |
| [Bookmark](./bookmark/) | Representa um marcador. |
| [Bookmarks](./bookmarks/) | Representa uma coleção de objetos [`Bookmark`](../aspose.pdf.facades/bookmark/). |
| [DocumentPrivilege](./documentprivilege/) | Representa os privilégios para acessar um arquivo Pdf. Consulte [`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/). Existem 4 maneiras de usar esta classe: 1. Usando privilégio pré-definido diretamente. 2. Baseado em um privilégio pré-definido e alterando algumas permissões específicas. 3. Baseado em um privilégio pré-definido e alterando algumas combinações específicas de permissões do Adobe Professional. 4. Mistura os modos 2 e 3. |
| [Facade](./facade/) | Classe base de fachada. |
| [FontColor](./fontcolor/) | Classe que representa a cor do texto. |
| [Form](./form/) | Classe que representa um objeto de formulário Acro. |
| [FormattedText](./formattedtext/) | Classe que representa texto formatado. Contém informações sobre o texto e sua cor, tamanho, estilo. |
| [FormDataConverter](./formdataconverter/) | Representa uma classe para converter dados de um formato para outro. Pode converter dados em fdf/xml/pdf/xfdf para OLEDB/OdbcDB. Também pode converter dados em OLEDB/OdbcDB para dados em fdf/xml/xfdf. Pode converter fdf para xml com a tag "hard-named". |
| [FormEditor](./formeditor/) | Classe para editar formulários (adição/exclusão de campos etc) |
| [FormFieldFacade](./formfieldfacade/) | Classe para representar propriedades de campo. |
| [LineInfo](./lineinfo/) | Representa as informações da linha. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Representa uma classe para trabalhar com anotações de documentos PDF (comentários). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Representa uma classe para trabalhar com marcadores de arquivos PDF, incluindo criar, modificar, exportar, importar e excluir. |
| [PdfContentEditor](./pdfcontenteditor/) | Representa uma classe para editar o conteúdo de arquivos PDF. |
| [PdfConverter](./pdfconverter/) | Representa uma classe para converter cada página de um arquivo pdf em imagens, suportando BMP, JPEG, PNG e TIFF agora. Conteúdo suportado em pdfs: imagens, formulário, comentário. |
| [PdfExtractor](./pdfextractor/) | Classe para extrair imagens e texto de documentos PDF. |
| [PdfFileEditor](./pdffileeditor/) | Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livreto, etc. |
| [PdfFileInfo](./pdffileinfo/) | Representa uma classe para acessar informações meta de documentos PDF. |
| [PdfFileMend](./pdffilemend/) | Representa uma classe para adicionar textos e imagens nas páginas de um documento PDF existente. |
| [PdfFileSanitization](./pdffilesanitization/) | Representa a API de sanitização e recuperação. Use-a se você não conseguir criar/abrir documentos de nenhuma outra maneira. |
| [PdfFileSecurity](./pdffilesecurity/) | Representa a criptografia ou descriptografia de um arquivo Pdf com senha de proprietário ou usuário, alterando a configuração de segurança e a senha. |
| [PdfFileSignature](./pdffilesignature/) | Representa uma classe para assinar um arquivo pdf com um certificado. |
| [PdfFileStamp](./pdffilestamp/) | Classe para adicionar carimbos (marca d'água ou fundo) a arquivos PDF. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Classe para remover todo o código Java Script. |
| [PdfPageEditor](./pdfpageeditor/) | Representa uma classe para editar a página de um arquivo PDF, incluindo girar página, ampliar página, mover posição e alterar o tamanho da página. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Representa um objeto que contém informações da página de impressão atual. |
| [PdfProducer](./pdfproducer/) | Representa uma classe para produzir PDF a partir de outros formatos. Este exemplo mostra como produzir um arquivo Pdf a partir de um arquivo CGM. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Representa o método que manipula o evento [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) de um [`PdfViewer`](../aspose.pdf.facades/pdfviewer/). |
| [PdfViewer](./pdfviewer/) | Representa uma classe para visualizar ou imprimir um pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Classe para manipulação com metadados XMP. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Esta classe contém parâmetros que definem o comportamento do PdfContentEditor quando a operação ReplaceText é realizada. |
| [SaveableFacade](./saveablefacade/) | Classe base para todas as fachadas salváveis. |
| [SignatureName](./signaturename/) | Representa uma classe para um nome de assinatura. |
| [Stamp](./stamp/) | Classe que representa um carimbo. |
| [StampInfo](./stampinfo/) | Classe que representa informações do carimbo. |
| [TextProperties](./textproperties/) | Representa propriedades do texto, como: tamanho do texto, cor, estilo etc. |
| [ViewerPreference](./viewerpreference/) | Descreve preferências do visualizador (modo de página, modo de página não em tela cheia, layout da página). |
## Interfaces

| Interface | Descrição |
| --- | --- |
| [IFacade](./ifacade/) | Interface de fachada geral que define métodos comuns de fachadas. |
| [ISaveableFacade](./isaveablefacade/) | Interface de fachada que define métodos comuns para todas as fachadas salváveis. |
## Enumeração

| Enumeração | Descrição |
| --- | --- |
| [Algorithm](./algorithm/) | Representa algoritmos que podem ser usados para criptografar documentos pdf. |
| [AutoRotateMode](./autorotatemode/) | Direção da rotação quando o documento é impresso. |
| [BlendingColorSpace](./blendingcolorspace/) | Classe que representa o espaço de cor de mesclagem. |
| [DataType](./datatype/) | Enumera definições de tipos de campo. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumeração de propriedades XMP padrão. |
| [EncodingType](./encodingtype/) | Enumera os tipos de codificação do texto utilizado. |
| [FieldType](./fieldtype/) | Enumeração dos possíveis tipos de campo. |
| [FontStyle](./fontstyle/) | Enumera 14 tipos de fonte. |
| [ImageMergeMode](./imagemergemode/) | Representa modos para mesclar imagens. |
| [KeySize](./keysize/) | Define diferentes tamanhos de chave que podem ser usados para criptografar documentos pdf. |
| [PositioningMode](./positioningmode/) | Define o modo de posicionamento. Os valores possíveis incluem Legado (compatibilidade retroativa) e Atual (método de cálculo de posição de texto atualizado) |
| [PropertyFlag](./propertyflag/) | Enumeração de possíveis flags de campo. |
| [StampType](./stamptype/) | Descreve tipos de carimbos. |
| [SubmitFormFlag](./submitformflag/) | Enumeração de possíveis flags de envio de formulário. |
| [WordWrapMode](./wordwrapmode/) | Define estratégias de quebra de linha |