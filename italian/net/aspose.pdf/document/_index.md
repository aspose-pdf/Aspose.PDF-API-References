---
title: "Classe Document"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Document. Classe che rappresenta un documento PDF"
type: docs
weight: 3900
url: /it/net/aspose.pdf/document/
---
## Document class

Classe che rappresenta il documento PDF.

```csharp
public sealed class Document : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Document](document/#constructor)() | Inizializza un documento vuoto. |
| [Document](document/#constructor_1)(PdfVersion) | Inizializza un documento vuoto per versione. |
| [Document](document/#constructor_2)(Stream) | Inizializza una nuova istanza di Document dallo stream *input*. |
| [Document](document/#constructor_11)(string) | Inizializza semplicemente Document usando *filename*. Lo stesso di [`Document`](./document/). |
| [Document](document/#constructor_6)(Stream, bool) | Inizializza una nuova istanza di Document dallo stream *input*. |
| [Document](document/#constructor_4)(Stream, CertificateEncryptionOptions) | Inizializza una nuova istanza di Document dallo stream *input*. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Apre un documento esistente da uno stream fornendo la conversione necessaria per ottenere un documento pdf. |
| [Document](document/#constructor_7)(Stream, string) | Inizializza una nuova istanza di Document dallo stream *input*. |
| [Document](document/#constructor_15)(string, bool) | Inizializza semplicemente Document usando *filename*. Lo stesso di [`Document`](./document/). |
| [Document](document/#constructor_13)(string, CertificateEncryptionOptions) | Inizializza una nuova istanza della classe `Document` per lavorare con un documento crittografato. |
| [Document](document/#constructor_12)(string, LoadOptions) | Apre un documento esistente da un file fornendo le opzioni di conversione necessarie per ottenere un documento pdf. |
| [Document](document/#constructor_16)(string, string) | Inizializza una nuova istanza della classe `Document` per lavorare con un documento crittografato. |
| [Document](document/#constructor_5)(Stream, CertificateEncryptionOptions, bool) | Inizializza una nuova istanza di Document dallo stream *input*. |
| [Document](document/#constructor_9)(Stream, string, bool) | Inizializza una nuova istanza di Document dallo stream *input*. |
| [Document](document/#constructor_8)(Stream, string, ICustomSecurityHandler) | Inizializza una nuova istanza di Document dallo stream *input*. |
| [Document](document/#constructor_14)(string, CertificateEncryptionOptions, bool) | Inizializza una nuova istanza della classe `Document` per lavorare con un documento crittografato. |
| [Document](document/#constructor_18)(string, string, bool) | Inizializza una nuova istanza della classe `Document` per lavorare con un documento crittografato. |
| [Document](document/#constructor_17)(string, string, ICustomSecurityHandler) | Inizializza una nuova istanza della classe `Document` per lavorare con un documento crittografato. |
| [Document](document/#constructor_10)(Stream, string, bool, ICustomSecurityHandler) | Inizializza una nuova istanza di Document dallo stream *input*. |
| [Document](document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | Inizializza una nuova istanza della classe `Document` per lavorare con un documento crittografato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Ottiene le azioni del documento. Questa proprietà è un'istanza della classe DocumentActions che consente di ottenere/impostare le azioni BeforClosing, BeforSaving, ecc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Consente di unire i contenuti delle pagine per ottimizzare le dimensioni del documento. Se usato, pagine diverse ma duplicate possono fare riferimento allo stesso oggetto di contenuto. Si noti che questa modalità può causare effetti collaterali, come la modifica del contenuto di una pagina quando un'altra pagina viene modificata. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Ottiene o imposta il colore di sfondo del documento. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Ottiene o imposta il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Ottiene la raccolta del documento. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Ottiene le impostazioni di sicurezza se il documento è crittografato. Se il documento non è crittografato, verrà sollevata l'eccezione corrispondente in .net 1.1 o CryptoAlgorithm sarà null per le altre versioni .net. |
| [CustomSecurityHandler](../../aspose.pdf/document/customsecurityhandler/) { get; } | Ottiene un gestore di sicurezza personalizzato. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Ottiene la raccolta delle destinazioni. Obsoleta. Si prega di usare NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Ottiene o imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Molte operazioni con il carattere non possono essere eseguite se queste operazioni sono proibite dalla licenza di questo carattere. Per esempio alcuni caratteri non possono essere incorporati in un documento PDF se le regole della licenza disabilitano l'incorporamento per quel carattere. Questa flag è usata per disabilitare qualsiasi restrizione di licenza per tutti i caratteri nel documento PDF corrente. Fare attenzione quando si utilizza questa flag. Quando è impostata significa che la persona che la imposta si assume tutta la responsabilità di possibili violazioni di licenza/legge. Quindi lo fa a proprio rischio. È fortemente consigliato usare questa flag solo quando si è completamente certi di non violare la legge sul diritto d'autore. Per impostazione predefinita false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Ottiene o imposta la flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Ottiene o imposta l'opzione di gestione della modalità duplex di stampa da utilizzare quando si stampa il file dalla finestra di dialogo di stampa. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Ottiene la raccolta di file incorporati nel documento. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Proprietà che dichiara che il documento deve incorporare tutti i caratteri Type1 standard per i quali la flag IsEmbedded è impostata su true. Tutti i caratteri PDF possono essere incorporati nel documento semplicemente impostando la flag IsEmbedded su true, ma i caratteri PDF standard Type1 sono un'eccezione a questa regola. L'incorporamento dei caratteri Type1 standard richiede molto tempo, quindi per incorporare questi caratteri è necessario non solo impostare la flag IsEmbedded su true per il carattere specificato, ma anche impostare una flag aggiuntiva a livello di documento - EmbedStandardFonts = true; Questa proprietà può essere impostata una sola volta per tutti i caratteri. Per impostazione predefinita false. |
| [EnableNotificationLogging](../../aspose.pdf/document/enablenotificationlogging/) { get; set; } | Ottiene o imposta un valore che indica se abilitare la registrazione delle notifiche. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Ottiene o imposta la flag che consente al documento di essere parzialmente scaricato dalla memoria. Questo permette di ridurre l'uso della memoria ma può avere un effetto negativo sulle prestazioni. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Ottiene o imposta la flag per gestire la sanitizzazione dei campi firma. Abilitata per impostazione predefinita. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Nome del file PDF che ha causato questo documento. |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Ottiene o imposta la flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Istanza di IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Ottiene il modulo Acro Form del documento. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Genera un'eccezione se il documento viene salvato con modifiche e contiene una firma. |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Ottiene o imposta la flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Ottiene o imposta la flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Ottiene o imposta la flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
| [Id](../../aspose.pdf/document/id/) { get; } | Ottiene l'ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Ottiene o imposta la flag per ignorare gli errori nei file di origine. Quando le pagine dal documento di origine vengono copiate nel documento di destinazione, il processo di copia si interrompe con un'eccezione se alcuni oggetti nei file di origine sono corrotti quando questa flag è false. esempio: dest.Pages.Add(src.Pages); Se questa flag è impostata su true, gli oggetti corrotti verranno sostituiti con valori vuoti. Per impostazione predefinita: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Ottiene le informazioni del documento. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Ottiene lo stato di crittografia del documento. True se il documento è crittografato. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Ottiene o imposta un valore che indica se il documento è linearizzato. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Ottiene se il documento è conforme a pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Ottiene se il documento è conforme a pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Ottiene o imposta se il documento è conforme a pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Raccolta di JavaScript a livello di documento. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Ottiene la struttura logica del documento. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Metadati del Document. (Un documento PDF può includere informazioni generali, come il titolo del documento, l'autore e le date di creazione e modifica. Tali informazioni globali sul documento (a differenza del suo contenuto o della sua struttura) sono chiamate metadati e sono destinate ad assistere nella catalogazione e nella ricerca di documenti in database esterni.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Raccolta di Named Destination nel documento. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Ottiene o imposta la modalità pagina, specificando come visualizzare il documento all'uscita dalla modalità a schermo intero. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Ottiene o imposta l'azione eseguita all'apertura del documento. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Ottiene o imposta il flag di ottimizzazione. Quando le pagine vengono aggiunte al documento, i flussi di risorse uguali nel file risultante vengono uniti in un unico oggetto PDF se questo flag è impostato. Ciò consente di ridurre la dimensione del file risultante ma può causare un'esecuzione più lenta e requisiti di memoria maggiori. Valore predefinito: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Ottiene gli outline del documento. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Ottiene la raccolta di Output intents nel documento. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Ottiene o imposta le informazioni della pagina. (solo per il generatore, non compilato durante la lettura del documento) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Ottiene le etichette delle pagine nel documento. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Ottiene o imposta il layout della pagina che deve essere usato quando il documento viene aperto. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Ottiene o imposta la modalità pagina, specificando come il documento deve essere visualizzato all'apertura. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Ottiene o imposta la raccolta di pagine del documento. Nota che le pagine sono numerate a partire da 1 nella raccolta. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Ottiene il formato PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Ottiene i permessi del documento. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Ottiene o imposta un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Ottiene o imposta l'opzione di scaling della pagina che deve essere selezionata quando viene visualizzata una finestra di stampa per questo documento. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Ottiene l'accesso al contenuto TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Ottiene una versione di Pdf dall'intestazione del file Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Ottieni e imposta il limite di dimensione del file per caricare un intero file in memoria. Il valore è impostato in megabyte. Il valore predefinito è 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Ottiene lo stato con licenza del sistema. Restituisce true se il sistema funziona in modalità con licenza e false altrimenti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Unisce i documenti. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Unisce i file pdf. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Unisce i documenti. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Unisce i documenti. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Associa xml al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Associa xml al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Associa xml/xsl al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Associa xml/xsl al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Associa xml/xsl al documento |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Modifica le password del documento. Questa operazione può essere eseguita solo usando la password del proprietario. |
| [Check](../../aspose.pdf/document/check/)(bool) | Convalida il documento. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Converti il documento usando le opzioni di conversione specificate |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Riconosci le immagini all'interno del documento e aggiungi le stringhe hocr sopra di esse. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Riconosci le immagini all'interno del documento e aggiungi le stringhe hocr sopra di esse. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Converti il documento e salva gli errori nello stream specificato. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Converti il documento e salva gli errori nel file specificato. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Converti il documento applicando il Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Converti il documento applicando il Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Converti il documento e salva gli errori nel file specificato. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Converti il documento e salva gli errori nel file specificato. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Converti la pagina in PNG per lo stream di immagini DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Decripta il documento. Chiama poi Save per ottenere la versione decrittata del documento. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Chiude tutte le risorse utilizzate da questo documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) | Cripta il documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, DocumentPrivilege, ICustomSecurityHandler) | Cripta il documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_3)(string, string, Permissions, CryptoAlgorithm) | Cripta il documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_5)(string, string, Permissions, ICustomSecurityHandler) | Cripta il documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Cripta il documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_4)(string, string, Permissions, CryptoAlgorithm, bool) | Cripta il documento. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Esporta tutte le annotazioni del documento nello stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Esporta tutte le annotazioni del documento in un file XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Rimuove tutti i campi dal documento e ne inserisce i valori al loro posto. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Rimuove tutti i campi (e le annotazioni) dal documento e ne inserisce i valori al loro posto. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Sostituisce il contenuto trasparente con grafica raster e vettoriale non trasparente. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Cancella la memoria |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Restituisce il valore dell'elemento dal dizionario del catalogo. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Ottiene un oggetto con ID specificato nel documento. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Ottieni i metadati XMP dal documento. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Verifica se il PDF corrente è stato salvato con aggiornamenti incrementali. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importa le annotazioni dallo stream al documento. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importa le annotazioni da un file XFDF al documento. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Verifica se il documento richiede la chiamata al metodo Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Carica un file, convertendolo in PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Unisce i documenti. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Unisce i file pdf. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Unisce i documenti. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Unisce i documenti. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linearizzare il documento per - aprire la prima pagina il più rapidamente possibile; - visualizzare la pagina successiva o seguire il collegamento alla pagina successiva il più rapidamente possibile; - visualizzare la pagina in modo incrementale man mano che arriva quando i dati per una pagina vengono consegnati su un canale lento (visualizzare prima i dati più utili); - consentire l'interazione dell'utente, come seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata. L'invocazione di questo metodo non salva effettivamente il documento. Al contrario, il documento viene solo preparato per avere una struttura ottimizzata; chiamare quindi Save per ottenere il documento ottimizzato. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Ottimizza le risorse nel documento: 1. Le risorse che non sono utilizzate nelle pagine del documento vengono rimosse; 2. Le risorse uguali vengono unite in un unico oggetto; 3. Gli oggetti non utilizzati vengono eliminati. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Ottimizza le risorse nel documento secondo la strategia di ottimizzazione definita. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato. Solo se il documento ha più di nodesNumInSubtrees oggetti pagina, altrimenti non fa nulla. Non chiamare questo metodo durante l'iterazione sugli elementi Pages, potrebbe dare risultati imprevedibili. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Elabora i paragrafi per il generatore. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Rimuove i metadati dal documento. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Rimuovi la conformità pdfa dal documento. |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Rimuovi la conformità pdfUa dal documento. |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Ripara il documento danneggiato. |
| [Save](../../aspose.pdf/document/save/#save)() | Salva il documento in modo incrementale (cioè utilizzando la tecnica di aggiornamento incrementale). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Salva il documento con le opzioni di salvataggio. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Memorizza il documento in uno stream. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Salva il documento nel file specificato. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Salva il documento con un nuovo nome insieme a un formato file. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Salva il documento in uno stream con le opzioni di salvataggio. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Salva il documento con un nuovo nome insieme a un formato file. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Salva il documento in modo incrementale (cioè utilizzando la tecnica di aggiornamento incrementale). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Salva il documento con le opzioni di salvataggio. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Memorizza il documento in uno stream. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Salva il documento nel file specificato. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Salva il documento con un nuovo nome insieme a un formato file. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Salva il documento in uno stream con le opzioni di salvataggio. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Salva il documento con un nuovo nome insieme a un formato file. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Salva il documento in XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Invia l'intero documento al dispositivo documento per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Invia l'intero documento al dispositivo documento per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Invia le pagine specifiche del documento al dispositivo documento per l'elaborazione. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Invia l'intero documento al dispositivo documento per l'elaborazione. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Imposta il titolo per Pdf Document. |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Imposta i metadati XMP del documento. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Convalida il documento nel file specificato. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Convalida il documento nel file specificato. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Convalida il documento nel file specificato. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Converte lo stream nel formato sorgente in uno stream nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Converte lo stream nel formato sorgente in un file di destinazione nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Converte il file sorgente nel formato sorgente in uno stream nel formato di destinazione. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Converte il file di origine nel formato di origine in un file di destinazione nel formato di destinazione. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Imposta il limite di dimensione del file per caricare un intero file in memoria al valore predefinito pari a 210 Mb. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Si verifica quando un carattere sostituisce un altro carattere nel documento. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Rappresenta il metodo che gestirà l'evento FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Contiene funzionalità per regolare i caratteri. |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Rappresenta le opzioni per i metodi Merge. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Rappresenta le opzioni per la riparazione di un documento PDF. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


