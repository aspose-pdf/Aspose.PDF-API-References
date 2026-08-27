---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il pacchetto com.aspose.pdf.facades fornisce classi originariamente provenienti da Aspose.Pdf.Kit."
type: docs
weight: 180
url: /it/java/com.aspose.pdf.facades/
---
Il pacchetto com.aspose.pdf.facades fornisce classi originariamente provenienti da Aspose.Pdf.Kit.

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IFacade](./ifacade/) | Interfaccia generale di facciata che definisce i metodi comuni delle facciate. |
| [IForm](./iform/) | Classe che rappresenta l'oggetto del modulo Acro. |
| [IFormEditor](./iformeditor/) | Classe per la modifica dei moduli (aggiunta/eliminazione di campi ecc.) |
| [IPdfFileEditor](./ipdffileeditor/) | Implementa operazioni sui file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc. |
| [IPdfFileStamp](./ipdffilestamp/) | Interfaccia per aggiungere timbri (filigrana o sfondo) ai file PDF. |
| [ISaveableFacade](./isaveablefacade/) | Interfaccia di facciata che definisce i metodi comuni a tutte le facciate salvabili. |
## Classi

| Classe | Descrizione |
| --- | --- |
| [AlignmentType](./alignmenttype/) | La classe contiene possibili tipi di allineamento. Utilizzare HorizontalAlignment invece. |
| [AutoRotateMode](./autorotatemode/) | Direzione della rotazione quando il documento è stampato. |
| [BDCProperties](./bdcproperties/) | Proprietà dell'operatore BDC. |
| [Bookmark](./bookmark/) | Rappresenta un segnalibro. |
| [Bookmarks](./bookmarks/) | Rappresenta una collezione di oggetti {@code Bookmark}. |
| [CgmPdfProducer](./cgmpdfproducer/) | Rappresenta una classe per generare PDF dal formato Computer Graphics Metafile (CGM). |
| [DataType](./datatype/) | Enumera le definizioni dei tipi di campo. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumerazione delle proprietà XMP standard. |
| [DocumentPrivilege](./documentprivilege/) | Rappresenta i privilegi per accedere a un file Pdf. Vedi {@code PdfFileSecurity}. Ci sono 4 modi di utilizzare questa classe: 1. Utilizzare direttamente un privilegio predefinito. 2. Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basarsi su un privilegio predefinito e modificare una combinazione specifica di autorizzazioni Adobe Professional. 4. Mescolare il modo 2 e il modo 3. //Way1: Utilizzare direttamente un privilegio predefinito. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Basarsi su un privilegio predefinito e modificare una combinazione specifica di autorizzazioni Adobe Professional. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mescolare il modo 2 e il modo 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Enumera i tipi di codifica del testo utilizzati. |
| [Facade](./facade/) | Classe facciata di base. |
| [FontColor](./fontcolor/) | Classe che rappresenta il colore del testo. |
| [Form](./form/) | Classe che rappresenta l'oggetto del modulo Acro. |
| [Form.ImportStatus](./form.importstatus/) | Stato del campo importato |
| [FormattedText](./formattedtext/) | Classe che rappresenta il testo formattato. Contiene informazioni sul testo e sul suo colore, dimensione, stile. |
| [FormEditor](./formeditor/) | Classe per la modifica dei moduli (aggiunta/eliminazione di campi ecc.) |
| [FormEditorWeb](./formeditorweb/) | Classe per modificare i moduli (aggiunta/cancellazione di campi ecc) |
| [FormFieldFacade](./formfieldfacade/) | Classe per rappresentare le proprietà del campo. |
| [FormWeb](./formweb/) | Rappresenta l'interfaccia del modulo Acro. |
| [InternalHelper](./internalhelper/) | Classe di supporto |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: dimensione della pagina risultante (larghezza, altezza) in unità di spazio predefinite o in percentuale della dimensione della pagina iniziale; margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuale della dimensione della pagina iniziale; alcuni valori possono essere lasciati null per il calcolo automatico. Questi valori saranno calcolati dal resto della dimensione della pagina dopo il calcolo dei valori specificati esplicitamente. Per esempio: se la larghezza della pagina = 100 e la nuova larghezza della pagina specificata è 60 unità, i margini sinistro e destro vengono calcolati automaticamente: (100 - 60) / 2 = 15. Questa classe è utilizzata nel metodo ResizeContents. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Valore del margine o della dimensione del contenuto specificato in percentuale delle unità di spazio predefinite. Questa classe è utilizzata in ContentsResizeParameters. |
| [LineInfo](./lineinfo/) | Rappresenta le informazioni della linea. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Rappresenta una classe per lavorare con le annotazioni (commenti) dei documenti PDF. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Rappresenta una classe per gestire i segnalibri dei file PDF, inclusi creazione, modifica, esportazione, importazione e cancellazione. |
| [PdfContentEditor](./pdfcontenteditor/) | Rappresenta una classe per modificare il contenuto dei file PDF. |
| [PdfConverter](./pdfconverter/) | Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supportando attualmente BMP, JPEG, PNG e TIFF. Contenuto supportato nei pdf: immagini, moduli, commenti. |
| [PdfExtractor](./pdfextractor/) | Classe per estrarre immagini e testo da un documento PDF. |
| [PdfFileEditor](./pdffileeditor/) | Implementa operazioni sui file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Azione eseguita quando si incontra un file corrotto nel processo di concatenazione. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Rappresenta una classe con metodo astratto solitamente fornito dal chiamante e gestisce gli eventi di avanzamento provenienti dalla concatenazione. Di solito tale gestore fornito dal cliente può essere usato per mostrare il progresso totale della concatenazione sulla console o in una barra di avanzamento. Rappresenta le informazioni sull'evento di avanzamento verificatosi. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Classe che fornisce informazioni sui file corrotti durante la concatenazione. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Dati della posizione dell'interruzione di pagina. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | Questa classe rappresenta le informazioni sul progresso della concatenazione che possono essere utilizzate in un'applicazione esterna. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | Questo enum descrive i possibili tipi di eventi di progresso che possono verificarsi durante la concatenazione. |
| [PdfFileEditorWeb](./pdffileeditorweb/) | Rappresenta la classe PdfFileEditorWeb. Implementa operazioni con file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc. |
| [PdfFileInfo](./pdffileinfo/) | Rappresenta una classe per accedere alle meta‑informazioni del documento PDF. |
| [PdfFileMend](./pdffilemend/) | Rappresenta una classe per aggiungere testi e immagini sulle pagine di un documento PDF esistente. |
| [PdfFileSanitization](./pdffilesanitization/) | Rappresenta l'API di sanificazione e recupero. Usala se non riesci a creare/aprire i documenti in altro modo. |
| [PdfFileSecurity](./pdffilesecurity/) | Rappresenta la cifratura o decifratura di un file Pdf con password proprietario o utente, la modifica delle impostazioni di sicurezza e della password. |
| [PdfFileSignature](./pdffilesignature/) | Rappresenta una classe per firmare un file pdf con un certificato. |
| [PdfFileStamp](./pdffilestamp/) | Classe per aggiungere timbri (filigrana o sfondo) ai file PDF. |
| [PdfFileStampWeb](./pdffilestampweb/) | Classe per aggiungere timbri (filigrana o sfondo) ai file PDF. Abilita il lavoro con HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Classe per rimuovere tutto il codice Java Script. |
| [PdfPageEditor](./pdfpageeditor/) | Rappresenta una classe per modificare la pagina del file PDF, inclusa la rotazione della pagina, lo zoom, lo spostamento della posizione e la modifica delle dimensioni della pagina. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Rappresenta un oggetto che contiene le informazioni sulla pagina di stampa corrente. |
| [PdfProducer](./pdfproducer/) | <p> Rappresenta una classe per generare PDF da altri formati. </p> <hr> <pre>Questo esempio mostra come produrre un file Pdf da un file CGM. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Rappresenta il metodo che gestisce l'evento QueryPageSettings di un PrintDocument. |
| [PdfViewer](./pdfviewer/) | Rappresenta una classe per visualizzare o stampare un pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Classe per la manipolazione dei metadati XMP. |
| [PositioningMode](./positioningmode/) | Definisce la modalità di posizionamento. I valori possibili includono Legacy (compatibilità retroattiva) e Current (metodo aggiornato di calcolo della posizione del testo). |
| [PropertyFlag](./propertyflag/) | Enumerazione dei possibili flag di campo. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Questa classe contiene i parametri che definiscono il comportamento di PdfContentEditor quando viene eseguita l'operazione ReplaceText. |
| [SaveableFacade](./saveablefacade/) | <p> Classe base per tutte le facciate salvabili. |
| [SignatureName](./signaturename/) | Rappresenta una classe per un nome di firma. Rappresenta un nome di firma più preciso. Utilizzato al posto dei nomi stringa. Consente di presentare firme con gli stessi nomi stringa. |
| [Stamp](./stamp/) | Classe che rappresenta un timbro. |
| [StampInfo](./stampinfo/) | Classe che rappresenta le informazioni del timbro. |
| [TextProperties](./textproperties/) | Rappresenta le proprietà del testo come: dimensione del testo, colore, stile ecc. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Classe che rappresenta i possibili valori di allineamento verticale. Usa VerticalAlignment invece |
| [ViewerPreference](./viewerpreference/) | Descrive le preferenze del visualizzatore (modalità pagina, modalità pagina non a schermo intero, layout pagina). |
| [WordWrapMode](./wordwrapmode/) | Definisce le strategie di interruzione delle parole |
## Enums

| Enum | Descrizione |
| --- | --- |
| [Algorithm](./algorithm/) | Rappresenta gli algoritmi che possono essere usati per crittografare un documento PDF. |
| [BlendingColorSpace](./blendingcolorspace/) | La classe rappresenta lo spazio colore di fusione. |
| [FieldType](./fieldtype/) | Enumerazione dei possibili tipi di campo. |
| [FontStyle](./fontstyle/) | Enumera 14 tipi di carattere. |
| [ImageMergeMode](./imagemergemode/) | Rappresenta le modalità per unire le immagini. |
| [KeySize](./keysize/) | Definisce diverse dimensioni delle chiavi che possono essere usate per crittografare documenti PDF. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Azione da eseguire se il font non contiene il carattere richiesto |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Ambito in cui l'operazione di sostituzione del testo è applicata REPLACE_FIRST per impostazione predefinita |
| [StampType](./stamptype/) | Descrive i tipi di timbro. |
| [SubmitFormFlag](./submitformflag/) | Enumerazione delle possibili flag di invio modulo. |
