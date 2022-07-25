---
title: Aspose.Pdf.Facades
second_title: Aspose.PDF per .NET API Reference
description: Il Aspose.Pdf.Facciatenamespace fornisce classi originariamente provenienti da Aspose.Pdf.Kit. Queste classi vengono utilizzate per manipolare documenti eseguendo operazioni come concatenare stampare firmare annotare ecc. ma ad alto livello senza accedere alla struttura interna di un documento.
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/
---
Il **Aspose.Pdf.Facciate**namespace fornisce classi originariamente provenienti da Aspose.Pdf.Kit. Queste classi vengono utilizzate per manipolare documenti eseguendo operazioni come concatenare, stampare, firmare, annotare ecc. ma ad alto livello senza accedere alla struttura interna di un documento.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AutoFiller](./autofiller) | Rappresenta una classe per ricevere dati dal database o da un'altra fonte di dati, li riempie nei campi progettati del modello pdf e infine genera un nuovo file pdf o flusso. Ha due modalità di input del file modello: input come flusso o file pdf . Ha quattro tipi di modalità di output: un flusso unito, un file unito, molti piccoli flussi, molti piccoli file. Può ricevere dati letterali contenuti in un System.Data.DataTable. |
| [Bookmark](./bookmark) | Rappresenta un segnalibro. |
| [Bookmarks](./bookmarks) | Rappresenta una raccolta di[`Bookmark`](../aspose.pdf.facades/bookmark) oggetti. |
| [DocumentPrivilege](./documentprivilege) | Rappresenta i privilegi per l'accesso al file Pdf. Fare riferimento a[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity) . Esistono 4 modi per utilizzare questa classe: 1.Utilizzare direttamente il privilegio predefinito. 2. Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basarsi su un privilegio predefinito e modificare alcune specifiche combinazioni di autorizzazioni Adobe Professional. 4. Mescola il modo2 e il modo3. |
| [Facade](./facade) | Classe facciata base. |
| [FontColor](./fontcolor) | Classe che rappresenta il colore del testo. |
| [Form](./form) | Classe che rappresenta l'oggetto modulo Acro. |
| [FormattedText](./formattedtext) | Classe che rappresenta il testo formattato. Contiene informazioni sul testo e il suo colore, dimensione, stile. |
| [FormDataConverter](./formdataconverter) | Rappresenta una classe per convertire i dati da un formato all'altro. Può convertire i dati in fdf/xml/pdf/xfdf in OLEDB/OdbcDB. Può anche convertire i dati in OLEDB/OdbcDB nei dati in fdf/xml/xfdf. Può convertire l'fdf in xml con il tag "denominato". |
| [FormEditor](./formeditor) | Classe per la modifica dei moduli (inserimento/cancellazione campo ecc.) |
| [FormFieldFacade](./formfieldfacade) | Classe per rappresentare le proprietà del campo. |
| [LineInfo](./lineinfo) | Rappresenta le informazioni della linea. |
| [PdfAnnotationEditor](./pdfannotationeditor) | Rappresenta una classe per lavorare con le annotazioni di documenti PDF (commenti). |
| [PdfBookmarkEditor](./pdfbookmarkeditor) | Rappresenta una classe per lavorare con i segnalibri del file PDF, inclusa la creazione, la modifica, l'esportazione, l'importazione e l'eliminazione. |
| [PdfContentEditor](./pdfcontenteditor) | Rappresenta una classe per modificare il contenuto del file PDF. |
| [PdfConverter](./pdfconverter) | Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supporta ora BMP, JPEG, PNG e TIFF. Contenuto supportato nei pdf: immagini, modulo, commento. |
| [PdfExtractor](./pdfextractor) | Classe per estrarre immagini e testo da documento PDF. |
| [PdfFileEditor](./pdffileeditor) | Esegue operazioni con file PDF: concatenazione, divisione, estrazione pagine, creazione libretto, ecc. |
| [PdfFileInfo](./pdffileinfo) | Rappresenta una classe per l'accesso alle metainformazioni del documento PDF. |
| [PdfFileMend](./pdffilemend) | Rappresenta una classe per l'aggiunta di testi e immagini sulle pagine di un documento PDF esistente. |
| [PdfFileSanitization](./pdffilesanitization) | Rappresenta l'API di sanificazione e ripristino. Usalo se non puoi creare/aprire documenti in altro modo. |
| [PdfFileSecurity](./pdffilesecurity) | Rappresenta la crittografia o la decrittografia di un file Pdf con password del proprietario o dell'utente, modifica dell'impostazione di sicurezza e password. |
| [PdfFileSignature](./pdffilesignature) | Rappresenta una classe per firmare un file pdf con un certificato. |
| [PdfFileStamp](./pdffilestamp) | Classe per l'aggiunta di timbri (filigrana o sfondo) ai file PDF. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper) | Classe per la rimozione di tutto il codice Java Script. |
| [PdfPageEditor](./pdfpageeditor) | Rappresenta una classe per modificare la pagina del file PDF, inclusa la rotazione della pagina, lo zoom della pagina, lo spostamento della posizione e la modifica delle dimensioni della pagina. |
| [PdfPrintPageInfo](./pdfprintpageinfo) | Rappresenta un oggetto che contiene informazioni sulla pagina di stampa corrente. |
| [PdfProducer](./pdfproducer) | Rappresenta una classe per produrre PDF da altri formati.  Questo esempio mostra come produrre file Pdf da file CGM. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler) | Rappresenta il metodo che gestisce l'evento QueryPageSettings di un PrintDocument. |
| [PdfViewer](./pdfviewer) | Rappresenta una classe per visualizzare o stampare un pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata) | Classe per la manipolazione con metadati XMP. |
| [ReplaceTextStrategy](./replacetextstrategy) | Questa classe contiene parametri che definiscono il comportamento di PdfContentEditor quando viene eseguita l'operazione ReplaceText. |
| [SaveableFacade](./saveablefacade) | Classe base per tutte le facciate salvabili. |
| [Stamp](./stamp) | Timbro di rappresentazione della classe. |
| [StampInfo](./stampinfo) | Classe che rappresenta le informazioni sul timbro. |
| [TextProperties](./textproperties) | Rappresenta le proprietà del testo come: dimensione del testo, colore, stile ecc. |
| [ViewerPreference](./viewerpreference) | Descrive le preferenze del visualizzatore (modalità pagina, modalità pagina non a schermo intero, layout di pagina). |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IFacade](./ifacade) | Interfaccia generale per le facciate che definisce i metodi comuni per le facciate. |
| [ISaveableFacade](./isaveablefacade) | Interfaccia di facciata che definisce i metodi comuni a tutte le facciate salvabili. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [Algorithm](./algorithm) | Rappresenta gli algoritmi che possono essere utilizzati per crittografare il documento pdf. |
| [AutoRotateMode](./autorotatemode) | Direzione di rotazione durante la stampa del documento. |
| [BlendingColorSpace](./blendingcolorspace) | La classe rappresenta la fusione dello spazio colore. |
| [DataType](./datatype) | Enumera le definizioni dei tipi di campo. |
| [DefaultMetadataProperties](./defaultmetadataproperties) | Enumerazione delle proprietà XMP standard. |
| [EncodingType](./encodingtype) | Enumera i tipi di codifica del testo utilizzando. |
| [FieldType](./fieldtype) | Enumerazione dei possibili tipi di campo. |
| [FontStyle](./fontstyle) | Enumera 14 tipi di font. |
| [ImageMergeMode](./imagemergemode) | Rappresenta le modalità per unire le immagini. |
| [KeySize](./keysize) | Definisce diverse dimensioni delle chiavi che possono essere utilizzate per crittografare i documenti PDF. |
| [PositioningMode](./positioningmode) | Definisce la modalità di posizionamento. I valori possibili includono Legacy (compatibilità con le versioni precedenti) e Current (metodo di calcolo della posizione del testo aggiornato) |
| [PropertyFlag](./propertyflag) | Enumerazione di possibili flag di campo. |
| [StampType](./stamptype) | Descrive i tipi di timbro. |
| [SubmitFormFlag](./submitformflag) | Enumerazione di possibili flag di invio form. |
| [WordWrapMode](./wordwrapmode) | Definisce le strategie di ritorno a capo automatico |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
