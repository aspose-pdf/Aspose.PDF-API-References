---
title: "com.aspose.pdf"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il com.aspose.pdf è un pacchetto radice per tutte le classi della libreria Aspose.PDF per Java che sono o direttamente in esso, come Document, o indirettamente tramite diversi sotto‑pacchetti."
type: docs
weight: 10
url: /it/java/com.aspose.pdf/
---
Il com.aspose.pdf è un pacchetto radice per tutte le classi della libreria Aspose.PDF per Java che sono o direttamente in esso, come Document, o indirettamente tramite diversi sotto‑pacchetti.

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | La procedura di callback per il riconoscimento hocr. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | La procedura di callback per il riconoscimento hocr. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | La procedura di callback per il riconoscimento hocr. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Contiene funzionalità per regolare i font |
| [IAnnotationVisitor](./iannotationvisitor/) | Definisce un Visitor per visitare diverse annotazioni del documento. |
| [IAppointment](./iappointment/) | Rappresenta un'interfaccia generale per azioni e destinazioni. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Interfaccia per le strategie di conversione dello spazio colore. |
| [IDocument](./idocument/) | interfaccia che rappresenta un documento PDF |
| [IFontOptions](./ifontoptions/) | Proprietà utili per regolare il comportamento dei Font |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | Questa interfaccia è dichiarata per la personalizzazione degli algoritmi di quantizzazione. Gli utenti possono implementare la propria realizzazione di questi algoritmi (ad esempio algoritmi basati su codice non gestito). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | Questa interfaccia è dichiarata per la personalizzazione degli algoritmi di quantizzazione. Gli utenti possono implementare la propria realizzazione di questi algoritmi (ad esempio algoritmi basati su codice non gestito). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Definisce un Visitor per visitare diversi operatori PDF. |
| [IPageSetOptions](./ipagesetoptions/) | Definisce le opzioni di conversione relative a un insieme di pagine da convertire. |
| [IPipelineOptions](./ipipelineoptions/) | Definisce le opzioni di conversione relative alla configurazione della pipeline. |
| [ITableElement](./itableelement/) | Questa interfaccia rappresenta un elemento di una tabella esistente estratta da TableAbsorber. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato, che otterrà le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.PDf nel cloud l'accesso diretto ai file di riferimento è impossibile, e del codice personalizzato inserito in un metodo speciale dovrebbe essere utilizzato. Questo delegato definisce la firma di tale metodo personalizzato. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Imposta il flag per indicare se la cartella temporanea sarà usata per ospitare i dati dei font temporanei. / * Vero per impostazione predefinita. / * Usa la memoria heap se valore = false; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | Alla proprietà di questo tipo è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione del salvataggio esterno dell'immagine estratta da SVG generato da PDF e che deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso l'elaborazione (ad esempio il salvataggio personalizzato su stream o su disco) può essere eseguita in quel codice personalizzato e quel codice deve restituire un percorso (o qualsiasi altra stringa senza virgolette) che sarà successivamente incorporato nello SVG generato al posto del percorso originale previsto per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se per qualche motivo l'elaborazione di questo o di quell'altro file deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso come se non esistesse alcun codice personalizzato esterno. |
## Classi

| Classe | Descrizione |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Rappresenta una cella della tabella presente nella pagina |
| [AbsorbedRow](./absorbedrow/) | Rappresenta una riga della tabella presente nella pagina |
| [AbsorbedTable](./absorbedtable/) | Rappresenta la tabella presente nella pagina |
| [ActionCollection](./actioncollection/) | Collezione di azioni |
| [Annotation](./annotation/) | Classe che rappresenta un oggetto di annotazione. |
| [AnnotationActionCollection](./annotationactioncollection/) | Rappresenta la collezione di azioni di annotazione. |
| [AnnotationCollection](./annotationcollection/) | Classe che rappresenta una collezione di annotazioni. |
| [AnnotationFlags](./annotationflags/) | Flag Un insieme di flag binari che specificano varie caratteristiche dell'annotazione. |
| [AnnotationSelector](./annotationselector/) | Questa classe è usata per selezionare le annotazioni utilizzando l'idea del modello Visitor. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Classe per il rendering di testo normale e ricco. |
| [AppearanceDictionary](./appearancedictionary/) | Dizionario di aspetto dell'annotazione che specifica come l'annotazione deve essere presentata visivamente sulla pagina. |
| [ApsLoadOptions](./apsloadoptions/) | Classe che descrive le opzioni di caricamento aps. Opzione per l'importazione dal formato APS XML. |
| [ApsSaveOptions](./apssaveoptions/) | Opzioni di salvataggio per l'esportazione in formato APS XML. |
| [ApsToFlowConverter](./apstoflowconverter/) | Conversione da APS a Flow |
| [Artifact](./artifact/) | Classe che rappresenta l'oggetto PDF Artifact. |
| [ArtifactCollection](./artifactcollection/) | Classe che rappresenta una collezione di artifact. |
| [AutoTaggingSettings](./autotaggingsettings/) | Fornisce impostazioni per la funzionalità di auto-tagging nei documenti PDF. La classe {@link AutoTaggingSettings} consente di configurare le opzioni per il tagging automatico del contenuto PDF. Include proprietà per abilitare o disabilitare l'auto-tagging, specificare una strategia per il riconoscimento dei titoli e definire i livelli dei titoli in base alle dimensioni dei caratteri. |
| [BackgroundArtifact](./backgroundartifact/) | Classe che descrive l'artifact di sfondo. Questo artifact consente di impostare lo sfondo della pagina. |
| [BarcodeField](./barcodefield/) | Classe che rappresenta il campo barcode. |
| [BaseActionCollection](./baseactioncollection/) | Classe che incapsula azioni di base con azioni interattive di pagina/annotazione/campo |
| [BaseOperatorCollection](./baseoperatorcollection/) | Rappresenta la classe base per la collezione di operatori. |
| [BaseParagraph](./baseparagraph/) | Rappresenta un oggetto base astratto che può essere aggiunto alla pagina (doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | La classe descrive l'artefatto di numerazione Bates. |
| [BitmapInfo](./bitmapinfo/) | Oggetto contenente un array di pixel e informazioni bitmap. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Formato pixel bitmap. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Rappresenta un'annotazione Bleed Mark. I segni di sbordamento sono posizionati agli angoli di una pagina stampata per indicare dove la pagina deve essere ritagliata e di quanto può deviare dai segni di taglio. |
| [Border](./border/) | Classe che rappresenta le caratteristiche del bordo dell'annotazione. |
| [BorderInfo](./borderinfo/) | Questa classe rappresenta il bordo per gli elementi grafici. |
| [BorderSide](./borderside/) | I flag enumerano i lati del bordo in forma binaria. |
| [BorderStyleConverter](./borderstyleconverter/) | Rappresenta la classe BorderStyleConverter. |
| [Brush](./brush/) | Questa classe rappresenta un pennello astratto. |
| [BuildVersionInfo](./buildversioninfo/) | Questa classe fornisce informazioni sulla build corrente del prodotto. |
| [ButtonField](./buttonfield/) | La classe rappresenta un campo pulsante. |
| [CaretAnnotation](./caretannotation/) | Classe che rappresenta l'annotazione Caret. |
| [CaretSymbolConverter](./caretsymbolconverter/) | Rappresenta la classe CaretSymbolConverter. |
| [CdrLoadOptions](./cdrloadoptions/) | La classe descrive le opzioni di caricamento CDR. |
| [Cell](./cell/) | Rappresenta una cella della riga della tabella. |
| [Cells](./cells/) | Rappresenta una collezione di celle della riga. |
| [CgmImportOptions](./cgmimportoptions/) | Opzione di importazione per importare dal formato Computer Graphics Metafile (CGM). |
| [CgmLoadOptions](./cgmloadoptions/) | Contiene opzioni per caricare/importare file CGM in un documento PDF. |
| [Characteristics](./characteristics/) | Rappresenta le caratteristiche dell'annotazione. |
| [CharInfo](./charinfo/) | Rappresenta un oggetto di informazioni sul carattere. Fornisce informazioni sul posizionamento dei caratteri. |
| [CharInfoCollection](./charinfocollection/) | <p> Rappresenta la collezione di oggetti CharInfo. </p> <hr> <pre> L'esempio dimostra come iterare attraverso tutti i caratteri e recuperare il carattere //apri documento Document pdfDocument = new Document(inFile); //crea l'oggetto TextFragmentAbsorber per raccogliere tutti gli oggetti di testo della pagina TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accetta l'assorbitore per tutte le pagine pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //ottieni i frammenti di testo estratti TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //itera attraverso i frammenti for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //itera attraverso i segmenti for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //itera attraverso i caratteri {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); //stampa le informazioni di posizione e rettangolo del carattere System.out.println(\"XIndent : \" + charInfo.getPosition().getXIndent()); System.out.println(\"YIndent : \" + charInfo.getPosition().getYIndent()); System.out.println(\"Width : \" + charInfo.getRectangle().getWidth()); System.out.println(\"Height : \" + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Fornisce l'accesso alle informazioni di posizionamento dei caratteri del segmento di testo. </p> |
| [CheckboxField](./checkboxfield/) | Classe che rappresenta il campo checkbox. |
| [ChoiceField](./choicefield/) | Rappresenta la classe base per i campi di scelta. |
| [CircleAnnotation](./circleannotation/) | Classe che rappresenta l'annotazione Circle. |
| [Collection](./collection/) | Rappresenta la classe per Collection(12.3.5 Collections). |
| [CollectionField](./collectionfield/) | Rappresenta una classe di campo dello schema di una raccolta di documenti. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Rappresenta il parametro sottotipo di un campo in una raccolta di schema. |
| [CollectionItem](./collectionitem/) | Rappresenta una classe di elemento della raccolta. L'elemento della raccolta contiene i dati descritti dallo schema della raccolta. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Rappresenta una classe per un valore di elemento della raccolta. |
| [CollectionSchema](./collectionschema/) | Rappresenta una classe che descrive lo \"Schema\" di una raccolta di documenti. |
| [Color](./color/) | Rappresenta una classe per valore di colore che può essere espresso in diversi spazi colore. |
| [ColorBarAnnotation](./colorbarannotation/) | Classe che rappresenta l'annotazione ColorBarAnnotation. La proprietà Color è ignorata, invece viene usato il colore ColorsOfCMYK. Alla creazione, il rapporto tra larghezza e altezza determina l'orientamento dell'annotazione - orizzontale o verticale. Successivamente, verifica che il rettangolo dell'annotazione sia al di fuori del TrimBox e, se non lo è, viene spostato nella posizione più vicina al di fuori del TrimBox, tenendo conto dell'orientamento dell'annotazione. È possibile ridurre la larghezza (altezza) affinché l'annotazione si adatti al di fuori del TrimBox. Se non c'è spazio per il layout, larghezza/altezza può essere impostata a zero (in tal caso, l'annotazione è presente nella pagina, ma non visualizzata). |
| [ColumnInfo](./columninfo/) | Questa classe rappresenta le informazioni di una colonna. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Classe che rappresenta eventi. |
| [ComboBoxField](./comboboxfield/) | Classe che rappresenta il campo Combobox del modulo. |
| [ComHelper](./comhelper/) | <p> Fornisce metodi per i client COM per caricare un documento in Aspose.PDF. </p> <hr> <p> Utilizzare la classe ComHelper per caricare un documento da un file o stream in un oggetto Document in un'applicazione COM. La classe Document fornisce un costruttore predefinito per creare un nuovo documento e fornisce anche costruttori sovraccaricati per caricare un documento da un file o stream. Se si utilizza Aspose.Words da un'applicazione .NET, è possibile usare direttamente tutti i costruttori di Document, ma se si utilizza Aspose.PDF da un'applicazione COM, è disponibile solo il costruttore predefinito di Document. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Classe astratta che rappresenta un'annotazione figura comune. |
| [CompositingParameters](./compositingparameters/) | Rappresenta un oggetto contenente i parametri di composizione grafica dello stato grafico corrente. |
| [ContentsAppender](./contentsappender/) | Esegue modifiche al contenuto solo in modalità APPEND. Questa modalità consente di evitare l'analisi non necessaria e pesante del contenuto prima che venga apportata una modifica. Aggiunge solo nuovi operatori alla fine o all'inizio del contenuto. |
| [Copier](./copier/) | Classe per la copia di oggetti. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Rappresenta i tipi di annotazione che sono posizionati negli angoli della pagina stampata. |
| [CustomExplicitDestination](./customexplicitdestination/) | Rappresenta una destinazione esplicita personalizzata. |
| [CustomSign](./customsign/) | Delegato per la firma personalizzata del documento (Beta). |
| [Dash](./dash/) | Classe che rappresenta il modello di tratteggio della linea. |
| [DateField](./datefield/) | Campo data con visualizzazione calendario. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Descrive l'aspetto predefinito del campo (font, dimensione del testo e colore). |
| [DefaultDirectory](./defaultdirectory/) | Specifica il percorso predefinito per qualche scopo. |
| [DestinationCollection](./destinationcollection/) | Classe che rappresenta la raccolta di tutte le destinazioni (un albero di nomi che mappa stringhe di nome a destinazioni (vedi 12.3.2.3, \"Named Destinations\") e (vedi 7.7.4, \"Name Dictionary\")) nel documento pdf. |
| [DestinationFactory](./destinationfactory/) | Rappresenta la classe DestinationFactory. |
| [DjvuLoadOptions](./djvuloadoptions/) | Classe che descrive le opzioni di caricamento DJVU. |
| [DocMDPSignature](./docmdpsignature/) | Rappresenta la classe del tipo di firma MDP (rilevamento e prevenzione delle modifiche) del documento. |
| [DocSaveOptions](./docsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato Doc |
| [Document](./document/) | Classe che rappresenta un documento PDF. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources(). @deprecated Questa classe è obsoleta. Si prega di utilizzare com.aspose.pdf.optimization.OptimizationOptions al suo posto. |
| [Document.RepairOptions](./document.repairoptions/) | Rappresenta le opzioni per la riparazione di un documento PDF. Questa classe fornisce un modo per personalizzare il processo di riparazione di un documento PDF. |
| [DocumentActionCollection](./documentactioncollection/) | Classe che descrive le azioni eseguite su alcune operazioni con il documento. |
| [DocumentExtensions](./documentextensions/) | Fornisce capacità aggiuntive per la classe Document. |
| [DocumentFactory](./documentfactory/) | Classe che consente di creare/caricare documenti di diversi tipi. |
| [DocumentInfo](./documentinfo/) | Rappresenta le meta‑informazioni di un documento PDF. |
| [DocumentWeb](./documentweb/) | Rappresenta la classe DocumentWeb |
| [Element](./element/) | Classe che rappresenta l'elemento base della struttura logica. |
| [ElementCollection](./elementcollection/) | Raccolta di elementi base della struttura logica. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Classe che rappresenta la collezione di file incorporati. |
| [EncryptedPayload](./encryptedpayload/) | Rappresenta il payload crittografato nella specifica del file. |
| [EpubLoadOptions](./epubloadoptions/) | Contiene le opzioni per il caricamento/importazione di un file EPUB in un documento PDF. |
| [EpubSaveOptions](./epubsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato EPUB |
| [ExcelSaveOptions](./excelsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato Excel |
| [ExplicitDestination](./explicitdestination/) | Rappresenta la classe base per destinazioni esplicite in un documento PDF. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | Rappresenta la classe ExplicitDestinationTypeConverter |
| [ExportFieldsOptions](./exportfieldsoptions/) | Rappresenta la classe base delle opzioni per l'esportazione dei campi modulo. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Rappresenta le opzioni per l'esportazione dei campi modulo in formato Json. Eredita da {@link ExportFieldsOptions} e aggiunge opzioni specifiche per l'esportazione Json. |
| [ExportImportMessages](./exportimportmessages/) | Contiene vari messaggi di errore per le operazioni di esportazione e importazione dei campi modulo. |
| [ExternalSignature](./externalsignature/) | Crea una firma PKCS#7Detached separata utilizzando un X509Certificate2. Supporta smartcard USB, token senza chiavi private esportabili. |
| [FdfReader](./fdfreader/) | Classe che esegue la lettura del formato FDF. Document doc = new Document(\"example.pdf\"); InputStream fdfStream = FileInputStream(\"file.fdf\"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save(\"example_out.pdf\"); |
| [Field](./field/) | Classe base per i campi AcroForm. |
| [FieldSerializationResult](./fieldserializationresult/) | Rappresenta il risultato di un processo di serializzazione di un campo modulo. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Rappresenta lo stato della serializzazione del campo modulo. |
| [FieldValueType](./fieldvaluetype/) | Rappresenta il tipo di valore del campo in una raccolta di schema. |
| [FigureElement](./figureelement/) | Classe che rappresenta la figura della struttura logica. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Classe che descrive l'annotazione di allegato file. |
| [FileFontSource](./filefontsource/) | Rappresenta una singola origine di file di carattere. |
| [FileHyperlink](./filehyperlink/) | Rappresenta l'oggetto collegamento ipertestuale del file. |
| [FileIconConverter](./fileiconconverter/) | Rappresenta la classe FileIconConverter |
| [FileParams](./fileparams/) | Definisce un dizionario di parametri di file incorporato che deve contenere informazioni aggiuntive specifiche del file. |
| [FileSelectBoxField](./fileselectboxfield/) | Campo per l'elemento casella di selezione file. |
| [FileSpecification](./filespecification/) | Classe che rappresenta un file incorporato. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far rientrare interamente il suo riquadro di delimitazione nella finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il riquadro di delimitazione nella finestra nell'altra dimensione. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata verticale superiore posizionata sul bordo superiore della finestra e i contenuti della pagina ingranditi appena a sufficienza per far rientrare l'intera larghezza del suo riquadro di delimitazione nella finestra. Un valore nullo per top indica che il valore corrente di quel parametro deve essere mantenuto invariato. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata orizzontale sinistra posizionata sul bordo sinistro della finestra e i contenuti della pagina ingranditi appena a sufficienza per far rientrare l'intera altezza del suo riquadro di delimitazione nella finestra. Un valore nullo per left indica che il valore corrente di quel parametro deve essere mantenuto invariato. |
| [FitExplicitDestination](./fitexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far rientrare l'intera pagina nella finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando la pagina nella finestra nell'altra dimensione. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata verticale superiore posizionata sul bordo superiore della finestra e i contenuti della pagina ingranditi appena a sufficienza per far rientrare l'intera larghezza della pagina nella finestra. Un valore nullo per top indica che il valore corrente di quel parametro deve essere mantenuto invariato. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far rientrare interamente il rettangolo specificato dalle coordinate left, bottom, right e top nella finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo nella finestra nell'altra dimensione. Un valore nullo per uno qualsiasi dei parametri può provocare un comportamento imprevedibile. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata orizzontale sinistra posizionata sul bordo sinistro della finestra e i contenuti della pagina ingranditi appena a sufficienza per far rientrare l'intera altezza della pagina nella finestra. Un valore nullo per left indica che il valore corrente di quel parametro deve essere mantenuto invariato. |
| [FixedPrint](./fixedprint/) | Rappresenta i dati di stampa fissi dell'annotazione Watermark. |
| [FloatingBox](./floatingbox/) | Rappresenta un FloatingBox in un documento PDF. FloatingBox è posizionato in modo personalizzato. |
| [FlowConverter](./flowconverter/) | Converti il documento PDF in formati Flow (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX in modalità EnchanedFlow, TableAbsorber in modalità FlowEngine. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Passaggio di dati dalla libreria Flow a TableAbsorber |
| [FolderFontSource](./folderfontsource/) | Rappresenta la cartella che contiene i file di carattere. |
| [Font](./font/) | <p> Rappresenta l'oggetto font. </p> <hr> <pre> L'esempio dimostra come cercare testo nella prima pagina e cambiare il font della prima occorrenza trovata. // Apri documento Document doc = new Document("input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Crea il font e contrassegnalo per l'incorporamento Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Salva il documento doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Rappresenta un oggetto assorbitore di font. Esegue la ricerca dei font e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code FontAbsorber.Fonts}. |
| [FontCollection](./fontcollection/) | <p> Rappresenta la collezione di font. </p> <hr> <pre> L'esempio dimostra come rendere tutti i font dichiarati nella pagina incorporati. // Apri documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // assicurati che tutti i font dichiarati nelle risorse della pagina siano incorporati // nota che se i font sono dichiarati nelle risorse del modulo non sono accessibili dalle risorse della pagina for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\\\Tests\\\\input.pdf"); </pre> <hr> <p> Le collezioni di font rappresentate dalla classe {@code FontCollection} sono utilizzate in diversi scenari. Per esempio, nelle risorse con la proprietà {@code Resources.Fonts}. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | Lo standard PDF/A richiede che tutti i font siano incorporati nel documento. Questa classe include flag per i casi in cui non è possibile incorporare alcuni font perché tali font sono assenti sul PC di destinazione. |
| [FontRepository](./fontrepository/) | <p> Esegue la ricerca dei font. Cerca nei font installati sul sistema e nei font PDF standard. Fornisce anche la funzionalità per aprire font personalizzati. </p> <hr> <pre> L'esempio dimostra come trovare un font e sostituire il font del testo della prima pagina. // Trova il font Font font = FontRepository.findFont("Arial"); // Apri documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Salva il documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Rappresenta una classe base per la sorgente del font. |
| [FontStyles](./fontstyles/) | Binary Flag <p> Specifica le informazioni di stile applicate al testo. </p> <hr> <p> Questa enumerazione ha un attributo {@code FlagsAttribute} che consente una combinazione dei valori dei suoi membri. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag enumera le strategie per il sottoinsieme dei font |
| [FooterArtifact](./footerartifact/) | Descrive l'artefatto footer. Può essere usato per impostare il footer della pagina. |
| [Form](./form/) | Classe che rappresenta l'oggetto modulo. |
| [Form.FlattenSettings](./form.flattensettings/) | Classe che descrive le impostazioni per la procedura di appiattimento del modulo. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | I moduli possono contenere informazioni di firma e possono essere firmati o non firmati. A volte la visualizzazione dei moduli nel visualizzatore deve dipendere dal fatto che il modulo sia firmato o meno. Questo enum enumera i possibili modi di rendering durante la conversione del tipo di modulo in relazione alla firma. |
| [FormattedFragment](./formattedfragment/) | Rappresenta un frammento formattato astratto. |
| [FreeTextAnnotation](./freetextannotation/) | Rappresenta un'annotazione di testo libero che visualizza il testo direttamente sulla pagina. A differenza di un'annotazione di testo ordinaria, un'annotazione di testo libero non ha uno stato aperto o chiuso; invece di essere visualizzata in una finestra pop-up, il testo è sempre visibile. |
| [GoToAction](./gotoaction/) | Rappresenta un'azione vai-a che cambia la visualizzazione verso una destinazione specificata (pagina, posizione e fattore di ingrandimento). |
| [GoToRemoteAction](./gotoremoteaction/) | Rappresenta un'azione vai-a remota simile a un'azione vai-a ordinaria ma salta a una destinazione in un altro file PDF invece del file corrente. |
| [GoToURIAction](./gotouriaction/) | Rappresenta un'azione URI che provoca la risoluzione di un URI. |
| [GraphInfo](./graphinfo/) | Rappresenta le informazioni grafiche. |
| [Group](./group/) | Una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina per l'uso nel modello di imaging trasparente. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | La classe descrive l'artefatto Heaader. Questo artefatto può essere usato per impostare l'intestazione della pagina. |
| [HeaderFooter](./headerfooter/) | La classe rappresenta la pagina PDF di intestazione o piè di pagina. |
| [Heading](./heading/) | Rappresenta l'intestazione. |
| [HideAction](./hideaction/) | Rappresenta un'azione di nascondimento che nasconde o mostra una o più annotazioni sullo schermo impostando o cancellando i loro flag Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Rappresenta un'annotazione di evidenziazione che mette in evidenza un intervallo di testo nel documento. |
| [HtmlFragment](./htmlfragment/) | Rappresenta un frammento html. |
| [HtmlLoadOptions](./htmlloadoptions/) | Rappresenta le opzioni per il caricamento/importazione di un file html in un documento pdf. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Binary Flag Specifica i flag che, insieme ad altre opzioni, determinano le dimensioni e i layout delle pagine. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato Html |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | Questo enum descrive le possibili misure di antialiasing durante la conversione |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato di CSS durante la conversione da PDF a formato HTML |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | È possibile assegnare a questa proprietà una strategia personalizzata che implementa l'elaborazione e/o il salvataggio di una parte di CSS creata durante la conversione da PDF a HTML. In tal caso l'elaborazione (come il salvataggio su stream o disco) deve essere eseguita nel codice personalizzato. |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa la creazione dell'URL del CSS referenziato nel documento HTML generato. Per esempio, se vuoi che il CSS sia referenziato in HTML, ad es. "otherPage.ASPX?CssID=zjjkklj", allora tale strategia personalizzata deve restituire "otherPage.ASPX?CssID=zjjkklj" |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | Rappresenta un insieme di dati relativi alla richiesta dal convertitore al codice personalizzato finalizzata a ottenere l'URL desiderato (o il modello di URL) del CSS in questione |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | Questa enumerazione definisce le regole che regolano la logica di codifica |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Enumera le modalità che possono essere usate per il salvataggio dei font referenziati nel PDF salvato. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | Questa classe rappresenta un insieme di dati relativi al salvataggio di file immagine di risorse esterne durante la conversione da PDF a HTML. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | Enumera i possibili tipi di file immagine che possono essere salvati come risorse esterne durante la conversione da Pdf a Html. |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | A volte sono presenti requisiti specifici per l'HTML creato. Questo enum definisce le modalità di preparazione dell'HTML che possono essere usate durante la conversione da PDF a HTML per soddisfare tali requisiti specifici. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | Se la proprietà SplitToPages di HtmlSaveOptions è impostata, allora vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione da PDF a HTML. Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato del markup di una pagina HTML durante la conversione da PDF a HTML. |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | Il risultato della conversione può contenere una o più pagine HTML (che possono anche referenziare file esterni come immagini o font). È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione della pagina HTML ottenuta (HTML stesso) creata durante la conversione. In tal caso l'elaborazione (come il salvataggio su stream o disco) può essere eseguita nel codice personalizzato. In tal caso tutte le azioni necessarie per il salvataggio del markup della pagina HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non verrà utilizzato. Se per qualche motivo l'elaborazione in questo o quel caso deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile parametro 'htmlSavingInfo': segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso, come se non esistesse alcun codice di salvataggio personalizzato esterno. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Enumera i possibili tipi di genitori dell'immagine; l'immagine può appartenere a una pagina HTML o a un'immagine genitore SVG. |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | Questo enum enumera le possibili modalità di incorporamento dei file referenziati in HTML. Consente di controllare se i file referenziati (HTML, font, immagini, CSS) saranno incorporati nel file HTML principale o generati come entità binarie separate. |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | Il PDF convertito può contenere immagini raster (.png, *.jpeg ecc.). Questo enum definisce i metodi di gestione delle immagini raster durante la conversione da PDF a HTML |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | Per questa proprietà è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione di una risorsa esterna (Font o Immagine) estratta dal PDF e che deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso l'elaborazione (come il salvataggio in stream o su disco) può essere eseguita in quel codice personalizzato e quel codice personalizzato deve restituire il percorso (o qualsiasi altra stringa senza virgolette) che verrà successivamente incorporato nell'HTML generato al posto del percorso originale previsto per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se per qualche motivo l'elaborazione di questo o di quell'altro file deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'resourceSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso come se non esistesse alcun codice personalizzato esterno. |
| [Hyperlink](./hyperlink/) | Rappresenta un collegamento ipertestuale astratto. |
| [IconFit](./iconfit/) | Descrive come l'icona dell'annotazione widget deve essere visualizzata all'interno del suo rettangolo di annotazione. |
| [Id](./id/) | <p> Rappresenta la struttura dell'identificatore del file. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Rappresenta un'immagine. |
| [ImageDeleteAction](./imagedeleteaction/) | Azione eseguita con l'oggetto immagine quando l'immagine viene rimossa dalla collezione. Se l'oggetto immagine viene rimosso |
| [ImagePlacement](./imageplacement/) | <p> Rappresenta le caratteristiche di un'immagine posizionata su una pagina di documento PDF. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Quando un'immagine è posizionata su una pagina, può avere dimensioni diverse da quelle fisiche definite in {@code Resources}. L'oggetto {@code ImagePlacement} è destinato a fornire tali informazioni, come dimensioni, risoluzione e così via. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Rappresenta un oggetto assorbitore di oggetti di posizionamento immagine. Esegue la ricerca degli utilizzi delle immagini e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> L'esempio dimostra come trovare le immagini nella prima pagina del documento PDF e ottenere le proprietà di posizionamento dell'immagine. // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println(\"image width:\" + imagePlacement.getRectangle().getWidth()); System.out.println(\"image height:\" + imagePlacement.getRectangle().getHeight()); System.out.println(\"image LLX:\" + imagePlacement.getRectangle(0).getX()); System.out.println(\"image LLY:\" + imagePlacement.getRectangle.getY()); System.out.println(\"image horizontal resolution:\" + imagePlacement.getResolution().getX()); System.out.println(\"image vertical resolution:\" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> L'oggetto {@code ImagePlacementAbsorber} è fondamentalmente utilizzato nello scenario di ricerca delle immagini. Quando la ricerca è completata, le occorrenze sono rappresentate con oggetti {@code ImagePlacement} contenuti nella collezione {@code ImagePlacementAbsorber.ImagePlacements}. L'oggetto {@code ImagePlacement} fornisce l'accesso alle proprietà di posizionamento dell'immagine: dimensioni, risoluzione ecc. </p> La rotazione positiva dell'immagine è in senso antiorario, per la pagina è in senso orario. Qui, è necessario rappresentare l'angolo di rotazione dell'immagine, quindi sottraiamo l'angolo della pagina dall'angolo dell'immagine. |
| [ImagePlacementCollection](./imageplacementcollection/) | Rappresenta una collezione di posizionamenti di immagini. |
| [ImageStamp](./imagestamp/) | Rappresenta un timbro grafico. |
| [ImageType](./imagetype/) | Rappresenta i tipi di formato immagine. |
| [ImportDataAction](./importdataaction/) | All'atto dell'invocazione di un'azione di importazione dati, i dati Forms Data Format (FDF) devono essere importati nel modulo interattivo del documento da un file specificato. |
| [ImportFieldsOptions](./importfieldsoptions/) | Rappresenta la classe base delle opzioni per l'importazione dei campi del modulo. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Rappresenta le opzioni per l'importazione dei campi del modulo in formato Json. Eredita da {@code ImportFieldsOptions} e aggiunge opzioni specifiche per l'importazione Json. |
| [ImportOptions](./importoptions/) | Il tipo ImportOptions mantiene un livello di astrazione sulle singole opzioni di importazione. |
| [InkAnnotation](./inkannotation/) | Rappresenta uno \"scarabocchio\" a mano libera composto da uno o più percorsi disgiunti. |
| [InternalHelper](./internalhelper/) | Classe interna |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | L'eccezione che viene lanciata quando un'operazione con il tipo di modulo non è valida. |
| [JavascriptAction](./javascriptaction/) | Classe che rappresenta un'azione JavaScript. |
| [JavaScriptCollection](./javascriptcollection/) | Questa classe rappresenta una collezione di JavaScript. |
| [LatexFragment](./latexfragment/) | Rappresenta un frammento TeX. @deprecated Si prega di utilizzare TeXFragment invece. |
| [LatexLoadOptions](./latexloadoptions/) | Rappresenta le opzioni per caricare/importare un file TeX in un documento PDF. @deprecated Utilizzare TeXLoadOptions invece. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato TeX. @deprecated Utilizzare TeXSaveOptions invece. |
| [LaunchAction](./launchaction/) | Rappresenta un'azione di avvio che avvia un'applicazione o apre o stampa un documento. |
| [Layer](./layer/) | Rappresenta un livello all'interno di una pagina PDF. |
| [LevelFormat](./levelformat/) | Rappresenta il formato del sommario. |
| [License](./license/) | Fornisce metodi per licenziare il componente. In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante. License license = new License(); license.setLicense(\"MyLicense.lic\"); |
| [LicenseInfo](./licenseinfo/) | Rappresenta le informazioni di licenza. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Collezione di operatori leggera. Destinata a essere usata in scenari in cui lo stream dei contenuti sottostante non è allegato, dove è richiesta solo la collezione di operatori come risultato. |
| [LineAnnotation](./lineannotation/) | Classe che rappresenta un'annotazione di linea. |
| [LineEndingConverter](./lineendingconverter/) | Rappresenta la classe LineEndingConverter |
| [LineEndingsDrawer](./lineendingsdrawer/) | Disegna le terminazioni di linea per le annotazioni. Classe interna solo per uso interno. |
| [LinkAnnotation](./linkannotation/) | Rappresenta un collegamento ipertestuale a una destinazione altrove nel documento o un'azione da eseguire. |
| [ListBoxField](./listboxfield/) | La classe rappresenta il campo ListBox. |
| [LoadOptions](./loadoptions/) | Il tipo LoadOptions contiene il livello di astrazione sulle singole opzioni di caricamento. |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Rappresenta la modalità di utilizzo dell'area dei margini durante la conversione (come HTML, EPUB ecc.), definisce il trattamento delle istruzioni del formato importato relative all'uso dei margini. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | ATTENZIONE! La funzionalità è implementata ma non è ancora stata resa disponibile nell'API pubblica poiché è stato riscontrato un problema bloccante nello strato OSHARED per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB ecc.) solitamente hanno un layout fluido, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia a volte il contenuto specifica posizioni orizzontali o una dimensione che non permette di inserire il contenuto nella dimensione di pagina richiesta. In tal caso possiamo definire cosa fare in questa situazione (ad esempio quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina del documento PDF risultante). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Risultato del caricamento personalizzato della risorsa |
| [LocaleOptions](./localeoptions/) | Il tipo LocaleOptions specifica la configurazione locale per Aspose.PDF. |
| [LocalHyperlink](./localhyperlink/) | Rappresenta un oggetto hyperlink locale. |
| [MarginInfo](./margininfo/) | Questa classe rappresenta un margine per diversi oggetti. |
| [MarkupAnnotation](./markupannotation/) | Classe astratta che rappresenta un'annotazione di markup. |
| [MarkupParagraph](./markupparagraph/) | Rappresenta un paragrafo. |
| [MarkupSection](./markupsection/) | Rappresenta una sezione di markup - la regione rettangolare di una pagina che contiene testo e può essere visualmente separata da altri blocchi di testo. |
| [Matrix](./matrix/) | La classe rappresenta la matrice di trasformazione. |
| [Matrix3D](./matrix3d/) | La classe rappresenta la matrice di trasformazione. |
| [MdLoadOptions](./mdloadoptions/) | Opzioni di caricamento per la conversione del formato Markdown. |
| [Measure](./measure/) | Classe che descrive il sistema di coordinate Measure. |
| [Measure.NumberFormat](./measure.numberformat/) | Formato numerico per la misura. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Rappresenta un elenco di formati numerici. |
| [MediaClip](./mediaclip/) | Classe che descrive l'oggetto media clip della resa. |
| [MediaClipData](./mediaclipdata/) | Classe che descrive i dati del media clip. |
| [MediaClipSection](./mediaclipsection/) | Questa classe descrive la sezione Media clip. |
| [MediaRendition](./mediarendition/) | Classe che descrive la resa multimediale. |
| [MemoryCleaner](./memorycleaner/) | Rappresenta la classe MemoryCleaner |
| [MemoryExtender](./memoryextender/) | Rappresenta la classe MemoryExtender. Utilizzando file di grandi dimensioni su un sistema con memoria heap limitata, può essere abilitata a usare lo spazio su disco come memoria di swap temporanea. |
| [MemoryFontSource](./memoryfontsource/) | Rappresenta una singola origine di file di carattere. |
| [Metadata](./metadata/) | Fornisce l'accesso al flusso di metadati XMP. |
| [Metered](./metered/) | <p> Fornisce metodi per impostare la chiave metered. </p> <hr> In questo esempio, verrà tentato di impostare la chiave pubblica e privata metered <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | Rappresenta le opzioni per il caricamento/importazione di file .mht in un documento pdf. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato Xml |
| [MovieAnnotation](./movieannotation/) | Rappresenta un'annotazione video che contiene grafiche animate e suono da presentare sullo schermo del computer e attraverso gli altoparlanti. Quando l'annotazione è attivata, il video viene riprodotto. |
| [NamedAction](./namedaction/) | Rappresenta azioni nominate che le applicazioni visualizzatrici di PDF dovrebbero supportare. |
| [NamedDestination](./nameddestination/) | Invece di essere definita direttamente con la sintassi esplicita, una destinazione può essere riferita indirettamente tramite un oggetto nome o una stringa di byte. |
| [Note](./note/) | Questa classe rappresenta la nota di paragrafo del generatore. |
| [NumberField](./numberfield/) | Campo di testo con caratteri validi specificati @see TextBoxField |
| [NumberTree](./numbertree/) | Classe che rappresenta la struttura ad albero dei numeri di un file PDF. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | Rappresenta le impostazioni OCSP utilizzate durante il processo di firma. |
| [OfdLoadOptions](./ofdloadoptions/) | Opzioni di caricamento per il formato OFD. |
| [Operator](./operator/) | Classe astratta che rappresenta l'operatore. |
| [OperatorCollection](./operatorcollection/) | La classe rappresenta una collezione di operatori |
| [OperatorSelector](./operatorselector/) | Questa classe è usata per selezionare gli operatori utilizzando l'idea del modello Visitor. |
| [Opi](./opi/) | Rappresenta l'Open Prepress Interface (OPI), un meccanismo per creare segnaposti a bassa risoluzione, o proxy, per immagini ad alta risoluzione. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Definisce un MemoryStream che può contenere una capacità più standard |
| [Option](./option/) | La classe rappresenta l'opzione del campo di scelta. |
| [OptionCollection](./optioncollection/) | Classe che rappresenta la collezione di opzioni del campo di scelta. |
| [OutlineCollection](./outlinecollection/) | Rappresenta la gerarchia del sommario del documento. |
| [OutlineItemCollection](./outlineitemcollection/) | Rappresenta una voce del sommario nella gerarchia del sommario di un documento PDF. |
| [Outlines](./outlines/) | La classe descrive una collezione di sommari. |
| [OutputIntent](./outputintent/) | Rappresenta un'intenzione di output che corrisponde alle caratteristiche cromatiche di un documento PDF con quelle di un dispositivo di output target o di un ambiente di produzione in cui il documento sarà stampato. |
| [OutputIntents](./outputintents/) | Rappresenta la collezione di {@link OutputIntent}. |
| [Page](./page/) | Classe che rappresenta una pagina di un documento PDF. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Procedura per personalizzare intestazione e piè di pagina. |
| [PageActionCollection](./pageactioncollection/) | Questa classe descrive le azioni di pagina |
| [PageCollection](./pagecollection/) | Collezione di pagine di documenti PDF. |
| [PageExtensions](./pageextensions/) | Fornisce funzionalità aggiuntive per la classe Page. |
| [PageInfo](./pageinfo/) | Rappresenta le informazioni della pagina per il generatore pdf. |
| [PageInformationAnnotation](./pageinformationannotation/) | Rappresenta un'annotazione Page Information in un documento PDF. Questa annotazione contiene il nome del file, il numero di pagina e la data e l'ora di creazione dell'annotazione. Questa classe è principalmente utilizzata per aggiungere metadati a una pagina specifica del documento PDF, il che può essere utile per scopi di tracciamento e riferimento. Per esempio, può essere usata per contrassegnare le pagine durante il processo di stampa o per fornire informazioni aggiuntive sulla pagina durante la visualizzazione del documento. |
| [PageLabel](./pagelabel/) | Classe che rappresenta l'intervallo di Page Label. |
| [PageLabelCollection](./pagelabelcollection/) | Classe che rappresenta la raccolta di page label. |
| [PageMarkup](./pagemarkup/) | Markup della pagina rappresentato da collezioni di {@code MarkupSection} e {@code MarkupParagraph}. |
| [PageNumberStamp](./pagenumberstamp/) | Rappresenta il timbro del numero di pagina ed è usato per numerare le pagine. |
| [PageSize](./pagesize/) | Classe che rappresenta le dimensioni della pagina in un documento PDF. |
| [PaginationArtifact](./paginationartifact/) | Rappresenta una classe base astratta per gli artefatti di impaginazione in un documento. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Rappresenta un oggetto assorbitore della struttura della pagina, come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce l'accesso a rettangoli e poligoni che la descrivono nello spazio delle coordinate del testo. Esegue inoltre la ricerca di segmenti di testo e fornisce l'accesso ai risultati della ricerca tramite collezioni {@code TextFragments} raggruppate per elementi di struttura. </p> L'esempio dimostra come trovare il primo segmento di testo di ogni paragrafo nella prima pagina del documento PDF e evidenziarlo. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Quando la ricerca è completata, la collezione {@code ParagraphAbsorber.PageMarkups} conterrà oggetti {@code PageMarkup} che rappresentano la struttura della pagina mediante collezioni di {@code MarkupSection} e {@code MarkupParagraph}. L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore, ecc.). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Rappresenta le opzioni per il {@link ParagraphAbsorber}. |
| [Paragraphs](./paragraphs/) | Questa classe rappresenta la raccolta di paragrafi. |
| [PasswordBoxField](./passwordboxfield/) | Classe che descrive il campo di testo per l'inserimento della password. |
| [PclLoadOptions](./pclloadoptions/) | Rappresenta le opzioni per il caricamento (import) di file PCL in un documento pdf. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Enumera i motori di conversione che possono essere usati per la conversione |
| [PDF3DAnnotation](./pdf3dannotation/) | Classe PDF3DAnnotation. Questa classe non può essere ereditata. @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | Classe PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Classe PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Classe PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Classe PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Classe PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Classe PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Classe PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Classe PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Classe PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Classe PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Rappresenta l'azione nel documento PDF |
| [PdfActionCollection](./pdfactioncollection/) | La classe descrive l'elenco delle azioni. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | Questa classe descrive le regole che possono essere utilizzate per affinare il processo di copia dei dati di codifica nei casi in cui il font simbolico TrueType abbia più di una codifica. Alcuni documenti PDF, dopo la conversione in formato PDF/A, potrebbero generare un errore "More than one encoding in symbolic TrueType font's cmap". Qual è la ragione di questo errore? Tutti i font simbolici TrueType hanno una tabella speciale "cmap" nei loro dati interni. Questa tabella mappa i codici dei caratteri agli indici dei glifi. E questa tabella può contenere diverse sotto‑tabelle di codifica che descrivono le codifiche utilizzate. Vedi informazioni avanzate sulle tabelle cmap su https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Di solito la tabella cmap contiene diverse sotto‑tabelle di codifica, ma lo standard PDF/A richiede che o venga lasciata una sola sotto‑tabella di codifica per questo font nel documento PDF/A, oppure che tra le sotto‑tabelle del font sia presente una sotto‑tabella di codifica (3,0). E la domanda chiave qui è: quali dati devono essere presi da altre sotto‑tabelle per essere copiati nella tabella di codifica di destinazione (3,0)? La maggior parte dei font ha tabelle cmap "well‑formed" in cui ogni sotto‑tabella di codifica è pienamente coerente con un'altra sotto‑tabella. Ma alcuni font hanno tabelle cmap con collisioni — dove, ad esempio, una sotto‑tabella ha l'indice di glifo 100 per Unicode 100, ma un'altra sotto‑tabella ha l'indice di glifo 200 per lo stesso Unicode 100. Per risolvere questi problemi è necessaria una strategia speciale. Per impostazione predefinita viene utilizzata la seguente strategia: si cerca la sotto‑tabella mac (1,0). Se questa tabella viene trovata, solo questi dati vengono usati per riempire la tabella di destinazione (3,0). Se la sotto‑tabella mac non viene trovata, allora tutte le sotto‑tabelle eccetto (3,0) vengono iterate e usate per copiare i dati nella sotto‑tabella di destinazione (3,0). Inoltre la mappatura per ogni unicode (unicode, indice del glifo) viene copiata nella tabella di destinazione solo se la tabella di destinazione non contiene ancora quel unicode al momento. Quindi, per esempio, se la prima sotto‑tabella ha l'indice di glifo 100 per Unicode 100, e la successiva sotto‑tabella ha l'indice di glifo 200 per lo stesso Unicode 100, verranno copiati solo i dati dalla prima sotto‑tabella (unicode=100, indice del glifo = 100). Quindi ogni sotto‑tabella precedente ha precedenza su quella successiva. Le proprietà di questa classe { PdfASymbolicFontEncodingStrategy} aiutano a regolare il comportamento predefinito. Se la proprietà {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) di tipo { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} è impostata, allora la sotto‑tabella pertinente verrà usata con precedenza rispetto alla sotto‑tabella mac (1,0). Il valore 'MacTable' dell'enumerazione {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} non ha senso in questo caso, poiché punta alla stessa sotto‑tabella mac (1,0) che verrà usata per impostazione predefinita. La proprietà {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) scarta tutte le priorità per qualsiasi sotto‑tabella. Se questa proprietà è impostata, allora solo le sotto‑tabelle della coda dichiarata verranno usate nell'ordine specificato. Se le sotto‑tabelle specificate non vengono trovate, verrà usata l'iterazione predefinita di tutte le sotto‑tabelle e la strategia di copia descritta sopra. L'oggetto { PdfASymbolicFontEncodingStrategy.QueueItem} specifica la sotto‑tabella di codifica utilizzata. Questa sotto‑tabella può essere impostata tramite una combinazione di membri (PlatformID, PlatformSpecificId) o tramite l'enumerazione { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. Nel caso in cui il font non abbia una sotto‑tabella (3,0), verrà usata un'altra sotto‑tabella per mantenere la compatibilità PDF/A. La scelta della sotto‑tabella da utilizzare viene effettuata secondo le stesse regole descritte in precedenza, in modo che le proprietà {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) e {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) vengano usate per determinare la sotto‑tabella risultante, e se il font non dispone della/e sotto‑tabella/e richiesta/e, verrà utilizzata qualsiasi sotto‑tabella esistente. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Specifica la sottotabella di codifica. Ogni sottotabella di codifica ha una combinazione unica di parametri (PlatformID, PlatformSpecificID). L'enumerazione {@code CMapEncodingTableType} e la proprietà {@code CMapEncodingTable} sono state implementate per semplificare la definizione della sottotabella di codifica necessaria. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Dichiara un insieme di alcune sottotabelle di codifica note |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | rappresenta un insieme di opzioni per convertire un documento PDF |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | Questa classe contiene flag per controllare la conversione PDF/A nei casi in cui il documento PDF di origine non corrisponda alla specifica PDF. Se i flag di questa classe vengono usati, le prestazioni diminuiscono, ma è necessario quando il documento PDF di origine non può essere convertito nel formato PDF/A in modo consueto. Per impostazione predefinita tutti i flag sono impostati su false. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Alcuni documenti PDF contengono simboli Unicode speciali, appartenenti all'Area di Uso Privato (PUA); vedere la descrizione su https://en.wikipedia.org/wiki/Private_Use_Areas. Questi simboli causano errori di conformità PDF/A come "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Questa enumerazione dichiara le strategie che possono essere usate per gestire i simboli PUA. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Alcuni documenti hanno una dimensione elevata dopo la conversione in formato PDF/A. Per ridurre la dimensione del file per questi documenti è necessario definire una strategia di rimozione dei caratteri. Questa enumerazione dichiara le strategie che possono essere usate per ottimizzare l'uso dei caratteri. Ogni strategia di questa enumerazione ha senso solo quando il flag {@code OptimizeFileSize} è impostato. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Descrive le strategie usate per allineare i segmenti di testo del documento. Attualmente è supportata solo la strategia per ripristinare i segmenti ai limiti originali. In futuro potranno essere aggiunte altre strategie. |
| [PdfPageStamp](./pdfpagestamp/) | La classe rappresenta un timbro che utilizza una pagina PDF come timbro. |
| [PdfSaveOptions](./pdfsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato Pdf |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Opzioni di caricamento per il formato PdfXml. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Opzioni di salvataggio per il formato PdfXml. |
| [Permissions](./permissions/) | Flag binario Questa enumerazione rappresenta i permessi dell'utente per un pdf. |
| [PKCS1](./pkcs1/) | Rappresenta un oggetto firma secondo lo standard PKCS#1. L'algoritmo di crittografia RSA e il metodo di digest SHA-1 sono usati per la firma. |
| [PKCS7](./pkcs7/) | Rappresenta l'oggetto PKCS#7 conforme alla specifica PKCS#7 nella RFC 2315 di Internet, PKCS #7: Cryptographic Message Syntax, Versione 1.5. Il digest SHA1 dell'intervallo di byte del documento è incapsulato nel campo SignedData di PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Rappresenta l'oggetto PKCS#7 conforme alla specifica PKCS#7 nella RFC 2315 di Internet, PKCS #7: Cryptographic Message Syntax, Versione 1.5. Il digest originale del messaggio firmato sull'intervallo di byte del documento è incorporato come campo SignedData normale di PKCS#7. Nessun dato è incapsulato nel campo SignedData di PKCS#7. |
| [Point](./point/) | Rappresenta un punto con coordinate frazionarie. |
| [Point3D](./point3d/) | Rappresenta un punto con coordinate frazionarie. |
| [PolyAnnotation](./polyannotation/) | Classe base astratta per le poliannotazioni. |
| [PolygonAnnotation](./polygonannotation/) | Classe che rappresenta un'annotazione poligonale. |
| [PolylineAnnotation](./polylineannotation/) | Rappresenta un'annotazione polilinea simile al poligono, tranne per il fatto che il primo e l'ultimo vertice non sono collegati implicitamente. |
| [PopupAnnotation](./popupannotation/) | Rappresenta l'annotazione pop-up che visualizza il testo in una finestra pop-up per l'inserimento e la modifica. |
| [Position](./position/) | Rappresenta un oggetto posizione |
| [PptxSaveOptions](./pptxsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato SVG |
| [PrintController](./printcontroller/) | Rappresenta il controller di stampa. |
| [PrintDuplex](./printduplex/) | L'opzione di gestione della carta da utilizzare quando si stampa il file dalla finestra di dialogo di stampa. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Classe astratta che rappresenta l'annotazione di segno di stampa. |
| [PrinterMarksKind](./printermarkskind/) | Specifica i tipi di segni della stampante da aggiungere a un documento. Questa enumerazione ha un attributo {@link FlagsAttribute} che consente una combinazione bitwise dei valori dei suoi membri. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Fornisce metodi di estensione per l'enumerazione {@link PrinterMarksKind}. |
| [PrintScaling](./printscaling/) | L'opzione di ridimensionamento della pagina che deve essere selezionata quando viene visualizzata una finestra di stampa per questo documento. |
| [ProgressEventType](./progresseventtype/) | Questa enum descrive i possibili tipi di eventi di avanzamento che possono verificarsi durante la conversione |
| [PsLoadOptions](./psloadoptions/) | Rappresenta le opzioni per il caricamento/importazione di file .mht in un documento pdf. |
| [PsSaveOptions](./pssaveoptions/) | Opzioni di salvataggio per l'esportazione in formato PS (PostScript) o EPS. |
| [RadioButtonField](./radiobuttonfield/) | Classe che rappresenta il campo pulsante radio. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Classe che rappresenta l'elemento del campo RadioButton. |
| [Rectangle](./rectangle/) | Classe che rappresenta un rettangolo. |
| [Redaction](./redaction/) | Solo per uso interno @author User |
| [RedactionAnnotation](./redactionannotation/) | Rappresenta l'annotazione Redact. |
| [RegexManager](./regexmanager/) | Fornisce un wrapper per le operazioni di espressioni regolari con impostazioni di timeout configurabili. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Rappresenta un'annotazione Registration Mark. I segni di registrazione sono simboli aggiunti alle lastre di stampa o agli schermi per garantire il corretto allineamento dei colori durante il processo di stampa. |
| [RenderingOptions](./renderingoptions/) | Rappresenta le opzioni di rendering |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: insieme di tipi di modalità di rendering |
| [Rendition](./rendition/) | Classe che descrive l'oggetto di resa di RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Un'azione di resa che controlla la riproduzione di contenuti multimediali. |
| [RenditionOperation](./renditionoperation/) | L'operazione da eseguire quando l'azione viene attivata. |
| [RenditionType](./renditiontype/) | L'enumerazione descrive i possibili tipi di Rendition. |
| [Resources](./resources/) | Classe che rappresenta le risorse della pagina. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Rappresenta ExtGStates con alcuni valori. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Rappresenta la strategia di conversione dallo spazio colore rgb a quello grigio del dispositivo. |
| [RichMediaAnnotation](./richmediaannotation/) | Classe che descrive RichMediaAnnotation che consente di incorporare dati video/audio in un documento PDF. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Evento che attiva l'annotazione. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Tipo del multimediale. |
| [RichTextBoxField](./richtextboxfield/) | Classe che descrive il componente editor di testo ricco. |
| [RichTextFontStyles](./richtextfontstyles/) | Opzioni per lo stile dei frammenti di testo in RichText. |
| [RootElement](./rootelement/) | Elemento di struttura radice. |
| [Row](./row/) | Rappresenta una riga della tabella. |
| [Rows](./rows/) | Rappresenta una collezione di righe della tabella. |
| [RtfLoadOptions](./rtfloadoptions/) | Opzioni di caricamento per il formato RTF. |
| [SaveOptions](./saveoptions/) | Il tipo SaveOptions mantiene il livello di astrazione sulle singole opzioni di salvataggio. |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Un'istanza di questa classe rappresenta informazioni sul bordo che può essere disegnata su un documento risultante. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Rappresenta le informazioni di una parte del bordo (superiore, inferiore, lato sinistro o lato destro). |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Un'istanza di questa classe rappresenta informazioni sul margine della pagina che può essere disegnata su un documento risultante. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Rappresenta le informazioni di una parte del margine (superiore, inferiore, lato sinistro o lato destro). |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | Questa classe rappresenta un insieme di dati relativi al salvataggio di file di risorse esterne che si verifica durante la conversione di PDF in altri formati (ad es. HTML). |
| [ScalingMode](./scalingmode/) | Il tipo di scala da utilizzare. |
| [ScalingReason](./scalingreason/) | Le circostanze in cui l'icona deve essere scalata all'interno del rettangolo dell'annotazione. |
| [ScreenAnnotation](./screenannotation/) | Un'annotazione schermo che specifica una regione di una pagina su cui possono essere riprodotti clip multimediali. |
| [SelectorRendition](./selectorrendition/) | La classe descrive la resa del selettore. |
| [Signature](./signature/) | Una classe astratta che rappresenta l'oggetto firma nel documento PDF. Le firme sono campi con valori di oggetti firma, quest'ultimi contengono dati utilizzati per verificare la validità del documento. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Una classe astratta che rappresenta l'oggetto di aspetto personalizzato della firma. |
| [SignatureField](./signaturefield/) | Rappresenta il campo modulo della firma. |
| [SignHash](./signhash/) | Delegato per la firma personalizzata dell'hash del documento (Beta). |
| [SoundAnnotation](./soundannotation/) | Rappresenta un'annotazione audio che contiene suono registrato dal microfono del computer o importato da un file. |
| [SoundData](./sounddata/) | Rappresenta i dati audio che definiscono il suono da riprodurre quando l'annotazione è attivata. |
| [SoundEncoding](./soundencoding/) | Il formato di codifica per i dati di esempio. |
| [SoundIcon](./soundicon/) | Enumera le icone da utilizzare nella visualizzazione dell'annotazione. |
| [SoundIconConverter](./soundiconconverter/) | Rappresenta la classe SoundIconConverter |
| [SoundSampleData](./soundsampledata/) | Rappresenta voci aggiuntive specifiche per un oggetto audio (Sezione 9.2 PDF1-7) |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Il formato di codifica per i dati del campione audio. |
| [SquareAnnotation](./squareannotation/) | Classe che rappresenta l'annotazione quadrata. |
| [SquigglyAnnotation](./squigglyannotation/) | Rappresenta l'annotazione ondulata che appare come una sottolineatura irregolare nel testo di un documento. |
| [Stamp](./stamp/) | Una classe astratta per vari tipi di timbri che vengono come discendenti. |
| [StampAnnotation](./stampannotation/) | <p> Rappresenta l'annotazione di timbro di gomma. Questo tipo di annotazione visualizza testo o grafica destinati a sembrare come se fossero stati timbrati sulla pagina con un timbro di gomma. </p> <hr> <pre> Il prossimo frammento di codice dimostra come aggiungere 2 timbri nella prima pagina del documento PDF. Il documento di input proviene da inFile e le modifiche vengono salvate in outFile. Il primo timbro ha l'icona NotForPublicRelease e il secondo proviene dall'immagine rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | Rappresenta la classe StampIconConverter |
| [StrikeOutAnnotation](./strikeoutannotation/) | Rappresenta un'annotazione barrata che appare come barratura nel testo del documento. |
| [StructElement](./structelement/) | Elemento di struttura generale. |
| [SubjectNameElements](./subjectnameelements/) | L'enumerazione descrive gli elementi nella stringa dell'oggetto della firma. |
| [SubmitFormAction](./submitformaction/) | Classe che descrive l'azione submit-form. |
| [SvgLoadOptions](./svgloadoptions/) | Rappresenta le opzioni per caricare/importare un file SVG in un documento PDF. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Enumera i motori di conversione che possono essere usati per la conversione |
| [SvgSaveOptions](./svgsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato SVG |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | Questa classe rappresenta un insieme di dati relativi al salvataggio di file immagine di risorse esterne durante la conversione da PDF a HTML. |
| [Symbology](./symbology/) | Una simbologia (Barcode) definisce i dettagli tecnici di un particolare tipo di codice a barre: la larghezza delle barre, il set di caratteri, il metodo di codifica, le specifiche del checksum, ecc. |
| [SystemFontSource](./systemfontsource/) | Rappresenta tutti i font installati nel sistema. |
| [TabAlignmentType](./tabalignmenttype/) | Enumera i tipi di allineamento delle tabulazioni. |
| [Table](./table/) | Rappresenta una tabella che può essere aggiunta alla pagina. |
| [TableAbsorber](./tableabsorber/) | <p> Rappresenta un oggetto assorbitore di elementi tabella. Esegue la ricerca e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TableAbsorber.TableList}. </p> <hr> <pre> L'esempio dimostra come trovare una tabella nella prima pagina del documento PDF e sostituire il testo in una cella della tabella. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | Enumera i tipi di leader di tabulazione. |
| [TableBroken](./tablebroken/) | Enumera la tabella interrotta. |
| [TabOrder](./taborder/) | Ordine di tabulazione nella pagina |
| [TabStop](./tabstop/) | Rappresenta una posizione di tabulazione personalizzata in un paragrafo. |
| [TabStops](./tabstops/) | Rappresenta una collezione di oggetti {@code TabStop}. |
| [TeXFragment](./texfragment/) | Rappresenta un frammento LaTeX. |
| [TeXLoadOptions](./texloadoptions/) | Rappresenta le opzioni per caricare/importare un file TeX in un documento PDF. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Implementa il recupero di uno stream di output dalla memoria. Puoi usarlo, ad esempio, quando non vuoi che l'output associato (come un file di log) venga scritto su disco ma desideri leggerlo successivamente dalla memoria. |
| [TeXSaveOptions](./texsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato TeX |
| [TextAbsorber](./textabsorber/) | <p> Rappresenta un oggetto assorbitore di testo. Esegue l'estrazione del testo e fornisce l'accesso al risultato tramite l'oggetto {@code TextAbsorber.Text}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo nella prima pagina del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> L'oggetto {@code TextAbsorber} è usato per estrarre il testo da un documento Pdf o dalla pagina del documento. </p> |
| [TextAnnotation](./textannotation/) | Rappresenta un'annotazione di testo che è una \"nota adesiva\" allegata a un punto nel documento PDF. |
| [TextBoxField](./textboxfield/) | Classe che rappresenta il campo casella di testo. |
| [TextBuilder](./textbuilder/) | Aggiunge l'oggetto testo alla pagina Pdf. |
| [TextDefaults](./textdefaults/) | Definisce i valori predefiniti del sottosistema di testo |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Specifica il tipo di valori predefiniti del sottosistema di testo |
| [TextEditOptions](./texteditoptions/) | Descrive le opzioni delle operazioni di modifica del testo. |
| [TextElement](./textelement/) | Elemento di testo generale della struttura logica del documento. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | Descrive l'errore di estrazione del testo che è comparso nel documento PDF. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Rappresenta la posizione nel documento PDF in cui è comparso l'errore di estrazione del testo. |
| [TextExtractionOptions](./textextractionoptions/) | Rappresenta le opzioni di estrazione del testo |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Definisce diverse modalità che possono essere utilizzate durante la conversione di un documento pdf in testo. Vedi la classe {@code TextDevice}. |
| [TextFormattingOptions](./textformattingoptions/) | Rappresenta le opzioni di formattazione del testo |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Definisce le specifiche dell'interlinea |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Definisce le strategie di interruzione delle parole |
| [TextFragment](./textfragment/) | <p> Rappresenta un frammento di testo PDF. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo font. // Apri documento Document doc = new Document("input.pdf"); // Trova il font che verrà usato per modificare il font del testo del documento Font font = FontRepository.findFont("Arial"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'absorber per la prima pagina doc.getPages().get(1).accept(absorber); // Modifica il testo e il font della prima occorrenza del testo absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salva il documento doc.save("output.pdf"); </pre> <hr> <pre> In poche parole, l'oggetto {@code TextFragment} contiene un elenco di oggetti {@code TextSegment}. In dettaglio: Il testo del documento PDF in {@code com.aspose.pdf} è rappresentato da due oggetti di base: {@code TextFragment} e {@code TextSegment} Le differenze tra loro dipendono principalmente dal contesto. Consideriamo lo scenario seguente. L'utente cerca il testo "hello world" per operare su di esso, modificare le sue proprietà, visualizzarlo ecc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> La rappresentazione fisica del testo PDF è molto complessa. Il testo "hello world" può consistere in diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.Pdf stabilisce fondamentalmente che l'oggetto {@code TextFragment} fornisce un unico insieme di operazioni logiche su un insieme di oggetti {@code TextSegment} fisici che rappresentano la query dell'utente. Nello scenario di ricerca del testo, {@code TextFragment} è la rappresentazione logica del testo "hello world", e la collezione di oggetti {@code TextSegment} rappresenta tutti i segmenti fisici che costruiscono l'oggetto testo "hello world". Quindi, {@code TextFragment} è vicino alla rappresentazione logica del testo. E {@code TextSegment} è vicino alla rappresentazione fisica del testo. Ovviamente ogni oggetto {@code TextSegment} può avere il proprio font, colore e proprietà di posizionamento. {@code TextFragment} fornisce un modo semplice per modificare il testo con le sue proprietà: impostare il font, la dimensione del font, il colore del font ecc. Nel frattempo, gli oggetti {@code TextSegment} sono accessibili e gli utenti possono operare con gli oggetti {@code TextSegment} in modo indipendente. <p> Nota che la modifica delle proprietà di TextFragment può cambiare la collezione interna {@code Segments} perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un unico segmento. Se il tuo requisito è lasciare invariata la collezione {@code Segments}, per favore modifica i segmenti interni individualmente. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina di un documento PDF e sostituire il testo e il suo carattere. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Trova il carattere che verrà usato per modificare il carattere del testo del documento com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get(1).accept(absorber); // Modifica il testo e il carattere della prima occorrenza del testo absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salva il documento doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> L'oggetto {@code TextFragmentAbsorber} è fondamentalmente usato nello scenario di ricerca del testo. Quando la ricerca è completata, le occorrenze sono rappresentate con oggetti {@code TextFragment} contenuti nella collezione {@code TextFragmentAbsorber.TextFragments}. L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (carattere, dimensione del carattere, colore, ecc.). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Rappresenta una collezione di frammenti di testo |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Rappresenta lo stato del testo di un frammento di testo. </p> <hr> <pre> L'esempio dimostra come cambiare il colore del testo e la dimensione del carattere del testo con l'oggetto {@code TextState}. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get(1).accept(absorber); // Cambia il colore di primo piano della prima occorrenza del testo absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Cambia la dimensione del carattere della prima occorrenza del testo absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Salva il documento doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Fornisce un modo per modificare le seguenti proprietà del testo: carattere ({@code TextFragmentState.Font} property) dimensione del carattere ({@code TextFragmentState.FontSize} property) stile del carattere ({@code TextFragmentState.FontStyle} property) colore di primo piano ({@code TextFragmentState.ForegroundColor} property) colore di sfondo ({@code TextFragmentState.BackgroundColor} property) <p> Nota che la modifica delle proprietà {@code TextFragmentState} può modificare la collezione interna {@code TextFragment.Segments} perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un unico segmento. Se il tuo requisito è mantenere invariata la collezione {@code TextFragment.Segments}, modifica i segmenti interni singolarmente. </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | Enumera le icone da utilizzare nella visualizzazione dell'annotazione. |
| [TextIconConverter](./texticonconverter/) | Rappresenta la classe TextIconConverter |
| [TextMarkupAnnotation](./textmarkupannotation/) | Classe base astratta per le annotazioni di markup del testo. |
| [TextOptions](./textoptions/) | Rappresenta le opzioni di elaborazione del testo |
| [TextParagraph](./textparagraph/) | <p> Rappresenta i paragrafi di testo come oggetto di testo multilinea. </p> <hr> <pre> L'esempio dimostra come creare un oggetto di paragrafo di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // crea il paragrafo di testo TextParagraph paragraph = new TextParagraph(); // imposta il rettangolo del paragrafo paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // imposta le opzioni di a capo delle parole paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // aggiunge le linee di stringa paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // aggiunge il paragrafo alla pagina Pdf con il TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // salva il documento Pdf doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | Modalità di sfondo per TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Rappresenta un oggetto assorbitore di paragrafi di testo. Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextParagraphAbsorber.TextParagraphs}. |
| [TextParagraphCollection](./textparagraphcollection/) | Rappresenta una collezione di paragrafi di testo |
| [TextReplaceOptions](./textreplaceoptions/) | Rappresenta le opzioni di sostituzione del testo |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Determina l'azione da eseguire dopo la sostituzione di un frammento di testo con uno più corto. None - nessuna azione, il testo sostituito può sovrapporsi al resto della riga; AdjustSpaceWidth - tenta di regolare gli spazi tra le parole per mantenere la lunghezza della riga; WholeWordsHyphenation - tenta di distribuire le parole tra le righe del paragrafo per mantenere il margine destro del paragrafo; ShiftRestOfLine - sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può essere modificata; Il valore predefinito è ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | Rappresenta le opzioni di ricerca del testo |
| [TextSegment](./textsegment/) | <p> Rappresenta un segmento di testo PDF. </p> <hr> <pre> L'esempio dimostra come cambiare il colore del testo e la dimensione del carattere del testo con l'oggetto {@code TextState} dell'oggetto {@code TextSegment}. // Apri documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get(1).accept(absorber); // Cambia il colore di primo piano del primo segmento di testo della prima occorrenza absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Cambia la dimensione del carattere del primo segmento di testo della prima occorrenza absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Salva il documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> In poche parole, gli oggetti {@code TextSegment} sono figli dell'oggetto {@code TextFragment}. In dettaglio: il testo di un documento PDF in {@code Aspose.Pdf} è rappresentato da due oggetti di base: {@code TextFragment} e {@code TextSegment}. Le differenze tra loro dipendono principalmente dal contesto. Consideriamo lo scenario seguente. L'utente cerca il testo "hello world" per operare su di esso, modificarne le proprietà, ecc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> La rappresentazione fisica del testo PDF è molto complessa. Il testo "hello world" può consistere in diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.PDF stabilisce fondamentalmente che l'oggetto {@code TextFragment} fornisce un unico set di operazioni logiche sui set di oggetti {@code TextSegment} fisici che rappresentano la query dell'utente. In uno scenario di ricerca testo, {@code TextFragment} è la rappresentazione logica del testo "hello world", e la collezione di oggetti {@code TextSegment} rappresenta tutti i segmenti fisici che costruiscono l'oggetto testo "hello world". Quindi, {@code TextFragment} è vicino alla rappresentazione logica del testo. E {@code TextSegment} è vicino alla rappresentazione fisica del testo. Ovviamente ogni oggetto {@code TextSegment} può avere il proprio font, colore, proprietà di posizionamento. {@code TextFragment} fornisce un modo semplice per cambiare il testo con le sue proprietà: impostare il font, impostare la dimensione del font, impostare il colore del font ecc. Nel frattempo gli oggetti {@code TextSegment} sono accessibili e gli utenti possono operare con gli oggetti {@code TextSegment} in modo indipendente. </p> |
| [TextSegmentCollection](./textsegmentcollection/) | Rappresenta una raccolta di segmenti di testo |
| [TextStamp](./textstamp/) | Rappresenta un timbro testuale. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Azione da eseguire se il carattere non è presente nel font. |
| [TextState](./textstate/) | Rappresenta lo stato di un testo |
| [TextStyle](./textstyle/) | Classe che rappresenta il campo checkbox. |
| [TimestampSettings](./timestampsettings/) | Rappresenta le impostazioni OCSP utilizzate durante il processo di firma. |
| [TocInfo](./tocinfo/) | Rappresenta le informazioni dell'indice. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | Questa classe descrive le regole che possono essere usate per risolvere l'errore Adobe Preflight "Il testo non può essere mappato su Unicode". |
| [TrimMarkAnnotation](./trimmarkannotation/) | Rappresenta un'annotazione Trim Mark. I segni di ritaglio sono posizionati agli angoli di una pagina stampata per indicare dove la pagina deve essere ritagliata. |
| [TxtLoadOptions](./txtloadoptions/) | Opzioni di caricamento per la conversione da TXT a PDF. |
| [UnderlineAnnotation](./underlineannotation/) | Rappresenta un'annotazione di sottolineatura che appare come una linea sotto il testo del documento. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | Questa classe rappresenta le opzioni di salvataggio per il salvataggio che utilizza un metodo di conversione unificato (con modello interno di documento unificato). |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Rappresenta una classe con metodo astratto solitamente fornito dalla parte chiamante e gestisce gli eventi di avanzamento provenienti dal convertitore. Di solito tale gestore fornito dal cliente può essere usato per mostrare l'avanzamento totale della conversione sulla console o in una barra di progresso. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | Questa classe rappresenta le informazioni sull'avanzamento della conversione che possono essere usate in un'applicazione esterna per mostrare l'avanzamento della conversione all'utente finale. |
| [WarningCallback](./warningcallback/) | Interfaccia per il supporto del meccanismo di callback dell'utente. |
| [WarningInfo](./warninginfo/) | Oggetto immutabile per incapsulare le informazioni di avviso. |
| [WarningType](./warningtype/) | / * Enum rappresenta il tipo di avviso. / * / |
| [Watermark](./watermark/) | Rappresenta una filigrana della pagina. |
| [WatermarkAnnotation](./watermarkannotation/) | La classe descrive l'oggetto annotazione Watermark. |
| [WatermarkArtifact](./watermarkartifact/) | La classe descrive l'artefatto della filigrana. Questo può essere usato per |
| [WebHyperlink](./webhyperlink/) | Rappresenta un oggetto di collegamento ipertestuale web. |
| [WidgetAnnotation](./widgetannotation/) | Classe che rappresenta l'annotazione widget. |
| [XFA](./xfa/) | Rappresenta il modulo XML relativo all'XML Forms Architecture (XFA). |
| [XfaParserOptions](./xfaparseroptions/) | classe per gestire l'incapsulamento dei dati correlati |
| [XfdfReader](./xfdfreader/) | <p> Classe che esegue la lettura del formato XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | Aggrega i metodi per scrivere annotazioni e campi nel formato file XFDF |
| [XForm](./xform/) | Classe che rappresenta XForm |
| [XFormCollection](./xformcollection/) | Classe che rappresenta la raccolta di XFormCollection. |
| [XImage](./ximage/) | Classe che rappresenta l'oggetto immagine X-Object. |
| [XImage.RawParameters](./ximage.rawparameters/) | Classe che rappresenta i parametri grezzi XImage dell'immagine. |
| [XImageCollection](./ximagecollection/) | Classe che rappresenta la raccolta XImage. |
| [XmlLoadOptions](./xmlloadoptions/) | Rappresenta le opzioni per caricare/importare un file XML in un documento pdf. |
| [XmlSaveOptions](./xmlsaveoptions/) | Opzioni di salvataggio per l'esportazione in formato Xml |
| [XmpField](./xmpfield/) | Rappresenta il campo XMP. |
| [XmpFieldType](./xmpfieldtype/) | Questo enum rappresenta i tipi di un campo XMP. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Categoria della proprietà: interna o esterna. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | Questo schema descrive un campo in un tipo strutturato. È molto simile allo schema PDF/A Property Value Type, ma definisce un campo in una struttura invece di una proprietà. Namespace dello schema URI: http://www.aiim.org/pdfa/ns/field# Prefisso richiesto dello schema: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Rappresenta la classe base per le istanze di field, property, value type. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Descrive una singola proprietà. Namespace dello schema URI: http://www.aiim.org/pdfa/ns/property# Prefisso richiesto dello schema: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Descrive lo schema di estensione XMP fornito da PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Rappresenta la descrizione dello schema di estensione XMP fornito da PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | Lo schema PDF/A ValueType è richiesto per tutti i tipi di valore di proprietà che non sono definiti nella specifica XMP 2004, cioè per i tipi di valore al di fuori della seguente lista: - Tipi di array (sono tipi contenitori che possono contenere uno o più campi): Alt, Bag, Seq - Tipi di valore di base: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipi di valore per la gestione dei media: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo di valore base per Job/Workflow: Job - Tipi di valore dello schema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Namespace dello schema URI: http://www.aiim.org/pdfa/ns/type# Prefisso richiesto dello schema: pdfaType |
| [XmpValue](./xmpvalue/) | Rappresenta il valore XMP. |
| [XpsLoadOptions](./xpsloadoptions/) | Rappresenta le opzioni per caricare/importare un file xps in un documento pdf. |
| [XpsSaveOptions](./xpssaveoptions/) | Opzioni di salvataggio per l'esportazione al formato Xps |
| [XslFoLoadOptions](./xslfoloadoptions/) | Rappresenta le opzioni per caricare/importare un file XSL-FO in un documento pdf. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | Il documento XSLFO di origine può contenere errori di formattazione. Questo enum elenca le possibili strategie di gestione di tali errori di formattazione. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate (left, top) posizionate nell'angolo superiore sinistro della finestra e il contenuto della pagina ingrandito del fattore zoom. Un valore null per uno qualsiasi dei parametri left, top o zoom indica che il valore corrente di quel parametro deve rimanere invariato. Un valore di zoom pari a 0 ha lo stesso significato di un valore null. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| Enum | Descrizione |
| --- | --- |
| [AFRelationship](./afrelationship/) | L'enumerazione descrive la relazione dei file associati. |
| [AnnotationState](./annotationstate/) | L'enumerazione degli stati a cui può essere impostata l'annotazione originale. |
| [AnnotationStateModel](./annotationstatemodel/) | Il modello di stato corrispondente allo stato dell'annotazione. |
| [AnnotationType](./annotationtype/) | Enumerazione dei tipi di annotazione. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Enumerazione del sottotipo possibile di artefatti. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Enumerazione dei possibili tipi di artefatto. |
| [BlendMode](./blendmode/) | L'enumerazione delle modalità di fusione. |
| [BorderCornerStyle](./bordercornerstyle/) | Enumera gli stili degli angoli del bordo. |
| [BorderEffect](./bordereffect/) | Descrive l'effetto che dovrebbe essere applicato al bordo delle annotazioni. |
| [BorderStyle](./borderstyle/) | Descrive lo stile del bordo dell'annotazione. |
| [BoxStyle](./boxstyle/) | Rappresenta gli stili per disegnare il segno di spunta nella casella di controllo. |
| [CapStyle](./capstyle/) | Stile della fine linea dell'annotazione a inchiostro. |
| [CaptionPosition](./captionposition/) | Enumerazione del posizionamento della didascalia dell'annotazione. |
| [CaretSymbol](./caretsymbol/) | Un simbolo da associare al cursore. |
| [ColorsOfCMYK](./colorsofcmyk/) | Colori inclusi nel modello di colore CMYK. |
| [ColorSpace](./colorspace/) | L'enumerazione degli spazi colore. |
| [ColorType](./colortype/) | Specifica il tipo di colore degli elementi nella pagina. |
| [ColumnAdjustment](./columnadjustment/) | Enumera i tipi di regolazione della colonna. |
| [ContentDisposition](./contentdisposition/) | Intestazione Content-Disposition del protocollo MIME. |
| [ConvertErrorAction](./converterroraction/) | Questa classe rappresenta l'azione per gli errori di conversione. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | Questa azione rappresenta le operazioni per la conversione di immagini con maschera morbida. |
| [ConvertTransparencyAction](./converttransparencyaction/) | Questa classe rappresenta l'azione per la conversione della trasparenza. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Rappresenta il tipo di algoritmo crittografico utilizzato nelle routine di crittografia/decrittografia. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * Il namespace {@code Aspose.Pdf.Security } contiene classi utilizzate per la crittografia e la firma digitale. / * / |
| [DefaultState](./defaultstate/) | Rappresenta lo stato predefinito di un livello PDF. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Rappresenta il tipo di algoritmo che mappa i dati in un \"hash\" |
| [Direction](./direction/) | Direzione del testo. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Le autorizzazioni di accesso concesse per questo documento. I valori validi sono: 1 - Non sono consentite modifiche al documento; qualsiasi modifica al documento invalida la firma. 2 - Le modifiche consentite sono la compilazione di moduli, l'istanziazione di modelli di pagina e la firma; altre modifiche invalidano la firma. 3 - Le modifiche consentite sono le stesse della voce 2, oltre alla creazione, eliminazione e modifica di annotazioni; altre modifiche invalidano la firma. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | Consente di specificare il formato file .doc o .docx. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Consente di controllare come un documento PDF viene convertito in un documento di elaborazione testi. Utilizzare la modalità **RecognitionMode.Textbox** quando il documento risultante non sarà modificato intensamente. Le caselle di testo sono facili da modificare quando non c'è molto da fare. Utilizzare la modalità **RecognitionMode.Flow** quando il documento di output necessita di ulteriori modifiche. I paragrafi e le linee di testo nella modalità flow consentono una facile modifica del testo, ma gli oggetti di formattazione non supportati appariranno peggio rispetto alla modalità **RecognitionMode.Textbox**. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | Quando un file PDF (che di solito ha un layout fisso) viene convertito, il motore di conversione tenta di eseguire raggruppamenti e analisi a più livelli per ripristinare l'intento originale dell'autore del documento e produrre un risultato in layout fluido. Questa proprietà regola tale conversione per il metodo desiderato di riconoscimento del contenuto. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumera i tipi di destinazioni esplicite. |
| [ExtendedBoolean](./extendedboolean/) | Rappresenta un tipo booleano che supporta il valore Undefined. |
| [ExtractImageMode](./extractimagemode/) | Definisce diverse modalità che possono essere utilizzate durante l'estrazione di immagini dai documenti. |
| [FileEncoding](./fileencoding/) | Codifica del file allegato. Valori possibili: Zip - il file è compresso con ZIP, None - il file non è compresso. |
| [FileIcon](./fileicon/) | Un'icona da utilizzare nella visualizzazione dell'annotazione. |
| [Fixup](./fixup/) | Questo enum rappresenta un tipo di Fixup. |
| [FormType](./formtype/) | Enumerazione dei possibili tipi di Acro Form. |
| [FreeTextIntent](./freetextintent/) | Enumera le intenzioni dell'annotazione di testo libero. |
| [HighlightingMode](./highlightingmode/) | Enumera la modalità di evidenziazione dell'annotazione, l'effetto visivo da utilizzare quando il pulsante del mouse è premuto o tenuto premuto all'interno della sua area attiva. |
| [HorizontalAlignment](./horizontalalignment/) | Descrive l'allineamento orizzontale. |
| [HtmlDocumentType](./htmldocumenttype/) | Rappresenta l'enumerazione dei tipi di documento Html. |
| [HtmlMediaType](./htmlmediatype/) | Specifica i possibili tipi di media utilizzati durante il rendering. |
| [IconCaptionPosition](./iconcaptionposition/) | Descrive la posizione dell'icona. |
| [ImageFileType](./imagefiletype/) | Enumera i tipi di file immagine. |
| [ImageFilterType](./imagefiltertype/) | Enumerazione che rappresenta il tipo di filtro immagine. |
| [ImageFormat](./imageformat/) | Questo enum rappresenta i formati immagine. |
| [ImportFormat](./importformat/) | Specifica il formato di importazione. |
| [Justification](./justification/) | Enumera le forme di allineamento (giustificazione) da utilizzare nella visualizzazione del testo dell'annotazione. |
| [LaunchActionOperation](./launchactionoperation/) | Elenca le operazioni da eseguire con il documento durante l'esecuzione dell'azione di avvio. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Elenca le possibili modalità di posizionamento delle lettere nelle parole nell'HTML risultante. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: insieme di tipi di schema di illuminazione. |
| [LineEnding](./lineending/) | Elenca gli stili di terminazione della linea da utilizzare nel disegno della linea. |
| [LineIntent](./lineintent/) | Elenca le intenzioni dell'annotazione di linea. |
| [LoadFormat](./loadformat/) | Specifica il formato di caricamento. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Valore che indica in che modo i valori frazionari sono visualizzati. |
| [NumberingStyle](./numberingstyle/) | Enumerazione degli stili di numerazione di pagina supportati per la classe PageLabel. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Specifica la posizione in un flusso da utilizzare per la ricerca. |
| [PageCoordinateType](./pagecoordinatetype/) | Descrive il tipo di coordinate della pagina. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Descrive il layout della pagina. |
| [PageMode](./pagemode/) | La classe descrive i componenti utilizzati della pagina del documento. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Specifica la variante per determinare la posizione dell'elemento sulla pagina. |
| [PasswordType](./passwordtype/) | Questa enum rappresenta i tipi di password noti utilizzati per i documenti PDF protetti da password. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: insieme di modalità di attivazione dell'annotazione 3D. |
| [PdfFormat](./pdfformat/) | Questa classe rappresenta un formato PDF. |
| [PdfVersion](./pdfversion/) | Questa enum rappresenta la versione del file PDF. |
| [PolyIntent](./polyintent/) | Elenca le intenzioni dell'annotazione di poligono o polilinea. |
| [PredefinedAction](./predefinedaction/) | Definisce diverse azioni che possono essere attivate da un file PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Rappresenta una posizione di un segno in un angolo della pagina. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Rappresenta una posizione di un segno di registrazione su una pagina. |
| [ReplyType](./replytype/) | Elenca i tipi di relazioni (il "tipo di risposta") tra l'annotazione e quella specificata da InReplyTo. |
| [ReturnAction](./returnaction/) | Enum rappresenta un'azione del flusso di lavoro del programma nel caso di invocazione del metodo {@code IWarningCallback.Warning(WarningInfo)}. |
| [Rotation](./rotation/) | Enumerazione dei possibili valori di rotazione. |
| [SaveFormat](./saveformat/) | Specifica il formato |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Rappresenta i tipi di linea che possono essere usati nel documento risultato per disegnare bordi o altre linee |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | elenca i possibili tipi di risorse esterne salvate |
| [StampIcon](./stampicon/) | Enumera le icone da utilizzare nella visualizzazione dell'annotazione. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | elenca i possibili tipi di file immagine che possono essere salvati come risorse esterne durante la conversione da Pdf a SVG |
| [TextAlignment](./textalignment/) | Allineamento del testo nell'annotazione. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Modalità di elaborazione del percorso di ritaglio |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Comportamento della sostituzione dei caratteri. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Modalità di trasformazione della lingua |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Azione da eseguire se il font non contiene il carattere richiesto |
| [TextRenderingMode](./textrenderingmode/) | La modalità di rendering del testo, Tmode, determina se la visualizzazione del testo deve far sì che i contorni dei glifi siano tracciati, riempiti, usati come limite di ritaglio, o una combinazione dei tre. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Specifica una politica su come la dimensione del font del testo debba essere regolata per adattarsi a un'area contenente. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Ambito in cui l'operazione di sostituzione del testo è applicata REPLACE_FIRST per impostazione predefinita. Questa opzione obsoleta è stata mantenuta per compatibilità. Influisce su PdfContentEditor e non ha effetto su TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | Enumerazione dei possibili valori di allineamento verticale. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
