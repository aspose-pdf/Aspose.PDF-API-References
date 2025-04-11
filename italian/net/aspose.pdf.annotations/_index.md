---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: Lo spazio dei nomi Aspose.Pdf.Annotations fornisce classi per lavorare con vari tipi di azioni, destinazioni e altre caratteristiche del documento che tradizionalmente vengono chiamate interattive, fornendo mezzi affinché l'utente possa intercomunicare con esso.
type: docs
weight: 50
url: /it/net/aspose.pdf.annotations/
---
Lo **spazio dei nomi Aspose.Pdf.Annotations** fornisce classi per lavorare con vari tipi di azioni, destinazioni e altre caratteristiche del documento che tradizionalmente vengono chiamate interattive, fornendo mezzi affinché l'utente possa intercomunicare con esso.

## Classi

| Classe | Descrizione |
| --- | --- |
| [ActionCollection](./actioncollection/) | Collezione di azioni |
| [Annotation](./annotation/) | Classe che rappresenta l'oggetto annotazione. |
| [AnnotationActionCollection](./annotationactioncollection/) | Rappresenta la collezione di azioni di annotazione. |
| [AnnotationCollection](./annotationcollection/) | Classe che rappresenta la collezione di annotazioni. |
| [AnnotationSelector](./annotationselector/) | Questa classe è utilizzata per selezionare annotazioni utilizzando l'idea del modello Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Dizionario dell'aspetto dell'annotazione che specifica come l'annotazione deve essere presentata visivamente sulla pagina. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Rappresenta un'annotazione di Bleed Mark. |
| [Border](./border/) | Classe che rappresenta le caratteristiche del bordo dell'annotazione. |
| [CaretAnnotation](./caretannotation/) | Classe che rappresenta l'annotazione Caret. |
| [Characteristics](./characteristics/) | Rappresenta le caratteristiche dell'annotazione |
| [CircleAnnotation](./circleannotation/) | Classe che rappresenta l'annotazione Circle. |
| [ColorBarAnnotation](./colorbarannotation/) | Classe che rappresenta l'annotazione ColorBarAnnotation. Proprietà Color ignorata, invece utilizzata ColorsOfCMYK colore. Alla creazione, il rapporto di larghezza e altezza determina l'orientamento dell'annotazione - orizzontale o verticale. Successivamente, controlla che il rettangolo dell'annotazione sia al di fuori del TrimBox, e se non lo è, viene spostato nella posizione più vicina al di fuori del TrimBox, tenendo conto dell'orientamento dell'annotazione. È possibile ridurre la larghezza (altezza) in modo che l'annotazione si adatti al di fuori del TrimBox. Se non c'è spazio per il layout, la larghezza/altezza può essere impostata su zero (in questo caso, l'annotazione è presente sulla pagina, ma non visualizzata). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Classe astratta che rappresenta l'annotazione figura comune. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Rappresenta i tipi di annotazione che sono posizionati negli angoli della pagina stampata. |
| [CustomExplicitDestination](./customexplicitdestination/) | Rappresenta una destinazione esplicita personalizzata. |
| [Dash](./dash/) | Classe che rappresenta il modello di tratteggio della linea. |
| [DefaultAppearance](./defaultappearance/) | Descrive l'aspetto predefinito del campo (font, dimensione e colore del testo). |
| [DocumentActionCollection](./documentactioncollection/) | Classe che descrive le azioni eseguite su alcune azioni con il documento |
| [ExplicitDestination](./explicitdestination/) | Rappresenta la classe base per le destinazioni esplicite nel documento PDF. |
| [FdfReader](./fdfreader/) | Classe che esegue la lettura del formato FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Classe che descrive l'annotazione di allegato file. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi giusto abbastanza per adattarsi completamente alla sua area di delimitazione all'interno della finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando l'area di delimitazione all'interno della finestra nell'altra dimensione. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata verticale superiore posizionata al bordo superiore della finestra e i contenuti della pagina ingranditi giusto abbastanza per adattarsi all'intera larghezza della sua area di delimitazione all'interno della finestra. Un valore nullo per la parte superiore specifica che il valore attuale di quel parametro deve essere mantenuto invariato. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata orizzontale sinistra posizionata al bordo sinistro della finestra e i contenuti della pagina ingranditi giusto abbastanza per adattarsi all'intera altezza della sua area di delimitazione all'interno della finestra. Un valore nullo per sinistra specifica che il valore attuale di quel parametro deve essere mantenuto invariato. |
| [FitExplicitDestination](./fitexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi giusto abbastanza per adattarsi all'intera pagina all'interno della finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando la pagina all'interno della finestra nell'altra dimensione. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata verticale superiore posizionata al bordo superiore della finestra e i contenuti della pagina ingranditi giusto abbastanza per adattarsi all'intera larghezza della pagina all'interno della finestra. Un valore nullo per la parte superiore specifica che il valore attuale di quel parametro deve essere mantenuto invariato. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi giusto abbastanza per adattarsi al rettangolo specificato dalle coordinate sinistra, inferiore, destra e superiore completamente all'interno della finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo all'interno della finestra nell'altra dimensione. Un valore nullo per uno qualsiasi dei parametri può comportare un comportamento imprevedibile. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata orizzontale sinistra posizionata al bordo sinistro della finestra e i contenuti della pagina ingranditi giusto abbastanza per adattarsi all'intera altezza della pagina all'interno della finestra. Un valore nullo per sinistra specifica che il valore attuale di quel parametro deve essere mantenuto invariato. |
| [FixedPrint](./fixedprint/) | Rappresenta i dati di stampa fissa dell'annotazione Watermark. |
| [FreeTextAnnotation](./freetextannotation/) | Rappresenta un'annotazione di testo libero che visualizza testo direttamente sulla pagina. A differenza di un'annotazione di testo ordinaria, un'annotazione di testo libero non ha uno stato aperto o chiuso; invece di essere visualizzato in una finestra pop-up, il testo è sempre visibile. |
| [GoToAction](./gotoaction/) | Rappresenta un'azione di go-to che cambia la vista a una destinazione specificata (pagina, posizione e fattore di ingrandimento). |
| [GoToRemoteAction](./gotoremoteaction/) | Rappresenta un'azione di go-to remota che è simile a un'azione di go-to ordinaria ma salta a una destinazione in un altro file PDF invece che nel file corrente. |
| [GoToURIAction](./gotouriaction/) | Rappresenta un'azione URI che causa la risoluzione di un URI. |
| [HideAction](./hideaction/) | Rappresenta un'azione di nascondere che nasconde o mostra una o più annotazioni sullo schermo impostando o cancellando i loro flag Hidden. |
| [HighlightAnnotation](./highlightannotation/) | Rappresenta un'annotazione di evidenziazione che evidenzia un intervallo di testo nel documento. |
| [ImportDataAction](./importdataaction/) | All'invocazione di un'azione di importazione dati, i dati del Formato Dati Moduli (FDF) devono essere importati nel modulo interattivo del documento da un file specificato. |
| [InkAnnotation](./inkannotation/) | Rappresenta un "scarabocchio" a mano libera composto da uno o più percorsi disgiunti. |
| [JavascriptAction](./javascriptaction/) | Classe che rappresenta l'azione javascript. |
| [LaunchAction](./launchaction/) | Rappresenta un'azione di avvio che avvia un'applicazione o apre o stampa un documento. |
| [LineAnnotation](./lineannotation/) | Classe che rappresenta l'annotazione di linea. |
| [LinkAnnotation](./linkannotation/) | Rappresenta un collegamento ipertestuale a una destinazione altrove nel documento o un'azione da eseguire. |
| [MarkupAnnotation](./markupannotation/) | Classe astratta che rappresenta l'annotazione di markup. |
| [Measure](./measure/) | Classe che descrive il sistema di coordinate Measure. |
| [MediaClip](./mediaclip/) | Classe che descrive l'oggetto clip multimediale di rappresentazione. |
| [MediaClipData](./mediaclipdata/) | Classe che descrive i dati del clip multimediale. |
| [MediaClipSection](./mediaclipsection/) | Questa classe descrive la sezione del clip multimediale. |
| [MediaRendition](./mediarendition/) | Classe che descrive la rappresentazione multimediale. |
| [MovieAnnotation](./movieannotation/) | Rappresenta un'annotazione di film che contiene grafica animata e suono da presentare sullo schermo del computer e attraverso gli altoparlanti. Quando l'annotazione è attivata, il film viene riprodotto. |
| [NamedAction](./namedaction/) | Rappresenta azioni nominate che le applicazioni di visualizzazione PDF si aspettano di supportare. |
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
| [PdfAction](./pdfaction/) | Rappresenta l'azione nel documento PDF |
| [PdfActionCollection](./pdfactioncollection/) | Classe che descrive l'elenco delle azioni. |
| [PolyAnnotation](./polyannotation/) | Classe base astratta per le annotazioni poligonali. |
| [PolygonAnnotation](./polygonannotation/) | Classe che rappresenta l'annotazione poligonale. |
| [PolylineAnnotation](./polylineannotation/) | Rappresenta l'annotazione polilinea che è simile al poligono, tranne per il fatto che il primo e l'ultimo vertice non sono connessi implicitamente. |
| [PopupAnnotation](./popupannotation/) | Rappresenta l'annotazione pop-up che visualizza testo in una finestra pop-up per l'inserimento e la modifica. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Classe astratta che rappresenta l'annotazione del marchio della stampante. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Fornisce metodi di estensione per l'enumerazione [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Rappresenta l'annotazione di Redact. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Rappresenta un'annotazione di Registration Mark. |
| [Rendition](./rendition/) | Classe che descrive l'oggetto di rappresentazione dell'annotazione di rappresentazione. |
| [RenditionAction](./renditionaction/) | Un'azione di rappresentazione che controlla la riproduzione di contenuti multimediali. |
| [RichMediaAnnotation](./richmediaannotation/) | Classe che descrive RichMediaAnnotation che consente di incorporare dati video/audio nel documento PDF. |
| [ScreenAnnotation](./screenannotation/) | Un'annotazione dello schermo che specifica una regione di una pagina sulla quale possono essere riprodotti i clip multimediali. |
| [SelectorRendition](./selectorrendition/) | Classe che descrive la rappresentazione del selettore. |
| [SoundAnnotation](./soundannotation/) | Rappresenta un'annotazione sonora che contiene suono registrato dal microfono del computer o importato da un file. |
| [SoundData](./sounddata/) | Rappresenta i dati sonori che definiscono il suono da riprodurre quando l'annotazione è attivata. |
| [SoundSampleData](./soundsampledata/) | Rappresenta voci aggiuntive specifiche per un oggetto sonoro (Sezione 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Classe che rappresenta l'annotazione quadrata. |
| [SquigglyAnnotation](./squigglyannotation/) | Rappresenta l'annotazione ondulata che appare come una sottolineatura frastagliata nel testo di un documento. |
| [StampAnnotation](./stampannotation/) | Rappresenta l'annotazione del timbro di gomma. Questo tipo di annotazione visualizza testo o grafica destinati a sembrare come se fossero stati timbrati sulla pagina con un timbro di gomma. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Rappresenta un'annotazione di barratura che appare come una barratura nel testo del documento. |
| [SubmitFormAction](./submitformaction/) | Classe che descrive l'azione di invio modulo. |
| [TextAnnotation](./textannotation/) | Rappresenta un'annotazione di testo che è un 'sticky note' attaccato a un punto nel documento PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Classe base astratta per le annotazioni di markup del testo. |
| [TextStyle](./textstyle/) | Classe che rappresenta lo stile del testo nell'annotazione |
| [TrimMarkAnnotation](./trimmarkannotation/) | Rappresenta un'annotazione di Trim Mark. |
| [UnderlineAnnotation](./underlineannotation/) | Rappresenta un'annotazione di sottolineatura che appare come una sottolineatura nel testo del documento. |
| [WatermarkAnnotation](./watermarkannotation/) | Classe che descrive l'oggetto annotazione Watermark. |
| [WidgetAnnotation](./widgetannotation/) | Classe che rappresenta l'annotazione widget. |
| [XfdfReader](./xfdfreader/) | Classe che esegue la lettura del formato XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate (sinistra, superiore) posizionate nell'angolo in alto a sinistra della finestra e i contenuti della pagina ingranditi dal fattore di zoom. Un valore nullo per uno qualsiasi dei parametri sinistra, superiore o zoom specifica che il valore attuale di quel parametro deve essere mantenuto invariato. Un valore di zoom di 0 ha lo stesso significato di un valore nullo. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Definisce il Visitor per visitare diverse annotazioni del documento. |
| [IAppointment](./iappointment/) | Rappresenta l'interfaccia generale per azioni e destinazioni. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Un insieme di flag che specificano varie caratteristiche dell'annotazione. |
| [AnnotationState](./annotationstate/) | L'enumerazione degli stati a cui l'annotazione originale può essere impostata. |
| [AnnotationStateModel](./annotationstatemodel/) | Il modello di stato corrispondente allo stato dell'annotazione. |
| [AnnotationType](./annotationtype/) | Enumerazione dei tipi di annotazione. |
| [BorderEffect](./bordereffect/) | Descrive l'effetto che dovrebbe essere applicato al bordo delle annotazioni. |
| [BorderStyle](./borderstyle/) | Descrive lo stile del bordo dell'annotazione. |
| [CapStyle](./capstyle/) | Stile della fine della linea dell'annotazione Ink. |
| [CaptionPosition](./captionposition/) | Enumerazione del posizionamento della didascalia dell'annotazione. |
| [CaretSymbol](./caretsymbol/) | Un simbolo da associare al cursore. |
| [ColorsOfCMYK](./colorsofcmyk/) | Colori inclusi nel modello di colore CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Enumera i tipi di destinazioni esplicite. |
| [FileIcon](./fileicon/) | Un'icona da utilizzare nella visualizzazione dell'annotazione. |
| [FreeTextIntent](./freetextintent/) | Enumera le intenzioni dell'annotazione di testo libero. |
| [HighlightingMode](./highlightingmode/) | Enumera la modalità di evidenziazione dell'annotazione, l'effetto visivo da utilizzare quando il pulsante del mouse è premuto o tenuto premuto all'interno della sua area attiva. |
| [Justification](./justification/) | Enumera le forme di giustificazione da utilizzare nella visualizzazione del testo dell'annotazione. |
| [LaunchActionOperation](./launchactionoperation/) | Enumera le operazioni da eseguire con il documento durante l'esecuzione dell'azione di avvio. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: insieme di tipi di schema di illuminazione. |
| [LineEnding](./lineending/) | Enumera gli stili di fine linea da utilizzare nel disegno della linea. |
| [LineIntent](./lineintent/) | Enumera le intenzioni dell'annotazione di linea. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: insieme di modalità di attivazione delle annotazioni 3D. |
| [PolyIntent](./polyintent/) | Enumera le intenzioni dell'annotazione poligonale o polilinea. |
| [PredefinedAction](./predefinedaction/) | Definisce diverse azioni che possono essere attivate da un file PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Rappresenta una posizione di un marchio in un angolo di una pagina. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Rappresenta una posizione di un marchio di registrazione su una pagina. |
| [PrinterMarksKind](./printermarkskind/) | Specifica i tipi di marchi della stampante da aggiungere a un documento. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: insieme di tipi di modalità di rendering |
| [RenditionOperation](./renditionoperation/) | L'operazione da eseguire quando l'azione viene attivata. |
| [RenditionType](./renditiontype/) | Enumerazione che descrive i possibili tipi di rappresentazione. |
| [ReplyType](./replytype/) | Enumera i tipi di relazioni (il "tipo di risposta") tra l'annotazione e uno specificato da InReplyTo. |
| [SoundEncoding](./soundencoding/) | Il formato di codifica per i dati campione. |
| [SoundIcon](./soundicon/) | Enumera le icone da utilizzare nella visualizzazione dell'annotazione. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Il formato di codifica per i dati campione sonori. |
| [StampIcon](./stampicon/) | Enumera le icone da utilizzare nella visualizzazione dell'annotazione. |
| [TextIcon](./texticon/) | Enumera le icone da utilizzare nella visualizzazione dell'annotazione. |