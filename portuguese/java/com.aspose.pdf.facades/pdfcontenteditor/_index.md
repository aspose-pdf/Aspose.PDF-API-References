---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para editar o conteúdo de arquivos PDF."
type: docs
weight: 380
url: /pt/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

Representa uma classe para editar o conteúdo de arquivos PDF.

## Campos

| Campo | Descrição |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | Um tipo de evento de documento. Fecha um documento. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | Um tipo de evento de documento. Abre um documento. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | Um tipo de evento de documento. Executa uma ação após a impressão. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | Um tipo de evento de documento. Executa uma ação após a gravação. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | Um tipo de evento de documento. Executa uma ação antes da impressão. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | Um tipo de evento de documento. Executa uma ação antes da gravação. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | O construtor do objeto PdfContentEditor. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | O construtor do objeto PdfContentEditor. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Adiciona ação adicional para o evento do documento. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Adiciona anexo de documento sem anotação. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Adiciona anexo de documento sem anotação. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Associa um fluxo PDF para edição. |
| [bindPdf](#bindPdf-java.lang.String-) | Associa um arquivo PDF para edição. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Altera a preferência de visualização. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Fecha o documento aberto. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Cria um link para iniciar um aplicativo no documento PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Cria um link para iniciar um aplicativo no documento PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Cria um link para iniciar um aplicativo no documento PDF. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Cria um marcador com a ação especificada. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Cria anotação de cursor. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Cria um link para ações personalizadas no documento PDF. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Cria anotação de anexo de arquivo. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Cria anotação de anexo de arquivo. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Cria anotação de texto livre no documento PDF |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Cria um link para JavaScript no documento PDF. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Cria anotação de linha. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | Cria um link local no documento PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Cria um link local no documento PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Cria um link local no documento PDF. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Cria anotação de marcação no documento PDF. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Cria um link para outra página de documento PDF. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Cria um link para outra página de documento PDF. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Cria um link para outra página de documento PDF. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Cria anotação de polígono. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Cria anotação de polilinha. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Cria anotação pop-up no documento PDF. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Cria uma anotação de selo de borracha. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Cria uma anotação de selo de borracha. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Cria uma anotação de selo de borracha. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Cria anotação de quadrado-círculo. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Cria anotação de texto no documento PDF |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Cria um link da web em documento PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Cria um link da web em documento PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Cria um link da web em documento PDF. |
| [deleteAttachments](#deleteAttachments--) | <p> Exclui todos os anexos no documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> Exclui todas as imagens do documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Exclui as imagens especificadas na página especificada. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Exclui vários selos na página especificada por índices de selo. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Exclui selo por ID de todas as páginas do documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Exclui selo na página especificada por ID do selo. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Exclui selos com IDs especificados de todas as páginas do documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Exclui selos na página especificada por múltiplos IDs de selo. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Cria anotação de curva. |
| [extractLink](#extractLink--) | <p> Extrai a coleção de instâncias de Link contidas no documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // trabalha com a instância Link } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Obtém um conjunto de parâmetros para a operação de substituição de texto |
| [getStamps](#getStamps-int-) | Retorna um array de selos na página. |
| [getTextEditOptions](#getTextEditOptions--) | Obtém opções de edição de texto. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtém opções de substituição de texto. |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtém opções de pesquisa de texto. |
| [getViewerPreference](#getViewerPreference--) | <p> Retorna a preferência de visualização. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Oculta o selo. Após ocultar, a visibilidade do selo pode ser restaurada com o método ShowStampById. |
| [moveStamp](#moveStamp-int-int-double-double-) | Altera a posição do selo na página. |
| [moveStampById](#moveStampById-int-int-double-double-) | Altera a posição do selo na página. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Remove a ação de abertura do documento. Esta operação é útil ao concatenar vários documentos que utilizam a ação explícita 'GoTo' na inicialização. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> Substitui a imagem especificada na página especificada do documento PDF por outra imagem. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Substitui texto no arquivo PDF na página especificada. </p> <hr> <pre> O exemplo demonstra como substituir texto em documento PDF na página especificada. // abre o documento Document doc = new Document(inFile); // cria objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // altera o texto editor.replaceText("hello world", 1, "hi world"); // salva o documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // alterar texto com fonte especificada editor.replaceText(\"hello world\", 1, \"hi world\", textState); // salvar documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> Substitui texto no arquivo PDF. </p> <hr> <pre> O exemplo demonstra como substituir texto em um documento PDF. Por padrão, ele substitui o primeiro texto encontrado. // abrir documento Document doc = new Document(inFile); // criar objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // alterar texto editor.replaceText(\"hello world\", \"hi world\"); // salvar documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> Substitui texto no arquivo PDF e define o tamanho da fonte. </p> <hr> <pre> O exemplo demonstra como substituir texto e definir o tamanho da fonte para o novo texto. // abrir documento Document doc = new Document(inFile); // criar fonte e marcá-la para incorporação com.aspose.pdf.Font font = FontRepository.FindFont(\"Courier New\"); font.isEmbedded ( true); // criar objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // alterar texto com fonte especificada editor.replaceText(\"hello world\", \"hi world\", 14); // salvar documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // alterar texto com fonte especificada editor.replaceText(\"hello world\", \"hi world\", textState); // salvar documento doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Defina um conjunto de parâmetros para a operação de substituição de texto |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Define opções de edição de texto. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Define opções de substituição de texto. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Define opções de pesquisa de texto. |
| [showStampById](#showStampById-int-int-) | Exibe o selo que foi ocultado por HiddenStampById. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

Um tipo de evento de documento. Fecha um documento.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

Um tipo de evento de documento. Abre um documento.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

Um tipo de evento de documento. Executa uma ação após a impressão.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

Um tipo de evento de documento. Executa uma ação após a gravação.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

Um tipo de evento de documento. Executa uma ação antes da impressão.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

Um tipo de evento de documento. Executa uma ação antes da gravação.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

O construtor do objeto PdfContentEditor.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
O construtor do objeto PdfContentEditor.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Adiciona ação adicional para o evento do documento. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Adiciona anexo de documento sem anotação. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Adiciona anexo de documento sem anotação. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Associa um fluxo PDF para edição.

### bindPdf {#bindPdf-java.lang.String-}
Associa um arquivo PDF para edição.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Altera a preferência de visualização. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| viewerAttribution |  | A atribuição de visualização definida na classe ViewerPreference. |

### close {#close--}
```
public void close()
```

Fecha o documento aberto.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
Cria um link para iniciar um aplicativo no documento PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Cria um link para iniciar um aplicativo no documento PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Cria um link para iniciar um aplicativo no documento PDF.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Cria um marcador com a ação especificada.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Cria anotação de cursor.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Cria um link para ações personalizadas no documento PDF.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Cria anotação de anexo de arquivo.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Cria anotação de anexo de arquivo.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
Cria anotação de texto livre no documento PDF

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
Cria um link para JavaScript no documento PDF.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Cria anotação de linha.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
Cria um link local no documento PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
Cria um link local no documento PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Cria um link local no documento PDF.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Cria anotação de marcação no documento PDF.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Cria um link para outra página de documento PDF.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Cria um link para outra página de documento PDF.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Cria um link para outra página de documento PDF.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Cria anotação de polígono.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Cria anotação de polilinha.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
Cria anotação pop-up no documento PDF.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Cria uma anotação de selo de borracha.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Cria uma anotação de selo de borracha.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Cria uma anotação de selo de borracha.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Cria anotação de quadrado-círculo.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
Cria anotação de texto no documento PDF

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
Cria um link da web em documento PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Cria um link da web em documento PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Cria um link da web em documento PDF.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> Exclui todos os anexos no documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> Exclui todas as imagens do documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Exclui as imagens especificadas na página especificada. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página na qual as imagens devem ser excluídas. |
| index |  | Um array representa os índices das imagens. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Exclui vários selos na página especificada por índices de selo. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Número da página onde o selo será excluído. |
| index |  | Índices de selo. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Exclui selo por ID de todas as páginas do documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stampId |  | Identificador do selo que deve ser excluído. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Exclui selo na página especificada por ID do selo. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Número da página onde o selo será excluído. |
| stampId |  | Identificador do selo que deve ser excluído. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Exclui selos com IDs especificados de todas as páginas do documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stampIds |  | Array de IDs de selo. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Exclui selos na página especificada por múltiplos IDs de selo. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Número da página onde os selos serão excluídos. |
| stampIds |  | Array de IDs de selo. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Cria anotação de curva.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> Extrai a coleção de instâncias de Link contidas no documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // trabalha com a instância Link } </pre>

**Returns:**
A coleção de objetos Link

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Obtém um conjunto de parâmetros para a operação de substituição de texto

**Returns:**
Elemento ReplaceTextStrategy

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Retorna um array de selos na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Número da página onde os selos serão pesquisados. |

**Returns:**
Array de selos.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtém opções de edição de texto.

**Returns:**
Elemento TextEditOptions

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Obtém opções de substituição de texto.

**Returns:**
Elemento TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtém opções de pesquisa de texto.

**Returns:**
Elemento TextSearchOptions

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Retorna a preferência de visualização. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
Retorna conjunto de flags ViewerPrefernece

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Oculta o selo. Após ocultar, a visibilidade do selo pode ser restaurada com o método ShowStampById.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Número da página. |
| stampId |  | Identificador do selo que deve ser ocultado. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Altera a posição do selo na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Número da página. |
| stampIndex |  | Índice do selo na página. |
| x |  | Nova posição horizontal do selo. |
| y |  | Nova posição vertical do selo. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Altera a posição do selo na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Número da página. |
| stampId |  | Identificador do selo que deve ser movido. |
| x |  | Nova posição horizontal do selo na página. |
| y |  | Nova posição vertical do selo na página. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Remove a ação de abertura do documento. Esta operação é útil ao concatenar vários documentos que utilizam a ação explícita 'GoTo' na inicialização. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> Substitui a imagem especificada na página especificada do documento PDF por outra imagem. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Substitui texto no arquivo PDF na página especificada. </p> <hr> <pre> O exemplo demonstra como substituir texto em documento PDF na página especificada. // abre o documento Document doc = new Document(inFile); // cria objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // altera o texto editor.replaceText("hello world", 1, "hi world"); // salva o documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Substitui texto no arquivo PDF na página especificada. {@code TextState} objeto (família de fontes, cor) pode ser especificado para o texto substituído. </p> <hr> <pre> O exemplo demonstra como substituir texto na primeira página do documento PDF e definir as propriedades de texto {@code TextState} para o novo texto. // abrir documento Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Courier New\"); font.isEmbedded ( true); // criar objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // criar objeto textState com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // alterar texto com a fonte especificada editor.replaceText(\"hello world\", 1, \"hi world\", textState); // salvar documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> Substitui texto no arquivo PDF. </p> <hr> <pre> O exemplo demonstra como substituir texto em um documento PDF. Por padrão, ele substitui o primeiro texto encontrado. // abrir documento Document doc = new Document(inFile); // criar objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // alterar texto editor.replaceText(\"hello world\", \"hi world\"); // salvar documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> Substitui texto no arquivo PDF e define o tamanho da fonte. </p> <hr> <pre> O exemplo demonstra como substituir texto e definir o tamanho da fonte para o novo texto. // abrir documento Document doc = new Document(inFile); // criar fonte e marcá-la para incorporação com.aspose.pdf.Font font = FontRepository.FindFont(\"Courier New\"); font.isEmbedded ( true); // criar objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // alterar texto com fonte especificada editor.replaceText(\"hello world\", \"hi world\", 14); // salvar documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Substitui texto no arquivo PDF usando o objeto {@code TextState} especificado. </p> <hr> <pre> O exemplo demonstra como substituir texto e definir as propriedades de texto {@code TextState} para o novo texto. Document doc = new Document(inFile); // Criar fonte e marcá-la para ser incorporada com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Courier New\"); font.isEmbedded ( true); // criar objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // criar objeto textState com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // alterar texto com a fonte especificada editor.replaceText(\"hello world\", \"hi world\", textState); // salvar documento doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Defina um conjunto de parâmetros para a operação de substituição de texto

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Define opções de edição de texto.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Define opções de substituição de texto.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Define opções de pesquisa de texto.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

Exibe o selo que foi ocultado por HiddenStampById.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | Número da página. |
| stampId |  | Identificador do selo que deve ser exibido. |
