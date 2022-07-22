---
title: Document
second_title: Aspose.PDF per .NET API Reference
description: Classe che rappresenta il documento PDF
type: docs
weight: 1870
url: /it/net/aspose.pdf/document/
---
## Document class

Classe che rappresenta il documento PDF

```csharp
public sealed class Document : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Document](document#constructor)() | Inizializza il documento vuoto. |
| [Document](document#constructor_1)(Stream) | Inizializza nuova istanza del documento da*input* flusso. |
| [Document](document#constructor_6)(string) | Inizia semplicemente il documento usando*filename* . Lo stesso di[`Document`](./document) . |
| [Document](document#constructor_3)(Stream, bool) | Inizializza nuova istanza del documento da*input* flusso. |
| [Document](document#constructor_2)(Stream, LoadOptions) | Apre un documento esistente da uno stream fornendo la conversione necessaria per ottenere il documento pdf. |
| [Document](document#constructor_4)(Stream, string) | Inizializza nuova istanza del documento da*input* flusso. |
| [Document](document#constructor_7)(string, LoadOptions) | Apre un documento esistente da un file fornendo le opzioni di conversione necessarie per ottenere il documento pdf. |
| [Document](document#constructor_8)(string, string) | Inizializza la nuova istanza di[`Document`](../document) classe per lavorare con documenti crittografati. |
| [Document](document#constructor_5)(Stream, string, bool) | Inizializza nuova istanza del documento da*input* flusso. |
| [Document](document#constructor_9)(string, string, bool) | Inizializza la nuova istanza di[`Document`](../document) classe per lavorare con documenti crittografati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | Ottiene le azioni del documento. Questa proprietà è un'istanza della classe DocumentActions che permette di ottenere/impostare azioni BeforClosing, BeforSaving, ecc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | Consente di unire i contenuti della pagina per ottimizzare le dimensioni del documento. Se utilizzate, le pagine differnet ma duplicate possono fare riferimento allo stesso oggetto di contenuto . Tieni presente che questa modalità può causare effetti collaterali come la modifica del contenuto della pagina quando viene modificata un'altra pagina. |
| [Background](../../aspose.pdf/document/background) { get; set; } | Ottiene o imposta il colore di sfondo del documento. |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | Ottiene o imposta il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | Ottiene la raccolta di documenti. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | Ottiene le impostazioni di sicurezza se il documento è crittografato. Se il documento non è crittografato, l'eccezione corrispondente verrà sollevata in .net 1.1 o CryptoAlgorithm sarà nullo per altre versioni di .net. |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | Ottiene la raccolta di destinazioni. Obsoleto. Si prega di utilizzare NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | Ottiene o imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | Molte operazioni con font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font. Ad esempio, alcuni font non possono essere incorporati nel documento PDF se le regole di licenza disabilitano l'incorporamento per questo font. Questo flag viene utilizzato per disabilitare qualsiasi restrizione di licenza per tutti i font nel documento PDF corrente. Fai attenzione quando usi questo flag. Quando è impostato significa che la persona che imposta questo flag, si assume tutta la responsabilità di possibili violazioni di licenza/legge su se stesso. Quindi Lui lo assume a proprio rischio. Si consiglia vivamente di utilizzare questo flag solo quando si è completamente sicuri di non violare la legge sul copyright. Per impostazione predefinita false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | Ottiene o imposta il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | Ottiene o imposta l'opzione di gestione della modalità di stampa duplex da utilizzare quando si stampa il file dalla finestra di dialogo di stampa. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | Ottiene la raccolta di file incorporati nel documento. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard con flag IsEmbedded impostato su true. Tutti i font PDF possono essere incorporati nel documento semplicemente impostando il flag IsEmbedded in true, ma i font Type1 standard PDF sono un'eccezione a questa regola. L'incorporamento dei font Type1 standard richiede molto tempo, quindi per incorporare questi font è necessario non solo impostare il flag IsEmbedded in true per il font specificato ma imposta anche un flag aggiuntivo a livello del documento - EmbedStandardFonts = true; Questa proprietà può essere impostata solo una volta per tutti i font. Per impostazione predefinita false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | Ottiene o imposta il flag che consente di scaricare parzialmente il documento dalla memoria. Ciò consente di ridurre l'utilizzo della memoria ma potrebbe avere un effetto negativo sulle prestazioni. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | Ottiene o imposta il flag per gestire la sanificazione dei campi firma. Abilitato per impostazione predefinita. |
| [FileName](../../aspose.pdf/document/filename) { get; } | Nome del file PDF che ha causato questo documento |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | Ottiene o imposta il flag che specifica se la finestra del documento deve essere ridimensionata per adattarla alla prima pagina visualizzata. |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | Istanza IDDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form) { get; } | Ottiene il modulo Acro del documento. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | Genera eccezione se il documento verrà salvato con le modifiche e avrà la firma |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | Ottiene o imposta il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | Ottiene o imposta il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | Ottiene o imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
| [Id](../../aspose.pdf/document/id) { get; } | Ottiene l'ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | Ottiene o imposta il flag di ignoranza degli errori nei file di origine. Quando le pagine dal documento di origine vengono copiate nel documento di destinazione, il processo di copia viene interrotto con l'eccezione se alcuni oggetti nei file di origine sono danneggiati quando questo flag è falso. esempio: dest.Pages.Add(src.Pages); Se questo flag è impostato su true, gli oggetti danneggiati verranno sostituiti con valori vuoti. Per impostazione predefinita: true. |
| [Info](../../aspose.pdf/document/info) { get; } | Ottiene informazioni sul documento. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | Ottiene lo stato crittografato del documento. Vero se il documento è crittografato. |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | Ottiene o imposta un valore che indica se il documento è linearizzato. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | Ottiene il documento è conforme a pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | Ottiene il documento is pdfua compliant. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | Ottiene o imposta il documento è conforme a pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | Raccolta di JavaScript a livello di documento. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | Ottiene la struttura logica del documento. |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | Metadati del documento. (Un documento PDF può includere informazioni generali, come il titolo del documento, l'autore e le date di creazione e modifica. Tali informazioni globali sul documento (al contrario del suo contenuto o struttura) sono chiamate metadati e sono destinato a facilitare la catalogazione e la ricerca di documenti in database esterni.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | Raccolta della destinazione denominata nel documento. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | Ottiene o imposta la modalità pagina, specificando come visualizzare il documento all'uscita dalla modalità a schermo intero. |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | Ottiene o imposta l'azione eseguita all'apertura del documento. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | Ottiene o imposta il flag di ottimizzazione. Quando le pagine vengono aggiunte al documento, flussi di risorse uguali nel file risultante vengono uniti in un oggetto PDF se questo flag è impostato. Ciò consente di ridurre la dimensione del file risultante, ma potrebbe causare un'esecuzione più lenta e requisiti di memoria maggiori. Valore predefinito: false. |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | Ottiene i contorni del documento. |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | Ottiene o imposta le informazioni sulla pagina. (solo per il generatore) |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | Ottiene le etichette di pagina nel documento. |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | Ottiene o imposta il layout di pagina che deve essere utilizzato all'apertura del documento. |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | Ottiene o imposta la modalità pagina, specificando come deve essere visualizzato il documento all'apertura. |
| [Pages](../../aspose.pdf/document/pages) { get; } | Ottiene o imposta la raccolta di pagine del documento. Si noti che le pagine sono numerate da 1 nella raccolta. |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | Ottiene il formato PDF |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | Ottiene le autorizzazioni del documento. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | Ottiene l'accesso al contenuto TaggedPdf. |
| [Version](../../aspose.pdf/document/version) { get; } | Ottiene una versione di Pdf dall'intestazione del file Pdf. |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | Ottiene lo stato della licenza del sistema. Restituisce true se il sistema funziona in modalità con licenza e false in caso contrario. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | Associa xml a document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | Associa xml a document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | Associa xml/xsl a document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | Associa xml/xsl a document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | Associa xml/xsl a document |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | Modifica le password dei documenti. Questa azione può essere eseguita solo utilizzando la password del proprietario. |
| [Check](../../aspose.pdf/document/check)(bool) | Convalida il documento. |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | Converti il documento e salva gli errori nel file specificato. |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | Converti documento utilizzando le opzioni di conversione specificate |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | Converti il documento e salva gli errori nel flusso specificato. |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | Converti il documento e salva gli errori nel file specificato. |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | Converti documento applicando la correzione. |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | Converti documento applicando la correzione. |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Converti il documento e salva gli errori nel file specificato. |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Converti il documento e salva gli errori nel file specificato. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | Converti la pagina in PNG per il flusso di immagini DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt)() | Decrittografa il documento. Chiama quindi Salva per ottenere la versione decrittografata del documento. |
| [Dispose](../../aspose.pdf/document/dispose)() | Chiude tutte le risorse utilizzate da questo documento. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Crittografa il documento. Chiama quindi Salva per ottenere la versione crittografata del documento. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Crittografa il documento. Chiama quindi Salva per ottenere la versione crittografata del documento. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Crittografa il documento. Chiama quindi Salva per ottenere la versione crittografata del documento. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | Esporta tutte le annotazioni del documento nello stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | Esporta tutte le annotazioni del documento nel file XFDF |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | Rimuove tutti i campi dal documento e ne inserisce i valori. |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | Rimuove tutti i campi dal documento e ne inserisce i valori. |
| [FreeMemory](../../aspose.pdf/document/freememory)() | Cancella memoria |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | Restituisce il valore dell'elemento dal dizionario del catalogo. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | Ottiene un oggetto con ID specificato nel documento. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | Ottieni metadati XMP dal documento. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importa le annotazioni dallo stream al documento. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importa le annotazioni dal file XFDF al documento. |
| [Optimize](../../aspose.pdf/document/optimize)() | Linearizza il documento in modo da - apre la prima pagina il più rapidamente possibile; - visualizza la pagina successiva o segui il collegamento alla pagina successiva il più rapidamente possibile; - visualizza la pagina in modo incrementale così come arriva quando i dati di una pagina vengono consegnati su un canale lento (visualizza prima i dati più utili); - consente di eseguire l'interazione dell'utente, come seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata. Invocare questo metodo in realtà non salva il documento . Al contrario, solo il documento è preparato per avere una struttura ottimizzata, chiama quindi Salva per ottenere il documento ottimizzato. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | Ottimizza le risorse nel documento: 1. Le risorse non utilizzate nelle pagine del documento vengono rimosse; 2. Le risorse uguali vengono unite in un unico oggetto; 3. Gli oggetti non utilizzati vengono eliminati. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | Ottimizza le risorse nel documento in base alla strategia di ottimizzazione definita. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | Paragrafi di processo per generatore. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | Rimuove i metadati dal documento. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | Rimuovere la conformità pdfa dal documento |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | Rimuovere la conformità pdfUa dal documento |
| [Repair](../../aspose.pdf/document/repair)() | Ripara il documento danneggiato. |
| [Save](../../aspose.pdf/document/save#save)() | Salva il documento in modo incrementale (ovvero utilizzando la tecnica di aggiornamento incrementale). |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | Salva il documento con le opzioni di salvataggio. |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | Memorizza il documento nello stream. |
| [Save](../../aspose.pdf/document/save#save_5)(string) | Salva il documento nel file specificato. |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | Salva il documento con un nuovo nome insieme a un formato file. |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | Salva il documento in uno stream con opzioni di salvataggio. |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | Salva il documento con un nuovo nome insieme a un formato file. |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | Salva il documento con un nuovo nome impostandone le opzioni di salvataggio. |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | Salva il documento in un flusso di risposta con opzioni di salvataggio. |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | Salva documento in XML. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | Invia l'intero documento al dispositivo documenti per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | Invia l'intero documento al dispositivo documenti per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | Invia determinate pagine del documento al dispositivo documenti per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | Invia l'intero documento al dispositivo documenti per l'elaborazione. |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | Imposta titolo per documento PDF |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | Imposta i metadati XMP del documento. |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | Convalida il documento nel file specificato. |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | Convalida il documento nel file specificato. |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | Convalida il documento nel file specificato. |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | Converte lo stream nel formato sorgente in stream nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | Converte il flusso nel formato di origine nel file di destinazione nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | Converte il file di origine nel formato di origine nel flusso nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | Converte il file di origine nel formato di origine nel file di destinazione nel formato di destinazione. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | La procedura di richiamata per riconoscimento hocr. |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | Rappresenta il metodo che gestirà l'evento FontSubstitution. |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | Mantiene la funzionalità per ottimizzare i caratteri |

### Guarda anche

* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
