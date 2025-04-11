---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlSaveOptions. Opzioni di salvataggio per l'esportazione in formato Html
type: docs
weight: 5560
url: /it/net/aspose.pdf/htmlsaveoptions/
---
## Classe HtmlSaveOptions

Opzioni di salvataggio per l'esportazione in formato Html

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
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Definisce la dimensione del batch se la conversione in batch è applicabile alla coppia di formati sorgente e destinazione. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi del font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione da pdf ad altri formati, ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Ottiene o imposta il flag che indica se le grafiche SVG trovate (se presenti) saranno compresse (zippate) in formato SVGZ durante il salvataggio |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Se l'attributo ConvertMarkedContentToLayers è impostato su true, allora tutti gli elementi all'interno di un contenuto contrassegnato PDF (layer) saranno inseriti in un div HTML con l'attributo "data-pdflayer" che specifica un nome di layer. Questo nome di layer sarà estratto dalle proprietà opzionali del contenuto contrassegnato PDF. Se questo attributo è false (per impostazione predefinita), non verranno creati layer dal contenuto contrassegnato PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Specifica il nome di un font installato che viene utilizzato per sostituire qualsiasi font del documento che non è incorporato e non è installato nel sistema. Se null, verrà utilizzato il font di sostituzione predefinito. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Ottiene o imposta il [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Con questa proprietà puoi definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Ad esempio, i numeri validi delle pagine devono essere presi dall'intervallo (1...[NumberOfPagesInConvertedDocument]) L'ordine di apparizione delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti: nelle pagine risultanti andranno sempre nell'ordine in cui sono presenti nel PDF sorgente. Se questo elenco è null (come è per impostazione predefinita), tutte le pagine saranno convertite. Se un numero di pagina di questo elenco esce dall'intervallo delle pagine presenti (1-[amountOfPagesInDocument]), verrà sollevata un'eccezione. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità per estrarre immagini o testo per documenti PDF con sottolayer OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Ottiene o imposta un valore che indica se l'HTML è creato come layout fisso. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Questo attributo specifica il testo del paragrafo a larghezza piena per la modalità Flow, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Fonti dei font pre-salvati. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Il testo con la dimensione specificata o inferiore sarà ignorato durante la conversione. Non rimuoviamo questo testo, lo ignoriamo e non lo trasferiamo nel file di output |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true - significa che gli errori di assenza di font saranno ignorati. I segmenti di testo che si riferiscono a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Ottiene o imposta la risoluzione per il rendering delle immagini. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Questo attributo imposta la larghezza minima della linea del percorso grafico. Se lo spessore della linea è inferiore a 1px, Adobe Acrobat lo arrotonda a questo valore. Quindi, questo attributo può essere utilizzato per emulare questo comportamento per i browser HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Questo attributo attiva la modalità in cui i glifi di testo non saranno raggruppati in parole e stringhe. Questa modalità consente di mantenere la massima precisione durante il posizionamento dei glifi sulla pagina e può essere utilizzata per la conversione di documenti con note musicali o glifi che devono essere posizionati separatamente l'uno dall'altro. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Se l'attributo RenderTextAsImage è impostato su true, il testo dalla sorgente diventa un'immagine in HTML. Può essere utile per rendere il testo non selezionabile o se il testo HTML non viene renderizzato correttamente. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Indica che il font completo sarà salvato, supporta solo i font True Type. Per impostazione predefinita, SaveFullFont = false e il convertitore salva il sottoinsieme del font iniziale necessario per visualizzare il testo del documento. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Questo attributo specifica un raggruppamento sequenziale di glifi e parole in stringhe. Ad esempio, i tag e le parole hanno un ordine diverso nell'HTML convertito e si desidera che corrispondano. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Quando è selezionata la modalità multipagina (cioè 'SplitIntoPages' è 'true'), questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML risultante. Per impostazione predefinita, questo attributo è false, quindi verrà creato un grande CSS comune per tutte le pagine create. La dimensione complessiva di tutti i CSS generati in questa modalità (un CSS per pagina) è solitamente molto maggiore della dimensione di un grande file CSS, perché nel primo caso le classi CSS sono duplicate in diversi file CSS per ogni pagina. Quindi, questa impostazione è peggiore da utilizzare solo quando sei interessato a un'elaborazione futura di ciascuna pagina HTML in modo indipendente, e quindi la dimensione del CSS di ciascuna pagina presa separatamente è la questione più critica. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Ottiene o imposta il flag che indica se ogni pagina del documento sorgente sarà convertita nel proprio documento HTML di destinazione, cioè se l'HTML risultante sarà suddiviso in più pagine HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Ottiene o imposta il titolo della pagina HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Il flag per combinare i frammenti di immagine in un'unica immagine. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Se l'attributo UseZOrder è impostato su true, le grafiche e il testo vengono aggiunti al documento HTML risultante secondo l'ordine Z nel documento PDF originale. Se questo attributo è false, tutta la grafica è posizionata come un singolo layer, il che può causare alcuni effetti indesiderati per gli oggetti sovrapposti. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di salvataggio deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Questo parametro definisce le misure di antialiasing richieste durante la conversione delle immagini di sfondo composte da PDF a HTML |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Quando il convertitore PDFtoHTML genera i CSS risultanti, i nomi delle classi CSS (qualcosa come ".stl_01 {}" ... ".stl_NN {}") vengono generati e utilizzati nel CSS risultante. Questa proprietà consente di impostare forzatamente il prefisso del nome della classe. Ad esempio, se desideri che tutti i nomi delle classi inizino con 'my_prefix_' (cioè siano qualcosa come 'my_prefix_1' ... 'my_prefix_NNN'), allora basta assegnare 'my_prefix_' a questa proprietà prima della conversione. Se questa proprietà rimane intatta (cioè null viene lasciato come valore), il convertitore genererà i nomi delle classi da solo (sarà qualcosa come ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Questo campo può contenere la strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione da Pdf a Html per la gestione del salvataggio dei CSS relativi al documento HTML creato nel suo insieme o alle sue pagine (se vengono generate più pagine HTML). Se desideri gestire il file CSS in un modo specifico, ti preghiamo di creare il metodo pertinente e assegnare il delegato creato da esso a questa proprietà. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Il risultato della conversione può contenere una o più pagine HTML. Puoi assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una pagina HTML (per essere precisi - markup-HTML, senza file collegati esternamente, se presenti) che è stata creata durante la conversione. In tal caso, l'elaborazione (come il salvataggio dell'HTML della pagina in uno stream o su disco) può essere eseguita in quel codice personalizzato. In tal caso, tutte le azioni necessarie per il salvataggio della pagina HTML devono essere intraprese nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel caso per qualche motivo deve essere eseguita dal codice stesso del convertitore, non nel codice personalizzato, ti preghiamo di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'htmlSavingInfo': segnalerà al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso nello stesso modo in cui se non ci fosse alcun codice personalizzato esterno per l'elaborazione. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Questo gestore può essere utilizzato per gestire gli eventi di avanzamento della conversione, ad esempio può essere utilizzato per mostrare una barra di avanzamento o messaggi sulla quantità attuale di pagine elaborate, un esempio di codice del gestore che mostra il progresso sulla console è: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Questo campo può contenere la strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione per la gestione personalizzata dei file di risorse referenziati creati (come immagini e font) relativi ai nodi dell'HTML salvato. Quella strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URL desiderato della risorsa salvata nell'HTML generato. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Questo campo può contenere un metodo personalizzato che restituisce l'URL (o il modello di URL se la generazione multipagina è attivata - vedere i dettagli qui sotto) del CSS soggetto come dovrebbe essere inserito nell'HTML risultante generato. Ad esempio, se desideri che il convertitore inserisca un URL specifico invece del nome del file CSS standard nell'CSS generato, allora dovresti semplicemente creare e inserire in questa proprietà un metodo che genera l'URL desiderato. Se il flag 'SplitCssIntoPages' è impostato, allora questa strategia personalizzata (se presente) deve restituire non l'URL esatto del CSS ma piuttosto una stringa modello che (dopo la sostituzione del segnaposto con il numero di pagina con la funzione string.Format() all'interno del convertitore) può essere risolta nell'URL per l'URL del CSS di questa o quella pagina. Esempi di stringhe di ritorno attese in tal caso sono: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Elenco dei nomi dei font incorporati nel PDF che non saranno incorporati nell'HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Definisce una regola di codifica speciale per ottimizzare la decodifica PDF per il documento corrente |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Definisce la modalità di salvataggio del font che sarà utilizzata durante il salvataggio del PDF nel formato desiderato |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | A volte sono presenti requisiti specifici per la generazione del markup HTML. Questo parametro definisce le modalità di preparazione dell'HTML che possono essere utilizzate durante la conversione da PDF a HTML per soddisfare tali requisiti specifici. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in più thread. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Imposta la modalità di posizionamento delle lettere nelle parole nell'HTML risultante |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Questo attributo rappresenta un insieme di impostazioni utilizzate per disegnare il bordo (se presente) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF sorgente. In sostanza, riguarda la visualizzazione dei bordi della carta della pagina, non il bordo della pagina riferito nella pagina PDF stessa. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Questo attributo rappresenta un insieme di margini extra della pagina (se presenti) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF sorgente. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input sarà inserito in un grande file HTML risultante. Questo flag definisce se l'HTML risultante sarà generato in modo tale che il flusso delle aree che rappresentano le pagine PDF nell'HTML risultante dipenderà dalla risoluzione dello schermo del visualizzatore. Supponiamo che la larghezza dello schermo sul lato del visualizzatore sia abbastanza grande da inserire 2 o più pagine una accanto all'altra in direzione orizzontale. Se questo flag è impostato su true, allora questa opportunità sarà utilizzata (quante più pagine saranno mostrate in direzione orizzontale una accanto all'altra quanto possibile, quindi il successivo gruppo orizzontale di pagine sarà mostrato sotto il primo). Altrimenti, le pagine fluiranno in questo modo: la pagina successiva va sempre sotto la precedente. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Definisce se i file referenziati (HTML, Font, Immagini, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | I PDF convertiti possono contenere immagini raster. Questo parametro definisce come devono essere gestite durante la conversione da PDF a HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Definisce se nelle HTML create verranno rimossi gli spazi vuoti superiori e inferiori senza alcun contenuto (se presenti). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | I PDF possono contenere testi che sono ombreggiati da altri elementi (ad esempio, da immagini) ma possono essere selezionati negli appunti in Acrobat Reader (di solito accade quando il documento contiene immagini e testi OCR estratti da esso). Questa impostazione indica al convertitore se dobbiamo salvare tali testi come testi trasparenti selezionabili nell'HTML risultante per imitare il comportamento di Acrobat Reader (altrimenti tali testi vengono solitamente salvati come nascosti, non disponibili per la copia negli appunti) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | I PDF possono contenere testi trasparenti che possono essere selezionati negli appunti (di solito accade quando il documento contiene immagini e testi OCR estratti da esso). Questa impostazione indica al convertitore se dobbiamo salvare tali testi come testi trasparenti selezionabili nell'HTML risultante |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Ottiene o imposta il percorso della directory in cui devono essere salvate tutte le immagini se vengono incontrate durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file immagine (se presenti) verranno salvati insieme ad altri file collegati all'HTML. Non influisce su nulla se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il file immagine pertinente. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Ottiene o imposta il percorso della directory in cui devono essere salvate solo le immagini SVG se vengono incontrate durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file SVG (se presenti) verranno salvati insieme ad altri file immagine (vicino al file di output) o in una cartella speciale per le immagini (se specificata nell'opzione SpecialImagesFolderIfAny). Non influisce su nulla se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il file immagine pertinente. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo identiche messe una accanto all'altra. In tal caso, i renderer dei formati di destinazione (ad esempio, MsWord per il formato DOCS) a volte generano confini visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di levigatura dei bordi delle immagini (anti-aliasing) sono diverse da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali confini visibili tra le parti delle stesse immagini di sfondo, ti preghiamo di provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità rallenta solitamente notevolmente la conversione, quindi, ti preghiamo di utilizzare questa opzione solo quando è davvero necessario. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | Il PDF stesso non contiene marcatori di sottolineatura per i testi. Viene emulato con una linea situata sotto il testo. Questa opzione consente al convertitore di provare a indovinare che questa o quella linea è una sottolineatura del testo e di inserire queste informazioni nel CSS invece di disegnare graficamente la sottolineatura |

## Esempi

Il seguente esempio mostra come convertire un file PDF in un file HTML

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
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

### Vedi Anche

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* interfaccia [IPageSetOptions](../ipagesetoptions/)
* interfaccia [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)