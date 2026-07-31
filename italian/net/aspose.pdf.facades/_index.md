---
title: "Aspose.Pdf.Facades"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Il namespace Aspose.Pdf.Facades fornisce classi originariamente provenienti da Aspose.Pdf.Kit. Queste classi sono usate per manipolare i documenti eseguendo operazioni come concatenazione, aggiunta di timbri, firma, annotazione, ecc., ma a livello alto senza accedere alla struttura interna di un documento."
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/
---
Lo spazio dei nomi **Aspose.Pdf.Facades** fornisce classi originariamente provenienti da Aspose.Pdf.Kit. Queste classi sono usate per manipolare i documenti eseguendo operazioni come concatenazione, aggiunta di filigrane, firma, annotazione, ecc., ma a livello alto senza accesso alla struttura interna del documento.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AutoFiller](./autofiller/) | Rappresenta una classe per ricevere dati da un database o da altre origini dati, inserirli nei campi progettati del modello PDF e infine generare un nuovo file PDF o stream. Dispone di due modalità di input per il file modello: input come stream o come file PDF. Ha quattro tipi di modalità di output: un stream unificato, un file unificato, molti piccoli stream, molti piccoli file. Può ricevere dati letterali contenuti in un System.Data.DataTable. |
| [BDCProperties](./bdcproperties/) | Proprietà dell'operatore BDC. |
| [Bookmark](./bookmark/) | Rappresenta un segnalibro. |
| [Bookmarks](./bookmarks/) | Rappresenta una raccolta di oggetti [`Bookmark`](../aspose.pdf.facades/bookmark/). |
| [DocumentPrivilege](./documentprivilege/) | Rappresenta i privilegi per l'accesso a file Pdf. Vedi [`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/). Ci sono 4 modalità di utilizzo di questa classe: 1. Utilizzare direttamente il privilegio predefinito. 2. Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basarsi su un privilegio predefinito e modificare una combinazione specifica di autorizzazioni di Adobe Professional. 4. Mescolare il modo 2 e il modo 3. |
| [Facade](./facade/) | Classe di facciata di base. |
| [FontColor](./fontcolor/) | Classe che rappresenta il colore del testo. |
| [Form](./form/) | Classe che rappresenta l'oggetto Acro form. |
| [FormattedText](./formattedtext/) | Classe che rappresenta il testo formattato. Contiene informazioni sul testo e sul suo colore, dimensione, stile. |
| [FormDataConverter](./formdataconverter/) | Rappresenta una classe per convertire i dati da un formato a un altro. Può convertire i dati in fdf/xml/pdf/xfdf nel OLEDB/OdbcDB. Può anche convertire i dati nel OLEDB/OdbcDB nei dati in fdf/xml/xfdf. Può convertire il fdf in xml con un tag "hard-named". |
| [FormEditor](./formeditor/) | Classe per modificare i moduli (aggiunta/cancellazione di campi ecc) |
| [FormFieldFacade](./formfieldfacade/) | Classe per rappresentare le proprietà del campo. |
| [LineInfo](./lineinfo/) | Rappresenta le informazioni della linea. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Rappresenta una classe per lavorare con le annotazioni (commenti) dei documenti PDF. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Rappresenta una classe per gestire i segnalibri dei file PDF, inclusi creazione, modifica, esportazione, importazione e cancellazione. |
| [PdfContentEditor](./pdfcontenteditor/) | Rappresenta una classe per modificare il contenuto di un file PDF. |
| [PdfConverter](./pdfconverter/) | Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supportando attualmente BMP, JPEG, PNG e TIFF. Contenuto supportato nei pdf: immagini, moduli, commenti. |
| [PdfExtractor](./pdfextractor/) | Classe per estrarre immagini e testo da un documento PDF. |
| [PdfFileEditor](./pdffileeditor/) | Implementa operazioni sui file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc. |
| [PdfFileInfo](./pdffileinfo/) | Rappresenta una classe per accedere alle meta‑informazioni di un documento PDF. |
| [PdfFileMend](./pdffilemend/) | Rappresenta una classe per aggiungere testi e immagini sulle pagine di un documento PDF esistente. |
| [PdfFileSanitization](./pdffilesanitization/) | Rappresenta l'API di sanificazione e recupero. Usala se non riesci a creare/aprire documenti in altro modo. |
| [PdfFileSecurity](./pdffilesecurity/) | Rappresenta la cifratura o decifratura di un file Pdf con password proprietario o utente, modificando le impostazioni di sicurezza e la password. |
| [PdfFileSignature](./pdffilesignature/) | Rappresenta una classe per firmare un file pdf con un certificato. |
| [PdfFileStamp](./pdffilestamp/) | Classe per aggiungere timbri (filigrana o sfondo) ai file PDF. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Classe per rimuovere tutto il codice Java Script. |
| [PdfPageEditor](./pdfpageeditor/) | Rappresenta una classe per modificare la pagina di un file PDF, includendo rotazione, zoom, spostamento e cambiamento delle dimensioni della pagina. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Rappresenta un oggetto che contiene le informazioni sulla pagina di stampa corrente. |
| [PdfProducer](./pdfproducer/) | Rappresenta una classe per produrre PDF da altri formati. Questo esempio mostra come produrre un file Pdf da un file CGM. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Rappresenta il metodo che gestisce l'evento [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) di un [`PdfViewer`](../aspose.pdf.facades/pdfviewer/). |
| [PdfViewer](./pdfviewer/) | Rappresenta una classe per visualizzare o stampare un pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Classe per la manipolazione dei metadati XMP. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Questa classe contiene parametri che definiscono il comportamento di PdfContentEditor quando viene eseguita l'operazione ReplaceText. |
| [SaveableFacade](./saveablefacade/) | Classe base per tutte le facades salvabili. |
| [SignatureName](./signaturename/) | Rappresenta una classe per un nome di firma. |
| [Stamp](./stamp/) | Classe che rappresenta un timbro. |
| [StampInfo](./stampinfo/) | Classe che rappresenta le informazioni del timbro. |
| [TextProperties](./textproperties/) | Rappresenta le proprietà del testo come: dimensione del testo, colore, stile ecc. |
| [ViewerPreference](./viewerpreference/) | Descrive le preferenze del visualizzatore (modalità pagina, modalità pagina non a schermo intero, layout pagina). |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IFacade](./ifacade/) | Interfaccia generale di facciata che definisce i metodi comuni delle facciate. |
| [ISaveableFacade](./isaveablefacade/) | Interfaccia di facciata che definisce i metodi comuni a tutte le facciate salvabili. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [Algorithm](./algorithm/) | Rappresenta gli algoritmi che possono essere usati per crittografare un documento pdf. |
| [AutoRotateMode](./autorotatemode/) | Direzione della rotazione quando il documento è stampato. |
| [BlendingColorSpace](./blendingcolorspace/) | Classe che rappresenta lo spazio colore di fusione. |
| [DataType](./datatype/) | Enumera le definizioni dei tipi di campo. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumerazione delle proprietà XMP standard. |
| [EncodingType](./encodingtype/) | Enumera i tipi di codifica del testo utilizzati. |
| [FieldType](./fieldtype/) | Enumerazione dei possibili tipi di campo. |
| [FontStyle](./fontstyle/) | Enumera 14 tipi di carattere. |
| [ImageMergeMode](./imagemergemode/) | Rappresenta le modalità per unire le immagini. |
| [KeySize](./keysize/) | Definisce diverse dimensioni di chiave che possono essere usate per crittografare documenti pdf. |
| [PositioningMode](./positioningmode/) | Definisce la modalità di posizionamento. I valori possibili includono Legacy (compatibilità retroattiva) e Current (metodo aggiornato di calcolo della posizione del testo). |
| [PropertyFlag](./propertyflag/) | Enumerazione delle possibili flag di campo. |
| [StampType](./stamptype/) | Descrive i tipi di timbro. |
| [SubmitFormFlag](./submitformflag/) | Enumerazione delle possibili flag di invio del modulo. |
| [WordWrapMode](./wordwrapmode/) | Definisce le strategie di a capo automatico. |


