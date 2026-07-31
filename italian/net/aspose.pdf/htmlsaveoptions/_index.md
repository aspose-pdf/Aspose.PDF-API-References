---
title: "Classe HtmlSaveOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.HtmlSaveOptions. Opzioni di salvataggio per l'esportazione in formato Html"
type: docs
weight: 5690
url: /it/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Opzioni di salvataggio per l'esportazione in formato Html.

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Inizializza una nuova istanza della classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Inizializza una nuova istanza della classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Inizializza una nuova istanza della classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Inizializza una nuova istanza della classe `HtmlSaveOptions`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati sorgente e destinazione. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi dei caratteri saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Ottiene o imposta il flag che indica se le grafiche SVG trovate (se presenti) verranno compresse (zippate) nel formato SVGZ durante il salvataggio |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Se l'attributo ConvertMarkedContentToLayers è impostato su true, tutti gli elementi all'interno di un contenuto marcato PDF (layer) verranno inseriti in un div HTML con l'attributo \"data-pdflayer\" che specifica il nome del layer. Questo nome del layer verrà estratto dalle proprietà opzionali del contenuto marcato PDF. Se questo attributo è false (impostazione predefinita), non verranno creati layer dal contenuto marcato PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Specifica il nome di un font installato che viene usato per sostituire qualsiasi font del documento che non è incorporato e non è installato nel sistema. Se null, viene usato il font di sostituzione predefinito. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Ottiene o imposta il [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Con questa proprietà è possibile definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Cioè, i numeri di pagina validi devono essere presi dall'intervallo (1...[NumberOfPagesInConvertedDocument]). L'ordine di comparsa delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti: nelle pagine risultanti verranno sempre visualizzate nell'ordine in cui sono presenti nel PDF di origine. Se questo elenco è null (come è impostato per impostazione predefinita), verranno convertite tutte le pagine. Se qualche numero di pagina di questo elenco supera l'intervallo delle pagine presenti (1-[amountOfPagesInDocument]), verrà generata un'eccezione. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità di estrazione di immagini o testo per i documenti PDF con sottolivello OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Ottiene o imposta un valore che indica se l'HTML è creato come layout fisso. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Questo attributo specifica il testo del paragrafo a larghezza intera per la modalità Flow, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Origini dei font pre‑salvati. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Il testo con la dimensione specificata o inferiore verrà ignorato durante la conversione. Non rimuoviamo questo testo, lo ignoriamo e non lo trasferiamo nel file di output. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Ottiene o imposta l'indicazione che gli errori relativi all'assenza del font saranno ignorati. true - indica che gli errori di assenza del font saranno ignorati. I segmenti di testo che si riferiscono a risorse errate verranno saltati durante l'elaborazione. false per impostazione predefinita |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Ottiene o imposta la risoluzione per il rendering dell'immagine. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Questo attributo imposta la larghezza minima della linea del percorso grafico. Se lo spessore della linea è inferiore a 1 px, Adobe Acrobat lo arrotonda a questo valore. Pertanto questo attributo può essere usato per emulare questo comportamento nei browser HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Questo attributo attiva la modalità in cui i glifi di testo non verranno raggruppati in parole e stringhe. Questa modalità consente di mantenere la massima precisione durante il posizionamento dei glifi sulla pagina e può essere usata per la conversione di documenti con note musicali o glifi che devono essere posizionati separatamente l'uno dall'altro. Questo parametro verrà applicato al documento solo quando il valore dell'attributo FixedLayout è true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Se l'attributo RenderTextAsImage è impostato su true, il testo della sorgente diventa un'immagine in HTML. Può essere utile per rendere il testo non selezionabile o quando il testo HTML non viene renderizzato correttamente. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Indica che verrà salvato il font completo, supporta solo i font True Type. Per impostazione predefinita SaveFullFont = false e il convertitore salva il sottoinsieme del font iniziale necessario per visualizzare il testo del documento. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Questo attributo specifica un raggruppamento sequenziale di glifi e parole in stringhe. Ad esempio, i tag e le parole hanno ordine diverso nell'HTML convertito e si desidera che corrispondano. Questo parametro verrà applicato al documento solo quando il valore dell'attributo FixedLayout è true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Quando è selezionata la modalità multipagina (ad es. 'SplitIntoPages' è 'true'), questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML risultante. Per impostazione predefinita questo attributo è false, quindi viene creato un unico CSS comune per tutte le pagine generate. La dimensione complessiva di tutti i CSS generati in questa modalità (un CSS per pagina) è solitamente molto superiore alla dimensione di un unico grande file CSS, poiché nel primo caso le classi CSS sono duplicate in diversi file CSS per ciascuna pagina. Pertanto questa impostazione è consigliata solo quando si è interessati all'elaborazione futura di ogni pagina HTML in modo indipendente, e quindi la dimensione del CSS di ciascuna pagina presa singolarmente è il problema più critico. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Ottiene o imposta il flag che indica se ogni pagina del documento di origine verrà convertita nel proprio documento HTML di destinazione, cioè se l'HTML risultante sarà suddiviso in più pagine HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Ottiene o imposta il titolo della pagina HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Il flag per combinare i frammenti di immagine in un'unica immagine. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Se l'attributo UseZORder è impostato su true, le grafiche e il testo vengono aggiunti al documento HTML risultante secondo lo Z-order del documento PDF originale. Se questo attributo è false, tutte le grafiche vengono inserite in un unico livello, il che può causare effetti indesiderati per gli oggetti sovrapposti. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. Continuare è l'azione predefinita e l'operazione di salvataggio prosegue, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di salvataggio deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Questo parametro definisce le misure di antialiasing richieste durante la conversione di immagini di sfondo composte da PDF a HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Quando il convertitore PDFtoHTML genera i CSS risultanti, i nomi delle classi CSS (ad esempio ".stl_01 {}" ... ".stl_NN {}") vengono generati e usati nel CSS di risultato. Questa proprietà consente di impostare forzatamente il prefisso del nome della classe. Per esempio, se si desidera che tutti i nomi delle classi inizino con 'my_prefix_' (cioè siano qualcosa come 'my_prefix_1' ... 'my_prefix_NNN'), basta assegnare 'my_prefix_' a questa proprietà prima della conversione. Se questa proprietà rimane invariata (cioè null viene lasciato come valore), il convertitore genererà i nomi delle classi autonomamente (sarà qualcosa come ".stl_01 {}" ... ".stl_NN {}"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione da Pdf a Html per gestire il salvataggio dei CSS relativi al documento HTML creato nel suo complesso o alle sue pagine (se vengono generate più pagine HTML). Se si desidera gestire il file CSS in modo specifico, è sufficiente creare il metodo pertinente e assegnare il delegato creato a questa proprietà. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Il risultato della conversione può contenere una o più pagine HTML. È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una singola pagina HTML (in modo più preciso – markup HTML, senza file collegati esternamente, se presenti) generata durante la conversione. In tal caso l'elaborazione (come il salvataggio della pagina HTML in stream o su disco) può essere eseguita in quel codice personalizzato. In tal caso tutte le azioni necessarie per il salvataggio della pagina HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se, per qualche motivo, l'elaborazione per questo o quel caso deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato la variabile flag 'CustomProcessingCancelled' del parametro 'htmlSavingInfo': segnalerà al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso, nello stesso modo in cui avverrebbe se non fosse presente alcun codice personalizzato esterno per l'elaborazione. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Questo gestore può essere utilizzato per gestire gli eventi di avanzamento della conversione, ad esempio può servire a mostrare una barra di avanzamento o messaggi sul numero corrente di pagine elaborate; un esempio di codice del gestore che mostra l'avanzamento sulla console è: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione per la gestione personalizzata dei file di risorse creati e referenziati (come immagini e font) correlati ai nodi dell'HTML salvato. Tale strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URL desiderato della risorsa salvata nell'HTML generato. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Questo campo può contenere un metodo personalizzato che restituisce l'URL (o il modello di URL se la generazione multipagina è attiva – vedere i dettagli sotto) del CSS di riferimento da inserire nell'HTML risultato generato. Per esempio, se si desidera che il convertitore inserisca un URL specifico al posto del nome file CSS standard nell'HTML generato, è sufficiente creare e assegnare a questa proprietà un metodo che genera l'URL desiderato. Se il flag 'SplitCssIntoPages' è impostato, allora questa strategia personalizzata (se presente) deve restituire non l'URL esatto del CSS ma una stringa modello che (dopo la sostituzione del segnaposto con il numero di pagina tramite la funzione string.Format() all'interno del convertitore) può essere risolta nell'URL del CSS per quella pagina. Esempi di stringa di ritorno attesa in tal caso sono: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Elenco dei nomi dei font incorporati nel PDF che non devono essere incorporati nell'HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Definisce una regola speciale di codifica per ottimizzare la decodifica PDF per il documento corrente. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Definisce la modalità di salvataggio dei font che verrà utilizzata durante il salvataggio del PDF nel formato desiderato. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | A volte sono presenti requisiti specifici per la generazione del markup HTML. Questo parametro definisce le modalità di preparazione dell'HTML che possono essere utilizzate durante la conversione da PDF a HTML per soddisfare tali requisiti specifici. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in pochi thread. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Imposta la modalità di posizionamento delle lettere nelle parole nell'HTML risultato. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Questo attributo rappresenta un insieme di impostazioni utilizzate per disegnare il bordo (se presente) nel documento HTML risultato attorno all'area che rappresenta la pagina PDF di origine. In sostanza riguarda la visualizzazione dei margini della carta della pagina, non il bordo della pagina referenziato nella pagina PDF stessa. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Questo attributo rappresenta un insieme di margini di pagina aggiuntivi (se presenti) nel documento HTML risultato attorno all'area che rappresenta la pagina PDF di origine. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Se l'attributo 'SplitOnPages=false', l'intero HTML che rappresenta tutte le pagine PDF di input verrà inserito in un unico grande file HTML risultato. Questo flag definisce se l'HTML risultato sarà generato in modo tale che il flusso delle aree che rappresentano le pagine PDF nell'HTML risultato dipenda dalla risoluzione dello schermo del visualizzatore. Supponiamo che la larghezza dello schermo del visualizzatore sia sufficientemente ampia da posizionare 2 o più pagine una accanto all'altra in direzione orizzontale. Se questo flag è impostato su true, allora questa opportunità sarà sfruttata (tante pagine saranno mostrate in orizzontale una accanto all'altra quanto è possibile, poi il prossimo gruppo orizzontale di pagine sarà mostrato sotto il primo). Altrimenti le pagine fluiranno in questo modo: la pagina successiva viene sempre posizionata sotto la precedente. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Definisce se i file di riferimento (HTML, Font, Immagini, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Il PDF convertito può contenere immagini raster. Questo parametro definisce come devono essere gestite durante la conversione da PDF a HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Definisce se nell'HTML creato verranno rimossi gli spazi vuoti superiori e inferiori senza alcun contenuto (se presenti). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | Il PDF può contenere testi che sono coperti da altri elementi (ad es. da immagini) ma possono essere selezionati negli appunti in Acrobat Reader (di solito accade quando il documento contiene immagini e testi OCR estratti). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML risultante per imitare il comportamento di Acrobat Reader (altrimenti tali testi sono solitamente salvati come nascosti, non disponibili per la copia negli appunti). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | Il PDF può contenere testi trasparenti che possono essere selezionati negli appunti (di solito accade quando il documento contiene immagini e testi OCR estratti). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML risultante. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Ottiene o imposta il percorso della directory in cui devono essere salvate tutte le immagini se vengono incontrate durante il salvataggio del documento come HTML. Se il parametro è vuoto o nullo, i file immagine (se presenti) verranno salvati insieme agli altri file collegati all'HTML. Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Ottiene o imposta il percorso della directory in cui devono essere salvati solo i file SVG se vengono incontrati durante il salvataggio del documento come HTML. Se il parametro è vuoto o nullo, i file SVG (se presenti) verranno salvati insieme agli altri file immagine (vicino al file di output) o in una cartella speciale per le immagini (se specificata nell'opzione SpecialImagesFolderIfAny). Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a tasselli identiche posizionate una accanto all'altra. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare l'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità solitamente rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | Il PDF stesso non contiene marcatori di sottolineatura per i testi. Viene emulato con una linea posta sotto il testo. Questa opzione consente al convertitore di provare a indovinare se una linea è la sottolineatura di un testo e inserire queste informazioni nel CSS invece di disegnare la sottolineatura graficamente. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in un file HTML

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Il percorso al tuo file PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// Il percorso al file HTML di output.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inizializza HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Salva il file HTML
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### Vedi anche

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


