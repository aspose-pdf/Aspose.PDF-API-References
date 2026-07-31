---
title: "Aspose.Pdf.Annotations"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Lo spazio dei nomi Aspose.Pdf.Annotations fornisce classi per lavorare con vari tipi di destinazioni di azioni e altre funzionalità del documento tradizionalmente chiamate interattive, fornendo mezzi con cui l'utente può interagire con esso."
type: docs
weight: 50
url: /it/net/aspose.pdf.annotations/
---
Lo spazio dei nomi **Aspose.Pdf.Annotations** fornisce classi per lavorare con vari tipi di azioni, destinazioni e altre funzionalità del documento tradizionalmente chiamate interattive, offrendo mezzi con cui l'utente può interagire con esso.

## Classi

| Classe | Descrizione |
| --- | --- |
| [ActionCollection](./actioncollection/) | Raccolta di azioni |
| [Annotation](./annotation/) | Classe che rappresenta l'oggetto annotazione. |
| [AnnotationActionCollection](./annotationactioncollection/) | Rappresenta la raccolta di azioni di annotazione. |
| [AnnotationCollection](./annotationcollection/) | Classe che rappresenta la raccolta di annotazioni. |
| [AnnotationSelector](./annotationselector/) | Questa classe è usata per selezionare le annotazioni utilizzando l'idea del modello Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Dizionario di aspetto dell'annotazione che specifica come l'annotazione deve essere presentata visivamente sulla pagina. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Rappresenta un'annotazione Bleed Mark. |
| [Border](./border/) | Classe che rappresenta le caratteristiche del bordo dell'annotazione. |
| [CaretAnnotation](./caretannotation/) | Classe che rappresenta l'annotazione Caret. |
| [Characteristics](./characteristics/) | Rappresenta le caratteristiche dell'annotazione |
| [CircleAnnotation](./circleannotation/) | Classe che rappresenta l'annotazione Circle. |
| [ColorBarAnnotation](./colorbarannotation/) | Classe che rappresenta l'annotazione ColorBarAnnotation. La proprietà Color è ignorata, invece viene usato il colore ColorsOfCMYK. Alla creazione, il rapporto tra larghezza e altezza determina l'orientamento dell'annotazione - orizzontale o verticale. Successivamente, verifica che il rettangolo dell'annotazione sia al di fuori del TrimBox e, in caso contrario, lo sposta nella posizione più vicina al di fuori del TrimBox, tenendo conto dell'orientamento dell'annotazione. È possibile ridurre la larghezza (altezza) affinché l'annotazione si adatti al di fuori del TrimBox. Se non c'è spazio per il layout, larghezza/altezza può essere impostata a zero (in tal caso, l'annotazione è presente nella pagina, ma non viene visualizzata). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Classe astratta che rappresenta l'annotazione figura comune. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Rappresenta i tipi di annotazione che vengono posizionati negli angoli della pagina stampata. |
| [CustomExplicitDestination](./customexplicitdestination/) | Rappresenta una destinazione esplicita personalizzata. |
| [Dash](./dash/) | Classe che rappresenta il modello di tratteggio della linea. |
| [DefaultAppearance](./defaultappearance/) | Descrive l'aspetto predefinito del campo (font, dimensione del testo e colore). |
| [DocumentActionCollection](./documentactioncollection/) | Classe che descrive le azioni eseguite su alcune azioni con il documento. |
| [ExplicitDestination](./explicitdestination/) | Rappresenta la classe base per destinazioni esplicite in un documento PDF. |
| [FdfReader](./fdfreader/) | Classe che esegue la lettura del formato FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Classe che descrive l'annotazione di allegato file. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far entrare interamente la sua area di delimitazione nella finestra sia orizzontalmente sia verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando l'area di delimitazione nella finestra nell'altra dimensione. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata verticale superiore posizionata sul bordo superiore della finestra e i contenuti della pagina ingranditi appena a sufficienza per far entrare l'intera larghezza della sua area di delimitazione nella finestra. Un valore nullo per top indica che il valore corrente di quel parametro deve essere mantenuto invariato. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata orizzontale sinistra posizionata sul bordo sinistro della finestra e i contenuti della pagina ingranditi appena a sufficienza per far entrare l'intera altezza della sua area di delimitazione nella finestra. Un valore nullo per left indica che il valore corrente di quel parametro deve essere mantenuto invariato. |
| [FitExplicitDestination](./fitexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far entrare l'intera pagina nella finestra sia orizzontalmente sia verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando la pagina nella finestra nell'altra dimensione. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata verticale superiore posizionata sul bordo superiore della finestra e i contenuti della pagina ingranditi appena a sufficienza per far entrare l'intera larghezza della pagina nella finestra. Un valore nullo per top indica che il valore corrente di quel parametro deve essere mantenuto invariato. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far entrare interamente nella finestra, sia orizzontalmente sia verticalmente, il rettangolo specificato dalle coordinate left, bottom, right e top. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo nella finestra nell'altra dimensione. Un valore nullo per uno qualsiasi dei parametri può provocare un comportamento imprevedibile. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata orizzontale sinistra posizionata sul bordo sinistro della finestra e i contenuti della pagina ingranditi appena a sufficienza per far entrare l'intera altezza della pagina nella finestra. Un valore nullo per left indica che il valore corrente di quel parametro deve essere mantenuto invariato. |
| [FixedPrint](./fixedprint/) | Rappresenta i dati di stampa fissi dell'annotazione Watermark. |
| [FreeTextAnnotation](./freetextannotation/) | Rappresenta un'annotazione di testo libero che visualizza il testo direttamente sulla pagina. A differenza di un'annotazione di testo ordinaria, un'annotazione di testo libero non ha uno stato aperto o chiuso; invece di essere visualizzata in una finestra pop-up, il testo è sempre visibile. |
| [GoToAction](./gotoaction/) | Rappresenta un'azione vai-a che cambia la visualizzazione verso una destinazione specificata (pagina, posizione e fattore di ingrandimento). |
| [GoToRemoteAction](./gotoremoteaction/) | Rappresenta un'azione vai-a remota simile a un'azione vai-a ordinaria ma salta a una destinazione in un altro file PDF invece del file corrente. |
| [GoToURIAction](./gotouriaction/) | Rappresenta un'azione URI che provoca la risoluzione di un URI. |
| [HideAction](./hideaction/) | Rappresenta un'azione nascondi che nasconde o mostra una o più annotazioni sullo schermo impostando o cancellando i loro flag Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Rappresenta un'annotazione evidenzia che mette in evidenza un intervallo di testo nel documento. |
| [ImportDataAction](./importdataaction/) | All'invocazione di un'azione import-data, i dati Forms Data Format (FDF) devono essere importati nel modulo interattivo del documento da un file specificato. |
| [InkAnnotation](./inkannotation/) | Rappresenta uno "scarabocchio" a mano libera composto da uno o più percorsi disgiunti. |
| [JavascriptAction](./javascriptaction/) | Classe che rappresenta l'azione javascript. |
| [LaunchAction](./launchaction/) | Rappresenta un'azione di avvio che avvia un'applicazione o apre o stampa un documento. |
| [LineAnnotation](./lineannotation/) | Classe che rappresenta l'annotazione di linea. |
| [LinkAnnotation](./linkannotation/) | Rappresenta un collegamento ipertestuale a una destinazione altrove nel documento o un'azione da eseguire. |
| [MarkupAnnotation](./markupannotation/) | Classe astratta che rappresenta l'annotazione di markup. |
| [Measure](./measure/) | Classe che descrive il sistema di coordinate Measure. |
| [MediaClip](./mediaclip/) | Classe che descrive l'oggetto media clip della resa. |
| [MediaClipData](./mediaclipdata/) | Classe che descrive i dati del media clip. |
| [MediaClipSection](./mediaclipsection/) | Questa classe descrive la sezione Media clip. |
| [MediaRendition](./mediarendition/) | Classe che descrive la resa media. |
| [MovieAnnotation](./movieannotation/) | Rappresenta un'annotazione video che contiene grafica animata e suono da presentare sullo schermo del computer e attraverso gli altoparlanti. Quando l'annotazione è attivata, il video viene riprodotto. |
| [NamedAction](./namedaction/) | Rappresenta azioni nominate che le applicazioni visualizzatrici PDF dovrebbero supportare. |
| [NamedDestination](./nameddestination/) | Invece di essere definita direttamente con la sintassi esplicita, una destinazione può essere riferita indirettamente tramite un oggetto nome o una stringa di byte. |
| [PageInformationAnnotation](./pageinformationannotation/) | Rappresenta un'annotazione di informazioni sulla pagina in un documento PDF. Questa annotazione contiene il nome del file, il numero di pagina e la data e l'ora di creazione dell'annotazione. |
| [PDF3DAnnotation](./pdf3dannotation/) | Classe PDF3DAnnotation. Questa classe non può essere ereditata. |
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
| [PdfAction](./pdfaction/) | Rappresenta l'Azione in un documento PDF |
| [PdfActionCollection](./pdfactioncollection/) | La classe descrive l'elenco delle azioni. |
| [PolyAnnotation](./polyannotation/) | Classe base astratta per le annotazioni poligonali. |
| [PolygonAnnotation](./polygonannotation/) | Classe che rappresenta l'annotazione poligono. |
| [PolylineAnnotation](./polylineannotation/) | Rappresenta l'annotazione polilinea che è simile al poligono, tranne per il fatto che il primo e l'ultimo vertice non sono collegati implicitamente. |
| [PopupAnnotation](./popupannotation/) | Rappresenta l'annotazione pop-up che visualizza il testo in una finestra pop-up per l'inserimento e la modifica. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Classe astratta che rappresenta l'annotazione di segno di stampa. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Fornisce metodi di estensione per l'enumerazione [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Rappresenta l'annotazione Redact. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Rappresenta un'annotazione Registration Mark. |
| [Rendition](./rendition/) | Classe che descrive l'oggetto di resa di RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Un'azione di resa che controlla la riproduzione di contenuti multimediali. |
| [RichMediaAnnotation](./richmediaannotation/) | Classe che descrive RichMediaAnnotation che consente di incorporare dati video/audio nel documento PDF. |
| [ScreenAnnotation](./screenannotation/) | Un'annotazione schermo che specifica una regione di una pagina su cui possono essere riprodotti clip multimediali. |
| [SelectorRendition](./selectorrendition/) | Classe che descrive la resa del selettore. |
| [SoundAnnotation](./soundannotation/) | Rappresenta un'annotazione audio che contiene suono registrato dal microfono del computer o importato da un file. |
| [SoundData](./sounddata/) | Rappresenta i dati audio che definiscono il suono da riprodurre quando l'annotazione è attivata. |
| [SoundSampleData](./soundsampledata/) | Rappresenta voci aggiuntive specifiche per un oggetto audio (Sezione 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Classe che rappresenta l'annotazione quadrata. |
| [SquigglyAnnotation](./squigglyannotation/) | Rappresenta l'annotazione squiggly che appare come una sottolineatura irregolare nel testo di un documento. |
| [StampAnnotation](./stampannotation/) | Rappresenta l'annotazione timbro di gomma. Questo tipo di annotazione visualizza testo o grafica destinati a sembrare stampati sulla pagina con un timbro di gomma. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Rappresenta un'annotazione barrata che appare come barratura nel testo del documento. |
| [SubmitFormAction](./submitformaction/) | Classe che descrive l'azione submit-form. |
| [TextAnnotation](./textannotation/) | Rappresenta un'annotazione di testo che è una 'nota adesiva' allegata a un punto nel documento PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Classe base astratta per le annotazioni di markup del testo. |
| [TextStyle](./textstyle/) | Classe che rappresenta lo stile del testo nell'annotazione. |
| [TrimMarkAnnotation](./trimmarkannotation/) | Rappresenta un'annotazione Trim Mark. |
| [UnderlineAnnotation](./underlineannotation/) | Rappresenta un'annotazione di sottolineatura che appare come una sottolineatura nel testo del documento. |
| [WatermarkAnnotation](./watermarkannotation/) | La classe descrive l'oggetto annotazione Watermark. |
| [WidgetAnnotation](./widgetannotation/) | Classe che rappresenta l'annotazione widget. |
| [XfdfReader](./xfdfreader/) | Classe che esegue la lettura del formato XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate (left, top) posizionate nell'angolo superiore sinistro della finestra e il contenuto della pagina ingrandito del fattore zoom. Un valore nullo per ciascuno dei parametri left, top o zoom specifica che il valore corrente di quel parametro deve essere mantenuto invariato. Un valore di zoom pari a 0 ha lo stesso significato di un valore nullo. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Definisce Visitor per visitare diverse annotazioni del documento. |
| [IAppointment](./iappointment/) | Rappresenta l'interfaccia generale per azioni e destinazioni. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Un insieme di flag che specificano varie caratteristiche dell'annotazione. |
| [AnnotationState](./annotationstate/) | L'enumerazione degli stati a cui può essere impostata l'annotazione originale. |
| [AnnotationStateModel](./annotationstatemodel/) | Il modello di stato corrispondente allo stato dell'annotazione. |
| [AnnotationType](./annotationtype/) | Enumerazione dei tipi di annotazione. |
| [BorderEffect](./bordereffect/) | Descrive l'effetto che dovrebbe essere applicato al bordo delle annotazioni. |
| [BorderStyle](./borderstyle/) | Descrive lo stile del bordo dell'annotazione. |
| [CapStyle](./capstyle/) | Stile dell'estremità della linea dell'annotazione Ink. |
| [CaptionPosition](./captionposition/) | Enumerazione del posizionamento della didascalia dell'annotazione. |
| [CaretSymbol](./caretsymbol/) | Un simbolo da associare al cursore. |
| [ColorsOfCMYK](./colorsofcmyk/) | Colori inclusi nel modello di colore CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumera i tipi di destinazioni esplicite. |
| [FileIcon](./fileicon/) | Un'icona da utilizzare nella visualizzazione dell'annotazione. |
| [FreeTextIntent](./freetextintent/) | Enumera le intenzioni dell'annotazione di testo libero. |
| [HighlightingMode](./highlightingmode/) | Enumera la modalità di evidenziazione dell'annotazione, l'effetto visivo da utilizzare quando il pulsante del mouse è premuto o tenuto premuto all'interno della sua area attiva. |
| [Justification](./justification/) | Enumera le forme di allineamento (giustificazione) da utilizzare nella visualizzazione del testo dell'annotazione. |
| [LaunchActionOperation](./launchactionoperation/) | Enumera le operazioni da eseguire sul documento durante l'esecuzione dell'azione di avvio. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: insieme di tipi di schema di illuminazione. |
| [LineEnding](./lineending/) | Elenca gli stili di terminazione della linea da utilizzare nel disegno della linea. |
| [LineIntent](./lineintent/) | Elenca le intenzioni dell'annotazione di linea. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: insieme di modalità di attivazione dell'annotazione 3D. |
| [PolyIntent](./polyintent/) | Elenca le intenzioni dell'annotazione di poligono o polilinea. |
| [PredefinedAction](./predefinedaction/) | Definisce diverse azioni che possono essere attivate da un file PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Rappresenta una posizione di un segno in un angolo di una pagina. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Rappresenta una posizione di un segno di registrazione su una pagina. |
| [PrinterMarksKind](./printermarkskind/) | Specifica i tipi di segni della stampante da aggiungere a un documento. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: insieme di tipi di modalità di rendering |
| [RenditionOperation](./renditionoperation/) | L'operazione da eseguire quando l'azione viene attivata. |
| [RenditionType](./renditiontype/) | L'enumerazione descrive i possibili tipi di Rendition. |
| [ReplyType](./replytype/) | Elenca i tipi di relazioni (il "tipo di risposta") tra l'annotazione e quella specificata da InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Opzioni per lo stile dei frammenti di testo in RichText. |
| [SoundEncoding](./soundencoding/) | Il formato di codifica per i dati di esempio. |
| [SoundIcon](./soundicon/) | Elenca le icone da utilizzare nella visualizzazione dell'annotazione. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Il formato di codifica per i dati del campione audio. |
| [StampIcon](./stampicon/) | Elenca le icone da utilizzare nella visualizzazione dell'annotazione. |
| [TextIcon](./texticon/) | Elenca le icone da utilizzare nella visualizzazione dell'annotazione. |


