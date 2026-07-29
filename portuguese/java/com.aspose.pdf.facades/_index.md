---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Referência da API Aspose.PDF para Java"
description: "O pacote com.aspose.pdf.facades fornece classes que originalmente vieram do Aspose.Pdf.Kit."
type: docs
weight: 180
url: /pt/java/com.aspose.pdf.facades/
---
O pacote com.aspose.pdf.facades fornece classes que originalmente vieram do Aspose.Pdf.Kit.

## Interfaces

| Interface | Descrição |
| --- | --- |
| [IFacade](./ifacade/) | Interface de fachada geral que define métodos comuns de fachadas. |
| [IForm](./iform/) | Classe que representa o objeto de formulário Acro. |
| [IFormEditor](./iformeditor/) | Classe para editar formulários (adicionar/excluir campos etc.) |
| [IPdfFileEditor](./ipdffileeditor/) | Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc. |
| [IPdfFileStamp](./ipdffilestamp/) | Interface para adicionar carimbos (marca d'água ou fundo) a arquivos PDF. |
| [ISaveableFacade](./isaveablefacade/) | Interface de fachada que define métodos comuns para todas as fachadas graváveis. |
## Classes

| Classe | Descrição |
| --- | --- |
| [AlignmentType](./alignmenttype/) | Classe que contém tipos de alinhamento possíveis. Use HorizontalAlignment em vez disso |
| [AutoRotateMode](./autorotatemode/) | Direção da rotação quando o documento é impresso. |
| [BDCProperties](./bdcproperties/) | Propriedades do operador BDC. |
| [Bookmark](./bookmark/) | Representa um marcador. |
| [Bookmarks](./bookmarks/) | Representa uma coleção de objetos {@code Bookmark}. |
| [CgmPdfProducer](./cgmpdfproducer/) | Representa uma classe para gerar PDF a partir do formato Computer Graphics Metafile (CGM). |
| [DataType](./datatype/) | Enumera definições de tipos de campo. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumeração de propriedades XMP padrão. |
| [DocumentPrivilege](./documentprivilege/) | Representa os privilégios para acessar arquivos Pdf. Consulte {@code PdfFileSecurity}. Existem 4 maneiras de usar esta classe: 1.Usando privilégio predefinido diretamente. 2.Baseado em um privilégio predefinido e alterando algumas permissões específicas. 3.Baseado em um privilégio predefinido e alterando uma combinação específica de permissões do Adobe Professional. 4.Mistura as maneiras 2 e 3. //Way1: Usando privilégio predefinido diretamente. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Baseado em um privilégio predefinido e alterando algumas permissões específicas. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Baseado em um privilégio predefinido e alterando uma combinação específica de permissões do Adobe Professional. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mistura as maneiras 2 e 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Enumera os tipos de codificação usados no texto. |
| [Facade](./facade/) | Classe fachada base. |
| [FontColor](./fontcolor/) | Classe que representa a cor do texto. |
| [Form](./form/) | Classe que representa o objeto de formulário Acro. |
| [Form.ImportStatus](./form.importstatus/) | Status do campo importado |
| [FormattedText](./formattedtext/) | Classe que representa texto formatado. Contém informações sobre o texto e sua cor, tamanho e estilo. |
| [FormEditor](./formeditor/) | Classe para editar formulários (adicionar/excluir campos etc.) |
| [FormEditorWeb](./formeditorweb/) | Classe para editar formulários (adicionar/excluir campo etc) |
| [FormFieldFacade](./formfieldfacade/) | Classe para representar propriedades de campo. |
| [FormWeb](./formweb/) | Representando a interface de formulário Acro. |
| [InternalHelper](./internalhelper/) | Classe de ajuda |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Classe para especificar parâmetros de redimensionamento de página. Permite definir os seguintes parâmetros: tamanho da página resultante (largura, altura) em unidades de espaço padrão ou em porcentagem do tamanho da página inicial; margens esquerda, superior, inferior e direita em unidades de espaço padrão ou em porcentagem do tamanho da página inicial; alguns valores podem ser deixados nulos para cálculo automático. Esses valores serão calculados a partir do restante do tamanho da página após o cálculo dos valores explicitamente especificados. Por exemplo: se a largura da página = 100 e a nova largura da página especificada for 60 unidades, então as margens esquerda e direita são calculadas automaticamente: (100 - 60) / 2 = 15. Esta classe é usada no método ResizeContents. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Valor da margem ou tamanho do conteúdo especificado em porcentagem das unidades de espaço padrão. Esta classe é usada em ContentsResizeParameters. |
| [LineInfo](./lineinfo/) | Representa as informações da linha. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Representa uma classe para trabalhar com anotações (comentários) de documentos PDF. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Representa uma classe para trabalhar com marcadores de arquivos PDF, incluindo criar, modificar, exportar, importar e excluir. |
| [PdfContentEditor](./pdfcontenteditor/) | Representa uma classe para editar o conteúdo de arquivos PDF. |
| [PdfConverter](./pdfconverter/) | Representa uma classe para converter cada página de um arquivo PDF em imagens, suportando atualmente BMP, JPEG, PNG e TIFF. Conteúdo suportado em PDFs: imagens, formulários, comentários. |
| [PdfExtractor](./pdfextractor/) | Classe para extrair imagens e texto de documentos PDF. |
| [PdfFileEditor](./pdffileeditor/) | Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Ação executada quando um arquivo corrompido é encontrado no processo de concatenação. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Representa uma classe com método abstrato que normalmente é fornecido pela parte chamadora e lida com eventos de progresso provenientes da concatenação. Normalmente, esse manipulador fornecido pelo cliente pode ser usado para mostrar o progresso total da concatenação no console ou em uma barra de progresso. Representa informações sobre o evento de progresso ocorrido. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Classe que fornece informações sobre arquivos corrompidos durante a concatenação. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Dados da posição de quebra de página. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | Esta classe representa informações sobre o progresso da concatenação que podem ser usadas em aplicação externa. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | Este enum descreve os tipos de eventos de progresso possíveis que podem ocorrer durante a concatenação |
| [PdfFileEditorWeb](./pdffileeditorweb/) | Representa a classe PdfFileEditorWeb que implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc. |
| [PdfFileInfo](./pdffileinfo/) | Representa uma classe para acessar metainformações de documento PDF. |
| [PdfFileMend](./pdffilemend/) | Representa uma classe para adicionar textos e imagens nas páginas de um documento PDF existente. |
| [PdfFileSanitization](./pdffilesanitization/) | Representa a API de sanitização e recuperação. Use-a se não for possível criar/abrir documentos de outra forma. |
| [PdfFileSecurity](./pdffilesecurity/) | Representa a criptografia ou descriptografia de um arquivo PDF com senha de proprietário ou de usuário, alterando as configurações de segurança e a senha. |
| [PdfFileSignature](./pdffilesignature/) | Representa uma classe para assinar um arquivo PDF com um certificado. |
| [PdfFileStamp](./pdffilestamp/) | Classe para adicionar carimbos (marca d'água ou plano de fundo) a arquivos PDF. |
| [PdfFileStampWeb](./pdffilestampweb/) | Classe para adicionar carimbos (marca d'água ou plano de fundo) a arquivos PDF. Habilita o trabalho com HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Classe para remover todo o código JavaScript. |
| [PdfPageEditor](./pdfpageeditor/) | Representa uma classe para editar a página de um arquivo PDF, incluindo rotação da página, zoom, movimentação da posição e alteração do tamanho da página. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Representa um objeto que contém informações da página de impressão atual. |
| [PdfProducer](./pdfproducer/) | <p> Representa uma classe para gerar PDF a partir de outros formatos. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Representa o método que trata o evento QueryPageSettings de um PrintDocument. |
| [PdfViewer](./pdfviewer/) | Representa uma classe para visualizar ou imprimir um PDF. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Classe para manipulação de metadados XMP. |
| [PositioningMode](./positioningmode/) | Define o modo de posicionamento. Valores possíveis incluem Legacy (compatibilidade retroativa) e Current (método atualizado de cálculo de posição de texto). |
| [PropertyFlag](./propertyflag/) | Enumeração de bandeiras de campo possíveis. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Esta classe contém parâmetros que definem o comportamento do PdfContentEditor quando a operação ReplaceText é executada. |
| [SaveableFacade](./saveablefacade/) | <p> Classe base para todas as fachadas salváveis.</p> |
| [SignatureName](./signaturename/) | Representa uma classe para um nome de assinatura. Representa um nome de assinatura mais preciso. Usado em vez de nomes de string. Permite apresentar assinaturas com os mesmos nomes de string. |
| [Stamp](./stamp/) | Classe representando carimbo. |
| [StampInfo](./stampinfo/) | Classe que representa informações de carimbo. |
| [TextProperties](./textproperties/) | Representa propriedades de texto como: tamanho do texto, cor, estilo etc. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Classe que representa valores possíveis de alinhamento vertical. Use VerticalAlignment em vez disso |
| [ViewerPreference](./viewerpreference/) | Descreve as preferências do visualizador (modo de página, modo de página sem tela cheia, layout de página). |
| [WordWrapMode](./wordwrapmode/) | Define estratégias de quebra de linha |
## Enums

| Enum | Descrição |
| --- | --- |
| [Algorithm](./algorithm/) | Representa algoritmos que podem ser usados para criptografar documentos PDF. |
| [BlendingColorSpace](./blendingcolorspace/) | Classe que representa o espaço de cor de mesclagem. |
| [FieldType](./fieldtype/) | Enumeração dos tipos de campo possíveis. |
| [FontStyle](./fontstyle/) | Enumera 14 tipos de fonte. |
| [ImageMergeMode](./imagemergemode/) | Representa modos de mesclagem de imagens. |
| [KeySize](./keysize/) | Define diferentes tamanhos de chave que podem ser usados para criptografar documentos PDF. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Ação a ser executada se a fonte não contiver o caractere necessário |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Escopo onde a operação de substituir texto é aplicada REPLACE_FIRST por padrão |
| [StampType](./stamptype/) | Descreve os tipos de selo. |
| [SubmitFormFlag](./submitformflag/) | Enumeração das possíveis bandeiras de envio de formulário. |
