---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Document. Classe che rappresenta un documento PDF
type: docs
weight: 3780
url: /it/net/aspose.pdf/document/
---
## Classe Documento

Classe che rappresenta un documento PDF.

```csharp
public sealed class Document : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Document](document/#constructor)() | Inizializza un documento vuoto. |
| [Document](document/#constructor_1)(PdfVersion) | Inizializza un documento vuoto per versione. |
| [Document](document/#constructor_2)(Stream) | Inizializza una nuova istanza di Document dal *flusso* di input. |
| [Document](document/#constructor_7)(string) | Inizializza Document utilizzando *nome file*. Lo stesso di [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | Inizializza una nuova istanza di Document dal *flusso* di input. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Apre un documento esistente da un flusso fornendo la conversione necessaria per ottenere un documento pdf. |
| [Document](document/#constructor_5)(Stream, string) | Inizializza una nuova istanza di Document dal *flusso* di input. |
| [Document](document/#constructor_9)(string, bool) | Inizializza Document utilizzando *nome file*. Lo stesso di [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | Apre un documento esistente da un file fornendo le opzioni di conversione necessarie per ottenere un documento pdf. |
| [Document](document/#constructor_10)(string, string) | Inizializza una nuova istanza della classe `Document` per lavorare con documenti crittografati. |
| [Document](document/#constructor_6)(Stream, string, bool) | Inizializza una nuova istanza di Document dal *flusso* di input. |
| [Document](document/#constructor_11)(string, string, bool) | Inizializza una nuova istanza della classe `Document` per lavorare con documenti crittografati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Ottiene le azioni del documento. Questa proprietà è un'istanza della classe DocumentActions che consente di ottenere/impostare azioni BeforClosing, BeforSaving, ecc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Consente di unire i contenuti delle pagine per ottimizzare la dimensione del documento. Se utilizzato, pagine diverse ma duplicate possono fare riferimento allo stesso oggetto di contenuto. Si prega di notare che questa modalità può causare effetti collaterali come la modifica del contenuto della pagina quando un'altra pagina viene modificata. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Ottiene o imposta il colore di sfondo del documento. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Ottiene o imposta un flag che specifica se la posizione della finestra del documento deve essere centrata sullo schermo. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Ottiene la collezione del documento. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Ottiene le impostazioni di sicurezza se il documento è crittografato. Se il documento non è crittografato, verrà sollevata l'eccezione corrispondente in .net 1.1 o CryptoAlgorithm sarà nullo per altre versioni di .net. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Ottiene la collezione di destinazioni. Obsoleto. Si prega di utilizzare NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Ottiene o imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Molte operazioni con i font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font. Ad esempio, alcuni font non possono essere incorporati in un documento PDF se le regole di licenza disabilitano l'incorporamento per questo font. Questo flag viene utilizzato per disabilitare eventuali restrizioni di licenza per tutti i font nel documento PDF corrente. Fare attenzione quando si utilizza questo flag. Quando è impostato, significa che la persona che imposta questo flag si assume tutta la responsabilità di eventuali violazioni di licenza/legge. Quindi lo fa a proprio rischio. Si raccomanda vivamente di utilizzare questo flag solo quando si è completamente certi di non violare la legge sul copyright. Di default è falso. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Ottiene o imposta un flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Ottiene o imposta l'opzione di gestione della modalità di stampa duplex da utilizzare quando si stampa il file dalla finestra di dialogo di stampa. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Ottiene la collezione di file incorporati nel documento. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Proprietà che dichiara che il documento deve incorporare tutti i font standard Type1 che hanno il flag IsEmbedded impostato su true. Tutti i font PDF possono essere incorporati nel documento semplicemente impostando il flag IsEmbedded su true, ma i font standard Type1 PDF sono un'eccezione a questa regola. L'incorporamento dei font standard Type1 richiede molto tempo, quindi per incorporare questi font è necessario non solo impostare il flag IsEmbedded su true per il font specificato, ma anche impostare un flag aggiuntivo a livello di documento - EmbedStandardFonts = true; Questa proprietà può essere impostata solo una volta per tutti i font. Di default è falso. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Ottiene o imposta un flag che consente al documento di essere parzialmente scaricato dalla memoria. Questo consente di ridurre l'uso della memoria, ma può avere un effetto negativo sulle prestazioni. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Ottiene o imposta un flag per gestire la sanificazione dei campi di firma. Abilitato per impostazione predefinita. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Nome del file PDF che ha causato questo documento |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Ottiene o imposta un flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Istanza di IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Ottiene l'Acro Form del documento. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Solleva un'eccezione se il documento verrà salvato con modifiche e ha una firma |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Ottiene o imposta un flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Ottiene o imposta un flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Ottiene o imposta un flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
| [Id](../../aspose.pdf/document/id/) { get; } | Ottiene l'ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Ottiene o imposta un flag per ignorare gli errori nei file sorgente. Quando le pagine del documento sorgente vengono copiate nel documento di destinazione, il processo di copia si interrompe con un'eccezione se alcuni oggetti nei file sorgente sono corrotti quando questo flag è falso. esempio: dest.Pages.Add(src.Pages); Se questo flag è impostato su true, gli oggetti corrotti verranno sostituiti con valori vuoti. Di default: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Ottiene le informazioni del documento. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Ottiene lo stato crittografato del documento. Vero se il documento è crittografato. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Ottiene o imposta un valore che indica se il documento è linearizzato. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Ottiene se il documento è conforme a pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Ottiene se il documento è conforme a pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Ottiene o imposta se il documento è conforme a pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Collezione di JavaScript a livello di documento. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Ottiene la struttura logica del documento. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Metadati del documento. (Un documento PDF può includere informazioni generali, come il titolo del documento, l'autore e le date di creazione e modifica. Tali informazioni globali sul documento (a differenza del suo contenuto o della sua struttura) sono chiamate metadati e sono destinate ad assistere nella catalogazione e nella ricerca di documenti in database esterni.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Collezione di Destinazioni Nominate nel documento. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Ottiene o imposta la modalità pagina, specificando come visualizzare il documento all'uscita dalla modalità a schermo intero. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Ottiene o imposta l'azione eseguita all'apertura del documento. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Ottiene o imposta il flag di ottimizzazione. Quando le pagine vengono aggiunte al documento, flussi di risorse uguali nel file risultante vengono uniti in un oggetto PDF se questo flag è impostato. Questo consente di ridurre la dimensione del file risultante, ma può causare un'esecuzione più lenta e maggiori requisiti di memoria. Valore predefinito: falso. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Ottiene le outline del documento. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Ottiene la collezione di Output intents nel documento. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Ottiene o imposta le informazioni sulla pagina. (solo per il generatore, non compilato durante la lettura del documento) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Ottiene le etichette delle pagine nel documento. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Ottiene o imposta il layout della pagina che deve essere utilizzato quando il documento viene aperto. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Ottiene o imposta la modalità pagina, specificando come il documento deve essere visualizzato quando aperto. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Ottiene o imposta la collezione delle pagine del documento. Nota che le pagine sono numerate da 1 nella collezione. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Ottiene il formato PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Ottiene i permessi del documento. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Ottiene o imposta un flag che specifica se la dimensione della pagina PDF deve essere utilizzata per selezionare il vassoio di carta di input. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Ottiene o imposta l'opzione di scaling della pagina che deve essere selezionata quando viene visualizzata una finestra di dialogo di stampa per questo documento. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Ottiene accesso al contenuto TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Ottiene una versione di Pdf dall'intestazione del file Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Ottiene e imposta il limite di dimensione del file per il caricamento di un intero file in memoria. Il valore è impostato in megabyte. Il valore predefinito è 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Ottiene lo stato di licenza del sistema. Restituisce vero se il sistema funziona in modalità licenziata e falso altrimenti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Unisce documenti. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Unisce file pdf. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Unisce documenti. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Unisce documenti. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Collega xml al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Collega xml al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Collega xml/xsl al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Collega xml/xsl al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Collega xml/xsl al documento |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Cambia le password del documento. Questa azione può essere eseguita solo utilizzando la password del proprietario. |
| [Check](../../aspose.pdf/document/check/)(bool) | Valida il documento. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Converte il documento utilizzando le opzioni di conversione specificate |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Riconosce le immagini all'interno del documento e aggiunge stringhe hocr sopra di esse. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Riconosce le immagini all'interno del documento e aggiunge stringhe hocr sopra di esse. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Converte il documento e salva gli errori nel flusso specificato. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Converte il documento e salva gli errori nel file specificato. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Converte il documento applicando il Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Converte il documento applicando il Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Converte il documento e salva gli errori nel file specificato. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Converte il documento e salva gli errori nel file specificato. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Converte la pagina in PNG per DSR, OMR, flusso di immagini OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Decrittografa il documento. Chiama poi Salva per ottenere la versione decrittografata del documento. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Chiude tutte le risorse utilizzate da questo documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Crittografa il documento. Chiama poi Salva per ottenere la versione crittografata del documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Crittografa il documento. Chiama poi Salva per ottenere la versione crittografata del documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Crittografa il documento. Chiama poi Salva per ottenere la versione crittografata del documento. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Esporta tutte le annotazioni del documento nel flusso. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Esporta tutte le annotazioni del documento in un file XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Rimuove tutti i campi dal documento e inserisce i loro valori al posto. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Rimuove tutti i campi (e annotazioni) dal documento e inserisce i loro valori al posto. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Sostituisce il contenuto trasparente con grafica raster e vettoriale non trasparente. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Pulisce la memoria |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Restituisce il valore dell'elemento dal dizionario del catalogo. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Ottiene un oggetto con ID specificato nel documento. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Ottiene i metadati XMP dal documento. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Controlla se il documento PDF corrente è stato salvato con aggiornamenti incrementali. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importa annotazioni dal flusso al documento. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importa annotazioni da un file XFDF al documento. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Controlla se il documento richiede la chiamata al metodo Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Carica un file, convertendolo in PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Unisce documenti. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Unisce file pdf. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Unisce documenti. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Unisce documenti. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linearizza il documento per - aprire la prima pagina il più rapidamente possibile; - visualizzare la pagina successiva o seguire un link alla pagina successiva il più rapidamente possibile; - visualizzare la pagina in modo incrementale man mano che arriva quando i dati per una pagina vengono consegnati su un canale lento (visualizzare prima i dati più utili); - consentire l'interazione dell'utente, come seguire un link, da eseguire anche prima che l'intera pagina sia stata ricevuta e visualizzata. Invocare questo metodo non salva effettivamente il documento. Al contrario, il documento è solo preparato per avere una struttura ottimizzata, chiama poi Salva per ottenere un documento ottimizzato. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Ottimizza le risorse nel documento: 1. Le risorse che non sono utilizzate nelle pagine del documento vengono rimosse; 2. Risorse uguali vengono unite in un oggetto; 3. Gli oggetti non utilizzati vengono eliminati. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Ottimizza le risorse nel documento secondo la strategia di ottimizzazione definita. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato. Solo se il documento ha più di nodesNumInSubtrees oggetti pagina, altrimenti non fa nulla. Non chiamare questo metodo mentre si itera sugli elementi Pages, potrebbe dare risultati imprevedibili |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Elabora i paragrafi per il generatore. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Rimuove i metadati dal documento. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Rimuove la conformità pdfa dal documento |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Rimuove la conformità pdfUa dal documento |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Ripara il documento danneggiato. |
| [Save](../../aspose.pdf/document/save/#save)() | Salva il documento in modo incrementale (cioè utilizzando la tecnica di aggiornamento incrementale). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Salva il documento con opzioni di salvataggio. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Memorizza il documento nel flusso. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Salva il documento nel file specificato. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Salva il documento con un nuovo nome insieme a un formato file. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Salva il documento in un flusso con opzioni di salvataggio. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Salva il documento con un nuovo nome insieme a un formato file. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Salva il documento in modo incrementale (cioè utilizzando la tecnica di aggiornamento incrementale). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Salva il documento con opzioni di salvataggio. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Memorizza il documento nel flusso. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Salva il documento nel file specificato. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Salva il documento con un nuovo nome insieme a un formato file. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Salva il documento in un flusso con opzioni di salvataggio. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Salva il documento con un nuovo nome insieme a un formato file. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Salva il documento in XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Invia l'intero documento al dispositivo documento per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Invia l'intero documento al dispositivo documento per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Invia le pagine specifiche del documento al dispositivo documento per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Invia l'intero documento al dispositivo documento per l'elaborazione. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Imposta il titolo per il documento Pdf |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Imposta i metadati XMP del documento. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Valida il documento nel file specificato. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Valida il documento nel file specificato. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Valida il documento nel file specificato. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Converte il flusso nel formato sorgente in un flusso nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Converte il flusso nel formato sorgente in un file di destinazione nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Converte il file sorgente nel formato sorgente in un flusso nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Converte il file sorgente nel formato sorgente in un file di destinazione nel formato di destinazione. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Imposta il limite di dimensione del file per il caricamento di un intero file in memoria al valore predefinito pari a 210 Mb. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Si verifica quando un font sostituisce un altro font nel documento. |

## Altri Membri

| Nome | Descrizione |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Rappresenta il metodo che gestirà l'evento FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Contiene funzionalità per regolare i font |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Rappresenta le opzioni per i metodi di unione. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Rappresenta le opzioni per riparare un documento PDF. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)