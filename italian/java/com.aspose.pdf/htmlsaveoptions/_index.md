---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Opzioni di salvataggio per l'esportazione in formato Html"
type: docs
weight: 1990
url: /it/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

Opzioni di salvataggio per l'esportazione in formato Html

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | Inizializza una nuova istanza della classe HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | Inizializza una nuova istanza della classe {@code HtmlSaveOptions}. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | Inizializza una nuova istanza della classe HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | Inizializza una nuova istanza della classe HtmlSaveOptions. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input non verrà suddiviso in pagine HTML separate, ma sarà inserito in un unico grande file HTML di risultato. Tuttavia ogni pagina PDF di origine sarà rappresentata con la propria area rettangolare in HTML (se necessario tali aree possono essere bordate per mostrare i bordi della carta della pagina con l'attributo speciale 'PageBorderIfAny'). Questo parametro definisce la larghezza del margine che sarà forzatamente lasciato intorno a quelle aree HTML di output che rappresentano le pagine del documento PDF di origine. In sostanza definisce l'intervallo garantito tra le rappresentazioni HTML delle pagine \"paper\" PDF in questa modalità di conversione. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | Questo parametro definisce le misure di antialiasing richieste durante la conversione di immagini di sfondo composte da PDF a HTML. |
| [getBatchSize](#getBatchSize--) | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | Quando il convertitore PDFtoHTML genera i CSS di risultato, i nomi delle classi CSS (qualcosa come \".stl_01 {}\" ... \".stl_NN {}\") vengono generati e utilizzati nel CSS di risultato. Questa proprietà consente di impostare forzatamente il prefisso del nome della classe. Ad esempio, se si desidera che tutti i nomi delle classi inizino con 'my_prefix_' (cioè qualcosa come 'my_prefix_1' ... 'my_prefix_NNN'), basta assegnare 'my_prefix_' a questa proprietà prima della conversione. Se questa proprietà rimane invariata (cioè null viene lasciato come valore), il convertitore genererà autonomamente i nomi delle classi (sarà qualcosa come \".stl_01 {}\" ... \".stl_NN {}\"). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione da PDF a HTML per la gestione del salvataggio dei CSS relativi al documento HTML creato nel suo complesso o alle sue pagine (se vengono generate più pagine HTML). Se si desidera gestire il file CSS in modo specifico, è sufficiente creare il metodo pertinente e assegnare il delegato creato a questa proprietà. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | Il risultato della conversione può contenere una o più pagine HTML. È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una pagina HTML (in modo più preciso – markup HTML, senza file collegati esterni, se presenti) creata durante la conversione. In tal caso l'elaborazione (come il salvataggio dell'HTML della pagina in stream o su disco) può essere eseguita in quel codice personalizzato. In tal caso tutte le azioni necessarie per il salvataggio della pagina HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se, per qualche motivo, l'elaborazione per questo o quello caso deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato la flag 'CustomProcessingCancelled' della variabile del parametro 'htmlSavingInfo': segnalerà al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso, nello stesso modo in cui avverrebbe se non ci fosse alcun codice personalizzato esterno per l'elaborazione. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, ad es. può essere usato per mostrare una barra di progresso o messaggi sulla quantità corrente di pagine elaborate; un esempio di codice del gestore che mostra il progresso sulla console è: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | Questo campo può contenere la strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione per la gestione personalizzata dei file di risorse referenziati creati (come immagini e font) relativi ai nodi dell'HTML salvato. Tale strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URL desiderato della risorsa salvata nell'HTML generato. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | Questo campo può contenere un metodo personalizzato che restituisce l'URL (o il modello di URL se la generazione multipagina è attiva – vedere i dettagli sotto) del CSS di riferimento così come deve essere inserito nell'HTML risultato generato. Per esempio, se si desidera che il convertitore inserisca un URL specifico al posto del nome file CSS standard nel CSS generato, è sufficiente creare e assegnare a questa proprietà un metodo che genera l'URL desiderato. Se il flag 'SplitCssIntoPages' è impostato, allora questa strategia personalizzata (se presente) deve restituire non l'URL esatto del CSS ma una stringa modello che (dopo la sostituzione del segnaposto con il numero di pagina tramite la funzione String.Format() all'interno del convertitore) può essere risolta in un URL per il CSS di quella pagina. Esempi di stringa di ritorno prevista in tal caso sono: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' ) |
| [getDefaultFontName](#getDefaultFontName--) | Specifica il nome di un font installato che viene utilizzato per sostituire qualsiasi font del documento non incorporato e non installato nel sistema. Se null, viene utilizzato il font di sostituzione predefinito. |
| [getDocumentType](#getDocumentType--) | Ottiene il {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | Elenco dei nomi dei font incorporati nel PDF che non devono essere incorporati in HTML. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | Con questa proprietà è possibile definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Cioè, i numeri validi delle pagine devono essere presi dall'intervallo (1...[NumberOfPagesInConvertedDocument]). L'ordine di comparsa delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti – nelle pagine risultanti andranno sempre nell'ordine in cui sono presenti nel PDF di origine. Se questo elenco è nullo (come è impostato per impostazione predefinita), tutte le pagine saranno convertite. Se qualche numero di pagina di questo elenco supera l'intervallo delle pagine presenti (1-[amountOfPagesInDocument]) verrà sollevata un'eccezione. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | Questo attributo specifica il testo del paragrafo a larghezza piena per la modalità Flow, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Definisce una regola speciale di codifica per ottimizzare la decodifica PDF per il documento corrente |
| [getFontSavingMode](#getFontSavingMode--) | Definisce la modalità di salvataggio dei font che sarà utilizzata durante il salvataggio del PDF nel formato desiderato |
| [getFontSources](#getFontSources--) | <p> Origini dei font dei font pre‑salvati. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | A volte sono presenti requisiti specifici per la generazione del markup HTML. Questo parametro definisce le modalità di preparazione dell'HTML che possono essere utilizzate durante la conversione da PDF a HTML per soddisfare tali requisiti specifici. |
| [getImageResolution](#getImageResolution--) | Ottiene o imposta la risoluzione per il rendering delle immagini. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Imposta la modalità di posizionamento delle lettere nelle parole nell'HTML risultante |
| [getMinimalLineWidth](#getMinimalLineWidth--) | Questo attributo imposta la larghezza minima della linea di un percorso grafico. Se lo spessore della linea è inferiore a 1 px, Adobe Acrobat lo arrotonda a questo valore. Pertanto, questo attributo può essere usato per emulare questo comportamento nei browser HTML. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | Questo attributo rappresenta un insieme di impostazioni utilizzate per disegnare il bordo (se presente) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF di origine. In sostanza riguarda la visualizzazione dei margini della carta della pagina, non il bordo della pagina riferito nel PDF stesso. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | Questo attributo rappresenta un insieme di margini di pagina aggiuntivi (se presenti) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF di origine. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | Definisce se i file di riferimento (HTML, Font, Immagini, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | Il PDF convertito può contenere immagini raster. Questo parametro definisce come devono essere gestite durante la conversione da PDF a HTML |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Ottiene o imposta il percorso della directory in cui devono essere salvate le immagini, se presenti, durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file immagine (se presenti) verranno salvati insieme agli altri file collegati all'HTML. Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Ottiene o imposta il percorso della directory in cui devono essere salvate solo le immagini SVG, se presenti, durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file SVG (se presenti) verranno salvati insieme agli altri file immagine (vicino al file di output) o in una cartella speciale per le immagini (se specificata nell'opzione SpecialImagesFolderIfAny). Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine. |
| [getTitle](#getTitle--) | Ottiene o imposta il titolo della pagina HTML. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Ottiene il flag che indica se le grafiche SVG trovate (se presenti) saranno compresse (zippate) nel formato SVGZ durante il salvataggio. Valore: {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | Se l'attributo ConvertMarkedContentToLayers è impostato su true, tutti gli elementi all'interno di un contenuto marcato PDF (layer) verranno inseriti in un div HTML con l'attributo \"data-pdflayer\" che specifica il nome del layer. Questo nome del layer sarà estratto dalle proprietà opzionali del contenuto marcato PDF. Se questo attributo è false (per impostazione predefinita), non verranno creati layer dal contenuto marcato PDF. |
| [isFixedLayout](#isFixedLayout--) | Ottiene un valore che indica se l'HTML è stato creato come layout fisso. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true – indica che gli errori di assenza di font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita. |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input verrà inserito in un unico grande file HTML di risultato. Questa flag definisce se l'HTML di risultato sarà generato in modo tale che il flusso delle aree che rappresentano le pagine PDF nell'HTML di risultato dipenda dalla risoluzione dello schermo del visualizzatore. Supponiamo che la larghezza dello schermo sul lato visualizzatore sia sufficientemente grande da posizionare 2 o più pagine una accanto all'altra in direzione orizzontale. Se questa flag è impostata su true, allora questa opportunità sarà utilizzata (tante pagine saranno mostrate in direzione orizzontale una accanto all'altra per quanto possibile, poi il prossimo gruppo orizzontale di pagine sarà mostrato sotto la prima). Altrimenti le pagine fluiranno in questo modo: la pagina successiva va sempre sotto la precedente. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | Questo attributo attiva la modalità in cui i glifi di testo non saranno raggruppati in parole e stringhe. Questa modalità consente di mantenere la massima precisione durante il posizionamento dei glifi sulla pagina e può essere utilizzata per la conversione di documenti con note musicali o glifi che devono essere posizionati separatamente l'uno dall'altro. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Definisce se nell'HTML creato verranno rimosse le aree vuote superiore e inferiore senza alcun contenuto (se presenti). |
| [isRenderTextAsImage](#isRenderTextAsImage--) | Se l'attributo RenderTextAsImage è impostato su true, il testo della sorgente diventa un'immagine nell'HTML. Può essere utile per rendere il testo non selezionabile o quando il testo HTML non viene renderizzato correttamente. |
| [isSaveFullFont](#isSaveFullFont--) | Indica che verrà salvato il font completo, supporta solo i font True Type. Per impostazione predefinita SaveFullFont = false e il convertitore salva il sottoinsieme del font iniziale necessario per visualizzare il testo del documento. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | Il PDF può contenere testi che sono ombreggiati da altri elementi (ad es. da immagini) ma che possono essere selezionati negli appunti in Acrobat Reader (di solito accade quando il documento contiene immagini e testi OCR estratti da esse). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML di risultato per imitare il comportamento di Acrobat Reader (altrimenti tali testi sono solitamente salvati come nascosti, non disponibili per la copia negli appunti). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Il PDF può contenere testi trasparenti che possono essere selezionati negli appunti (di solito accade quando il documento contiene immagini e testi OCR estratti da esse). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML di risultato. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | Questo attributo specifica un raggruppamento sequenziale di glifi e parole in stringhe. Per esempio, i tag e le parole hanno ordine diverso nell'HTML convertito e si desidera che corrispondano. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | Quando è selezionata la modalità multipagina (cioè 'SplitIntoPages' è 'true'), questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML di risultato. Per impostazione predefinita questo attributo è false, quindi verrà creato un unico grande CSS comune per tutte le pagine create. La dimensione complessiva di tutti i CSS generati in questa modalità (un CSS per pagina) è solitamente molto maggiore della dimensione di un unico grande file CSS, perché nel primo caso le classi CSS sono duplicate in diversi file CSS per ciascuna pagina. Pertanto, questa impostazione è consigliata solo quando si è interessati a elaborare in futuro ogni pagina HTML in modo indipendente, e quindi la dimensione del CSS di ogni singola pagina separata è la questione più critica. |
| [isSplitIntoPages](#isSplitIntoPages--) | Restituisce la flag che indica se ogni pagina del documento di origine sarà convertita nel proprio documento HTML di destinazione, cioè se l'HTML di risultato sarà suddiviso in più pagine HTML. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | Il PDF stesso non contiene marcatori di sottolineatura per i testi. È emulato con una linea situata sotto il testo. Questa opzione consente al convertitore di provare a indovinare se questa o quella linea è una sottolineatura del testo e inserire queste informazioni nel CSS invece di disegnare la sottolineatura graficamente. |
| [isUseZOrder](#isUseZOrder--) | Se l'attributo UseZORder è impostato su true, le grafiche e il testo vengono aggiunti al documento HTML risultante secondo l'ordine Z nel documento PDF originale. Se questo attributo è false, tutte le grafiche vengono inserite come unico livello, il che può causare alcuni effetti indesiderati per gli oggetti sovrapposti. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input non verrà suddiviso in pagine HTML separate, ma sarà inserito in un unico grande file HTML di risultato. Tuttavia ogni pagina PDF di origine sarà rappresentata con la propria area rettangolare in HTML (se necessario tali aree possono essere bordate per mostrare i bordi della carta della pagina con l'attributo speciale 'PageBorderIfAny'). Questo parametro definisce la larghezza del margine che sarà forzatamente lasciato intorno a quelle aree HTML di output che rappresentano le pagine del documento PDF di origine. In sostanza definisce l'intervallo garantito tra le rappresentazioni HTML delle pagine \"paper\" PDF in questa modalità di conversione. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | Questo parametro definisce le misure di antialiasing richieste durante la conversione di immagini di sfondo composte da PDF a HTML. |
| [setBatchSize](#setBatchSize-int-) | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Imposta il flag che indica se le grafiche SVG trovate (se presenti) verranno compresse (zippate) nel formato SVGZ durante il salvataggio Valore: Il {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | Se l'attributo ConvertMarkedContentToLayers è impostato su true, tutti gli elementi all'interno di un contenuto marcato PDF (layer) verranno inseriti in un div HTML con l'attributo \"data-pdflayer\" che specifica il nome del layer. Questo nome del layer sarà estratto dalle proprietà opzionali del contenuto marcato PDF. Se questo attributo è false (per impostazione predefinita), non verranno creati layer dal contenuto marcato PDF. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | Quando il convertitore PDFtoHTML genera i CSS di risultato, i nomi delle classi CSS (qualcosa come \".stl_01 {}\" ... \".stl_NN {}\") vengono generati e utilizzati nel CSS di risultato. Questa proprietà consente di impostare forzatamente il prefisso del nome della classe. Ad esempio, se si desidera che tutti i nomi delle classi inizino con 'my_prefix_' (cioè qualcosa come 'my_prefix_1' ... 'my_prefix_NNN'), basta assegnare 'my_prefix_' a questa proprietà prima della conversione. Se questa proprietà rimane invariata (cioè null viene lasciato come valore), il convertitore genererà autonomamente i nomi delle classi (sarà qualcosa come \".stl_01 {}\" ... \".stl_NN {}\"). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione da PDF a HTML per la gestione del salvataggio dei CSS relativi al documento HTML creato nel suo complesso o alle sue pagine (se vengono generate più pagine HTML). Se si desidera gestire il file CSS in modo specifico, è sufficiente creare il metodo pertinente e assegnare il delegato creato a questa proprietà. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Il risultato della conversione può contenere una o più pagine HTML. È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una pagina HTML (per essere precisi: markup-HTML, senza file collegati esterni, se presenti) che è stata creata durante la conversione. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, per esempio. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione per la gestione personalizzata dei file di risorse referenziati creati (come immagini e font) correlati ai nodi dell'HTML salvato. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Questo campo può contenere un metodo personalizzato che restituisce l'URL (o il modello di URL se la generazione multipagina è attiva - vedere i dettagli sotto) del CSS di riferimento così come dovrebbe essere inserito nell'HTML generato. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Specifica il nome di un font installato che viene utilizzato per sostituire qualsiasi font del documento non incorporato e non installato nel sistema. Se null, viene utilizzato il font di sostituzione predefinito. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | Imposta il {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | Elenco dei nomi dei font incorporati nel PDF che non devono essere incorporati in HTML. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | Con questa proprietà è possibile definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Cioè, i numeri validi delle pagine devono essere presi dall'intervallo (1...[NumberOfPagesInConvertedDocument]). L'ordine di comparsa delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti – nelle pagine risultanti andranno sempre nell'ordine in cui sono presenti nel PDF di origine. Se questo elenco è nullo (come è impostato per impostazione predefinita), tutte le pagine saranno convertite. Se qualche numero di pagina di questo elenco supera l'intervallo delle pagine presenti (1-[amountOfPagesInDocument]) verrà sollevata un'eccezione. |
| [setFixedLayout](#setFixedLayout-boolean-) | Imposta un valore che indica se quell'HTML è creato come layout fisso. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | Questo attributo specifica il testo del paragrafo a larghezza piena per la modalità Flow, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Definisce una regola speciale di codifica per ottimizzare la decodifica PDF per il documento corrente |
| [setFontSavingMode](#setFontSavingMode-int-) | Definisce la modalità di salvataggio dei font che sarà utilizzata durante il salvataggio del PDF nel formato desiderato |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | A volte sono presenti requisiti specifici per la generazione del markup HTML. Questo parametro definisce le modalità di preparazione dell'HTML che possono essere utilizzate durante la conversione da PDF a HTML per soddisfare tali requisiti specifici. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true – indica che gli errori di assenza di font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita. |
| [setImageResolution](#setImageResolution-int-) | Ottiene o imposta la risoluzione per il rendering delle immagini. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Imposta la modalità di posizionamento delle lettere nelle parole nell'HTML risultante |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | Questo attributo imposta la larghezza minima della linea di un percorso grafico. Se lo spessore della linea è inferiore a 1 px, Adobe Acrobat lo arrotonda a questo valore. Pertanto, questo attributo può essere usato per emulare questo comportamento nei browser HTML. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Questo attributo rappresenta l'insieme delle impostazioni usate per disegnare il bordo (se presente) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF di origine. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Questo attributo rappresenta un insieme di margini di pagina aggiuntivi (se presenti) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF di origine. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input verrà inserito in un unico grande file HTML di risultato. Questa flag definisce se l'HTML di risultato sarà generato in modo tale che il flusso delle aree che rappresentano le pagine PDF nell'HTML di risultato dipenda dalla risoluzione dello schermo del visualizzatore. Supponiamo che la larghezza dello schermo sul lato visualizzatore sia sufficientemente grande da posizionare 2 o più pagine una accanto all'altra in direzione orizzontale. Se questa flag è impostata su true, allora questa opportunità sarà utilizzata (tante pagine saranno mostrate in direzione orizzontale una accanto all'altra per quanto possibile, poi il prossimo gruppo orizzontale di pagine sarà mostrato sotto la prima). Altrimenti le pagine fluiranno in questo modo: la pagina successiva va sempre sotto la precedente. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | Definisce se i file di riferimento (HTML, Font, Immagini, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | Questo attributo attiva la modalità in cui i glifi di testo non saranno raggruppati in parole e stringhe. Questa modalità consente di mantenere la massima precisione durante il posizionamento dei glifi sulla pagina e può essere utilizzata per la conversione di documenti con note musicali o glifi che devono essere posizionati separatamente l'uno dall'altro. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | Il PDF convertito può contenere immagini raster. Questo parametro definisce come devono essere gestite durante la conversione da PDF a HTML |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Definisce se nell'HTML creato verranno rimosse le aree vuote superiore e inferiore senza alcun contenuto (se presenti). |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | Se l'attributo RenderTextAsImage è impostato su true, il testo della sorgente diventa un'immagine nell'HTML. Può essere utile per rendere il testo non selezionabile o quando il testo HTML non viene renderizzato correttamente. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Indica che verrà salvato il font completo, supporta solo i font True Type. Per impostazione predefinita SaveFullFont = false e il convertitore salva il sottoinsieme del font iniziale necessario per visualizzare il testo del documento. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Il PDF può contenere testi che sono ombreggiati da altri elementi (ad es. da immagini) ma che possono essere selezionati negli appunti in Acrobat Reader (di solito accade quando il documento contiene immagini e testi OCR estratti da esse). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML di risultato per imitare il comportamento di Acrobat Reader (altrimenti tali testi sono solitamente salvati come nascosti, non disponibili per la copia negli appunti). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Il PDF può contenere testi trasparenti che possono essere selezionati negli appunti (di solito accade quando il documento contiene immagini e testi OCR estratti da esse). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML di risultato. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | Questo attributo specifica un raggruppamento sequenziale di glifi e parole in stringhe. Per esempio, i tag e le parole hanno ordine diverso nell'HTML convertito e si desidera che corrispondano. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Ottiene o imposta il percorso della directory in cui devono essere salvate le immagini, se presenti, durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file immagine (se presenti) verranno salvati insieme agli altri file collegati all'HTML. Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Ottiene o imposta il percorso della directory in cui devono essere salvate solo le immagini SVG, se presenti, durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file SVG (se presenti) verranno salvati insieme agli altri file immagine (vicino al file di output) o in una cartella speciale per le immagini (se specificata nell'opzione SpecialImagesFolderIfAny). Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | Quando è selezionata la modalità multipagina (cioè 'SplitIntoPages' è 'true'), questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML di risultato. Per impostazione predefinita questo attributo è false, quindi verrà creato un unico grande CSS comune per tutte le pagine create. La dimensione complessiva di tutti i CSS generati in questa modalità (un CSS per pagina) è solitamente molto maggiore della dimensione di un unico grande file CSS, perché nel primo caso le classi CSS sono duplicate in diversi file CSS per ciascuna pagina. Pertanto, questa impostazione è consigliata solo quando si è interessati a elaborare in futuro ogni pagina HTML in modo indipendente, e quindi la dimensione del CSS di ogni singola pagina separata è la questione più critica. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Imposta il flag che indica se ogni pagina del documento di origine sarà convertita nel proprio documento HTML di destinazione, cioè se l'HTML risultante sarà suddiviso in più pagine HTML. |
| [setTitle](#setTitle-java.lang.String-) | Ottiene o imposta il titolo della pagina HTML. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | Il PDF stesso non contiene marcatori di sottolineatura per i testi. È emulato con una linea situata sotto il testo. Questa opzione consente al convertitore di provare a indovinare se questa o quella linea è una sottolineatura del testo e inserire queste informazioni nel CSS invece di disegnare la sottolineatura graficamente. |
| [setUseZOrder](#setUseZOrder-boolean-) | Se l'attributo UseZORder è impostato su true, le grafiche e il testo vengono aggiunti al documento HTML risultante secondo l'ordine Z nel documento PDF originale. Se questo attributo è false, tutte le grafiche vengono inserite come unico livello, il che può causare alcuni effetti indesiderati per gli oggetti sovrapposti. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

Inizializza una nuova istanza della classe HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

Inizializza una nuova istanza della classe {@code HtmlSaveOptions}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fixedLayout |  | valore booleano |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
Inizializza una nuova istanza della classe HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
Inizializza una nuova istanza della classe HtmlSaveOptions.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input non verrà suddiviso in pagine HTML separate, ma sarà inserito in un unico grande file HTML di risultato. Tuttavia ogni pagina PDF di origine sarà rappresentata con la propria area rettangolare in HTML (se necessario tali aree possono essere bordate per mostrare i bordi della carta della pagina con l'attributo speciale 'PageBorderIfAny'). Questo parametro definisce la larghezza del margine che sarà forzatamente lasciato intorno a quelle aree HTML di output che rappresentano le pagine del documento PDF di origine. In sostanza definisce l'intervallo garantito tra le rappresentazioni HTML delle pagine \"paper\" PDF in questa modalità di conversione.

**Returns:**
valore int @deprecated AdditionalMarginWidthInPoints è deprecato, si prega di usare PageMarginIfAny al suo posto.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

Questo parametro definisce le misure di antialiasing richieste durante la conversione di immagini di sfondo composte da PDF a HTML.

**Returns:**
elemento AntialiasingProcessingType @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione.

**Returns:**
valore int

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

Quando il convertitore PDFtoHTML genera i CSS di risultato, i nomi delle classi CSS (qualcosa come \".stl_01 {}\" ... \".stl_NN {}\") vengono generati e utilizzati nel CSS di risultato. Questa proprietà consente di impostare forzatamente il prefisso del nome della classe. Ad esempio, se si desidera che tutti i nomi delle classi inizino con 'my_prefix_' (cioè qualcosa come 'my_prefix_1' ... 'my_prefix_NNN'), basta assegnare 'my_prefix_' a questa proprietà prima della conversione. Se questa proprietà rimane invariata (cioè null viene lasciato come valore), il convertitore genererà autonomamente i nomi delle classi (sarà qualcosa come \".stl_01 {}\" ... \".stl_NN {}\").

**Returns:**
valore String

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione da PDF a HTML per la gestione del salvataggio dei CSS relativi al documento HTML creato nel suo complesso o alle sue pagine (se vengono generate più pagine HTML). Se si desidera gestire il file CSS in modo specifico, è sufficiente creare il metodo pertinente e assegnare il delegato creato a questa proprietà.

**Returns:**
istanza CssSavingStrategy

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

Il risultato della conversione può contenere una o più pagine HTML. È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una pagina HTML (in modo più preciso – markup HTML, senza file collegati esterni, se presenti) creata durante la conversione. In tal caso l'elaborazione (come il salvataggio dell'HTML della pagina in stream o su disco) può essere eseguita in quel codice personalizzato. In tal caso tutte le azioni necessarie per il salvataggio della pagina HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se, per qualche motivo, l'elaborazione per questo o quello caso deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato la flag 'CustomProcessingCancelled' della variabile del parametro 'htmlSavingInfo': segnalerà al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso, nello stesso modo in cui avverrebbe se non ci fosse alcun codice personalizzato esterno per l'elaborazione.

**Returns:**
istanza HtmlPageMarkupSavingStrategy

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, ad es. può essere usato per mostrare una barra di progresso o messaggi sulla quantità corrente di pagine elaborate; un esempio di codice del gestore che mostra il progresso sulla console è: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
istanza ConversionProgressEventHandler

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

Questo campo può contenere la strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione per la gestione personalizzata dei file di risorse referenziati creati (come immagini e font) relativi ai nodi dell'HTML salvato. Tale strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URL desiderato della risorsa salvata nell'HTML generato.

**Returns:**
istanza ResourceSavingStrategy

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

Questo campo può contenere un metodo personalizzato che restituisce l'URL (o il modello di URL se la generazione multipagina è attiva – vedere i dettagli sotto) del CSS di riferimento così come deve essere inserito nell'HTML risultato generato. Per esempio, se si desidera che il convertitore inserisca un URL specifico al posto del nome file CSS standard nel CSS generato, è sufficiente creare e assegnare a questa proprietà un metodo che genera l'URL desiderato. Se il flag 'SplitCssIntoPages' è impostato, allora questa strategia personalizzata (se presente) deve restituire non l'URL esatto del CSS ma una stringa modello che (dopo la sostituzione del segnaposto con il numero di pagina tramite la funzione String.Format() all'interno del convertitore) può essere risolta in un URL per il CSS di quella pagina. Esempi di stringa di ritorno prevista in tal caso sono: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' )

**Returns:**
istanza CssUrlMakingStrategy

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Specifica il nome di un font installato che viene utilizzato per sostituire qualsiasi font del documento non incorporato e non installato nel sistema. Se null, viene utilizzato il font di sostituzione predefinito.

**Returns:**
valore Stringa: Nome del font

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Ottiene il {@code HtmlDocumentTypeInternal}.

**Returns:**
Il {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

Elenco dei nomi dei font incorporati nel PDF che non devono essere incorporati in HTML.

**Returns:**
array di elementi String

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

Con questa proprietà è possibile definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Cioè, i numeri validi delle pagine devono essere presi dall'intervallo (1...[NumberOfPagesInConvertedDocument]). L'ordine di comparsa delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti – nelle pagine risultanti andranno sempre nell'ordine in cui sono presenti nel PDF di origine. Se questo elenco è nullo (come è impostato per impostazione predefinita), tutte le pagine saranno convertite. Se qualche numero di pagina di questo elenco supera l'intervallo delle pagine presenti (1-[amountOfPagesInDocument]) verrà sollevata un'eccezione.

**Returns:**
array di int

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

Questo attributo specifica il testo del paragrafo a larghezza piena per la modalità Flow, FixedLayout = false

**Returns:**
valore booleano

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Definisce una regola speciale di codifica per ottimizzare la decodifica PDF per il documento corrente

**Returns:**
elemento FontEncodingRules @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

Definisce la modalità di salvataggio dei font che sarà utilizzata durante il salvataggio del PDF nel formato desiderato

**Returns:**
elemento FontSavingModes @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Origini dei font dei font pre‑salvati. </p>

**Returns:**
oggetto FontSourceCollection <hr> <p> I font possono essere salvati preliminarmente a scopo di cache e poi passati al processo di conversione Html. Per esempio può essere utile nello scenario di divisione del documento e nell'elaborazione delle pagine del documento in più thread con un unico set di font. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

A volte sono presenti requisiti specifici per la generazione del markup HTML. Questo parametro definisce le modalità di preparazione dell'HTML che possono essere utilizzate durante la conversione da PDF a HTML per soddisfare tali requisiti specifici.

**Returns:**
elemento HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Ottiene o imposta la risoluzione per il rendering delle immagini.

**Returns:**
Valore: Risoluzione

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Imposta la modalità di posizionamento delle lettere nelle parole nell'HTML risultante

**Returns:**
Elemento LettersPositioningMethods @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

Questo attributo imposta la larghezza minima della linea di un percorso grafico. Se lo spessore della linea è inferiore a 1 px, Adobe Acrobat lo arrotonda a questo valore. Pertanto, questo attributo può essere usato per emulare questo comportamento nei browser HTML.

**Returns:**
valore float

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

Questo attributo rappresenta un insieme di impostazioni utilizzate per disegnare il bordo (se presente) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF di origine. In sostanza riguarda la visualizzazione dei margini della carta della pagina, non il bordo della pagina riferito nel PDF stesso.

**Returns:**
Istanza BorderInfo

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

Questo attributo rappresenta un insieme di margini di pagina aggiuntivi (se presenti) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF di origine.

**Returns:**
Istanza MarginInfo

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

Definisce se i file di riferimento (HTML, Font, Immagini, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate

**Returns:**
Elemento PartsEmbeddingModes @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

Il PDF convertito può contenere immagini raster. Questo parametro definisce come devono essere gestite durante la conversione da PDF a HTML

**Returns:**
Elemento RasterImagesSavingModes @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Ottiene o imposta il percorso della directory in cui devono essere salvate le immagini, se presenti, durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file immagine (se presenti) verranno salvati insieme agli altri file collegati all'HTML. Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine.

**Returns:**
valore String

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Ottiene o imposta il percorso della directory in cui devono essere salvate solo le immagini SVG, se presenti, durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file SVG (se presenti) verranno salvati insieme agli altri file immagine (vicino al file di output) o in una cartella speciale per le immagini (se specificata nell'opzione SpecialImagesFolderIfAny). Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine.

**Returns:**
valore String

### getTitle {#getTitle--}
```
public final String getTitle()
```

Ottiene o imposta il titolo della pagina HTML.

**Returns:**
valore String

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Ottiene il flag che indica se le grafiche SVG trovate (se presenti) saranno compresse (zippate) nel formato SVGZ durante il salvataggio. Valore: {@code HtmlDocumentType}.

**Returns:**
valore booleano

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

Se l'attributo ConvertMarkedContentToLayers è impostato su true, tutti gli elementi all'interno di un contenuto marcato PDF (layer) verranno inseriti in un div HTML con l'attributo \"data-pdflayer\" che specifica il nome del layer. Questo nome del layer sarà estratto dalle proprietà opzionali del contenuto marcato PDF. Se questo attributo è false (per impostazione predefinita), non verranno creati layer dal contenuto marcato PDF.

**Returns:**
valore booleano

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

Ottiene un valore che indica se l'HTML è stato creato come layout fisso.

**Returns:**
valore: {@code true} se [layout fisso]; altrimenti, {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true – indica che gli errori di assenza di font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita.

**Returns:**
valore booleano

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input verrà inserito in un unico grande file HTML di risultato. Questa flag definisce se l'HTML di risultato sarà generato in modo tale che il flusso delle aree che rappresentano le pagine PDF nell'HTML di risultato dipenda dalla risoluzione dello schermo del visualizzatore. Supponiamo che la larghezza dello schermo sul lato visualizzatore sia sufficientemente grande da posizionare 2 o più pagine una accanto all'altra in direzione orizzontale. Se questa flag è impostata su true, allora questa opportunità sarà utilizzata (tante pagine saranno mostrate in direzione orizzontale una accanto all'altra per quanto possibile, poi il prossimo gruppo orizzontale di pagine sarà mostrato sotto la prima). Altrimenti le pagine fluiranno in questo modo: la pagina successiva va sempre sotto la precedente.

**Returns:**
valore booleano

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

Questo attributo attiva la modalità in cui i glifi di testo non saranno raggruppati in parole e stringhe. Questa modalità consente di mantenere la massima precisione durante il posizionamento dei glifi sulla pagina e può essere utilizzata per la conversione di documenti con note musicali o glifi che devono essere posizionati separatamente l'uno dall'altro. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true.

**Returns:**
valore booleano

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Definisce se nell'HTML creato verranno rimosse le aree vuote superiore e inferiore senza alcun contenuto (se presenti).

**Returns:**
valore booleano

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

Se l'attributo RenderTextAsImage è impostato su true, il testo della sorgente diventa un'immagine nell'HTML. Può essere utile per rendere il testo non selezionabile o quando il testo HTML non viene renderizzato correttamente.

**Returns:**
valore booleano

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Indica che verrà salvato il font completo, supporta solo i font True Type. Per impostazione predefinita SaveFullFont = false e il convertitore salva il sottoinsieme del font iniziale necessario per visualizzare il testo del documento.

**Returns:**
valore booleano

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

Il PDF può contenere testi che sono ombreggiati da altri elementi (ad es. da immagini) ma che possono essere selezionati negli appunti in Acrobat Reader (di solito accade quando il documento contiene immagini e testi OCR estratti da esse). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML di risultato per imitare il comportamento di Acrobat Reader (altrimenti tali testi sono solitamente salvati come nascosti, non disponibili per la copia negli appunti).

**Returns:**
valore booleano

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Il PDF può contenere testi trasparenti che possono essere selezionati negli appunti (di solito accade quando il documento contiene immagini e testi OCR estratti da esse). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML di risultato.

**Returns:**
valore booleano

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

Questo attributo specifica un raggruppamento sequenziale di glifi e parole in stringhe. Per esempio, i tag e le parole hanno ordine diverso nell'HTML convertito e si desidera che corrispondano. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true.

**Returns:**
valore booleano

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

Quando è selezionata la modalità multipagina (cioè 'SplitIntoPages' è 'true'), questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML di risultato. Per impostazione predefinita questo attributo è false, quindi verrà creato un unico grande CSS comune per tutte le pagine create. La dimensione complessiva di tutti i CSS generati in questa modalità (un CSS per pagina) è solitamente molto maggiore della dimensione di un unico grande file CSS, perché nel primo caso le classi CSS sono duplicate in diversi file CSS per ciascuna pagina. Pertanto, questa impostazione è consigliata solo quando si è interessati a elaborare in futuro ogni pagina HTML in modo indipendente, e quindi la dimensione del CSS di ogni singola pagina separata è la questione più critica.

**Returns:**
valore booleano

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Restituisce la flag che indica se ogni pagina del documento di origine sarà convertita nel proprio documento HTML di destinazione, cioè se l'HTML di risultato sarà suddiviso in più pagine HTML.

**Returns:**
valore booleano

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

Il PDF stesso non contiene marcatori di sottolineatura per i testi. È emulato con una linea situata sotto il testo. Questa opzione consente al convertitore di provare a indovinare se questa o quella linea è una sottolineatura del testo e inserire queste informazioni nel CSS invece di disegnare la sottolineatura graficamente.

**Returns:**
valore booleano

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

Se l'attributo UseZORder è impostato su true, le grafiche e il testo vengono aggiunti al documento HTML risultante secondo l'ordine Z nel documento PDF originale. Se questo attributo è false, tutte le grafiche vengono inserite come unico livello, il che può causare alcuni effetti indesiderati per gli oggetti sovrapposti.

**Returns:**
valore booleano

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input non verrà suddiviso in pagine HTML separate, ma sarà inserito in un unico grande file HTML di risultato. Tuttavia ogni pagina PDF di origine sarà rappresentata con la propria area rettangolare in HTML (se necessario tali aree possono essere bordate per mostrare i bordi della carta della pagina con l'attributo speciale 'PageBorderIfAny'). Questo parametro definisce la larghezza del margine che sarà forzatamente lasciato intorno a quelle aree HTML di output che rappresentano le pagine del documento PDF di origine. In sostanza definisce l'intervallo garantito tra le rappresentazioni HTML delle pagine \"paper\" PDF in questa modalità di conversione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int @deprecated AdditionalMarginWidthInPoints è deprecato, si prega di usare PageMarginIfAny al suo posto. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

Questo parametro definisce le misure di antialiasing richieste durante la conversione di immagini di sfondo composte da PDF a HTML.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| antialiasingProcessing |  | elemento AntialiasingProcessingType @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Imposta il flag che indica se le grafiche SVG trovate (se presenti) verranno compresse (zippate) nel formato SVGZ durante il salvataggio Valore: Il {@code HtmlDocumentType}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

Se l'attributo ConvertMarkedContentToLayers è impostato su true, tutti gli elementi all'interno di un contenuto marcato PDF (layer) verranno inseriti in un div HTML con l'attributo \"data-pdflayer\" che specifica il nome del layer. Questo nome del layer sarà estratto dalle proprietà opzionali del contenuto marcato PDF. Se questo attributo è false (per impostazione predefinita), non verranno creati layer dal contenuto marcato PDF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
Quando il convertitore PDFtoHTML genera i CSS di risultato, i nomi delle classi CSS (qualcosa come \".stl_01 {}\" ... \".stl_NN {}\") vengono generati e utilizzati nel CSS di risultato. Questa proprietà consente di impostare forzatamente il prefisso del nome della classe. Ad esempio, se si desidera che tutti i nomi delle classi inizino con 'my_prefix_' (cioè qualcosa come 'my_prefix_1' ... 'my_prefix_NNN'), basta assegnare 'my_prefix_' a questa proprietà prima della conversione. Se questa proprietà rimane invariata (cioè null viene lasciato come valore), il convertitore genererà autonomamente i nomi delle classi (sarà qualcosa come \".stl_01 {}\" ... \".stl_NN {}\").

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione da PDF a HTML per la gestione del salvataggio dei CSS relativi al documento HTML creato nel suo complesso o alle sue pagine (se vengono generate più pagine HTML). Se si desidera gestire il file CSS in modo specifico, è sufficiente creare il metodo pertinente e assegnare il delegato creato a questa proprietà.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
Il risultato della conversione può contenere una o più pagine HTML. È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una pagina HTML (per essere precisi: markup-HTML, senza file collegati esterni, se presenti) che è stata creata durante la conversione.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Questo gestore può essere usato per gestire gli eventi di avanzamento della conversione, per esempio.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione per la gestione personalizzata dei file di risorse referenziati creati (come immagini e font) correlati ai nodi dell'HTML salvato.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
Questo campo può contenere un metodo personalizzato che restituisce l'URL (o il modello di URL se la generazione multipagina è attiva - vedere i dettagli sotto) del CSS di riferimento così come dovrebbe essere inserito nell'HTML generato.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Specifica il nome di un font installato che viene utilizzato per sostituire qualsiasi font del documento non incorporato e non installato nel sistema. Se null, viene utilizzato il font di sostituzione predefinito.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
Imposta il {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
Elenco dei nomi dei font incorporati nel PDF che non devono essere incorporati in HTML.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

Con questa proprietà è possibile definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Cioè, i numeri validi delle pagine devono essere presi dall'intervallo (1...[NumberOfPagesInConvertedDocument]). L'ordine di comparsa delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti – nelle pagine risultanti andranno sempre nell'ordine in cui sono presenti nel PDF di origine. Se questo elenco è nullo (come è impostato per impostazione predefinita), tutte le pagine saranno convertite. Se qualche numero di pagina di questo elenco supera l'intervallo delle pagine presenti (1-[amountOfPagesInDocument]) verrà sollevata un'eccezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

Imposta un valore che indica se quell'HTML è creato come layout fisso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | : {@code true} se [layout fisso]; altrimenti, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

Questo attributo specifica il testo del paragrafo a larghezza piena per la modalità Flow, FixedLayout = false

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Definisce una regola speciale di codifica per ottimizzare la decodifica PDF per il documento corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontEncodingStrategy |  | elemento FontEncodingRules @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

Definisce la modalità di salvataggio dei font che sarà utilizzata durante il salvataggio del PDF nel formato desiderato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontSavingMode |  | elemento FontSavingModes @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

A volte sono presenti requisiti specifici per la generazione del markup HTML. Questo parametro definisce le modalità di preparazione dell'HTML che possono essere utilizzate durante la conversione da PDF a HTML per soddisfare tali requisiti specifici.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | elemento HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati. true – indica che gli errori di assenza di font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Ottiene o imposta la risoluzione per il rendering delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore: Risoluzione |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Imposta la modalità di posizionamento delle lettere nelle parole nell'HTML risultante

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

Questo attributo imposta la larghezza minima della linea di un percorso grafico. Se lo spessore della linea è inferiore a 1 px, Adobe Acrobat lo arrotonda a questo valore. Pertanto, questo attributo può essere usato per emulare questo comportamento nei browser HTML.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
Questo attributo rappresenta l'insieme delle impostazioni usate per disegnare il bordo (se presente) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF di origine.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
Questo attributo rappresenta un insieme di margini di pagina aggiuntivi (se presenti) nel documento HTML risultante attorno all'area che rappresenta la pagina PDF di origine.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

Se l'attributo 'SplitOnPages=false', allora l'intero HTML che rappresenta tutte le pagine PDF di input verrà inserito in un unico grande file HTML di risultato. Questa flag definisce se l'HTML di risultato sarà generato in modo tale che il flusso delle aree che rappresentano le pagine PDF nell'HTML di risultato dipenda dalla risoluzione dello schermo del visualizzatore. Supponiamo che la larghezza dello schermo sul lato visualizzatore sia sufficientemente grande da posizionare 2 o più pagine una accanto all'altra in direzione orizzontale. Se questa flag è impostata su true, allora questa opportunità sarà utilizzata (tante pagine saranno mostrate in direzione orizzontale una accanto all'altra per quanto possibile, poi il prossimo gruppo orizzontale di pagine sarà mostrato sotto la prima). Altrimenti le pagine fluiranno in questo modo: la pagina successiva va sempre sotto la precedente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | valore booleano |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

Definisce se i file di riferimento (HTML, Font, Immagini, CSS) saranno incorporati nel file HTML principale o saranno generati come entità binarie separate

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| partsEmbeddingMode |  | Elemento PartsEmbeddingModes @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

Questo attributo attiva la modalità in cui i glifi di testo non saranno raggruppati in parole e stringhe. Questa modalità consente di mantenere la massima precisione durante il posizionamento dei glifi sulla pagina e può essere utilizzata per la conversione di documenti con note musicali o glifi che devono essere posizionati separatamente l'uno dall'altro. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

Il PDF convertito può contenere immagini raster. Questo parametro definisce come devono essere gestite durante la conversione da PDF a HTML

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImagesSavingMode |  | Elemento RasterImagesSavingModes @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Definisce se nell'HTML creato verranno rimosse le aree vuote superiore e inferiore senza alcun contenuto (se presenti).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | valore booleano |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

Se l'attributo RenderTextAsImage è impostato su true, il testo della sorgente diventa un'immagine nell'HTML. Può essere utile per rendere il testo non selezionabile o quando il testo HTML non viene renderizzato correttamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Indica che verrà salvato il font completo, supporta solo i font True Type. Per impostazione predefinita SaveFullFont = false e il convertitore salva il sottoinsieme del font iniziale necessario per visualizzare il testo del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

Il PDF può contenere testi che sono ombreggiati da altri elementi (ad es. da immagini) ma che possono essere selezionati negli appunti in Acrobat Reader (di solito accade quando il documento contiene immagini e testi OCR estratti da esse). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML di risultato per imitare il comportamento di Acrobat Reader (altrimenti tali testi sono solitamente salvati come nascosti, non disponibili per la copia negli appunti).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | valore booleano |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Il PDF può contenere testi trasparenti che possono essere selezionati negli appunti (di solito accade quando il documento contiene immagini e testi OCR estratti da esse). Questa impostazione indica al convertitore se è necessario salvare tali testi come testi trasparenti selezionabili nell'HTML di risultato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| saveTransparentTexts |  | valore booleano |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

Questo attributo specifica un raggruppamento sequenziale di glifi e parole in stringhe. Per esempio, i tag e le parole hanno ordine diverso nell'HTML convertito e si desidera che corrispondano. Questo parametro sarà applicato al documento solo quando il valore dell'attributo FixedLayout è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Ottiene o imposta il percorso della directory in cui devono essere salvate le immagini, se presenti, durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file immagine (se presenti) verranno salvati insieme agli altri file collegati all'HTML. Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Ottiene o imposta il percorso della directory in cui devono essere salvate solo le immagini SVG, se presenti, durante il salvataggio del documento come HTML. Se il parametro è vuoto o null, i file SVG (se presenti) verranno salvati insieme agli altri file immagine (vicino al file di output) o in una cartella speciale per le immagini (se specificata nell'opzione SpecialImagesFolderIfAny). Non influisce in alcun modo se la proprietà CustomImageSavingStrategy è stata utilizzata con successo per elaborare il relativo file immagine.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

Quando è selezionata la modalità multipagina (cioè 'SplitIntoPages' è 'true'), questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML di risultato. Per impostazione predefinita questo attributo è false, quindi verrà creato un unico grande CSS comune per tutte le pagine create. La dimensione complessiva di tutti i CSS generati in questa modalità (un CSS per pagina) è solitamente molto maggiore della dimensione di un unico grande file CSS, perché nel primo caso le classi CSS sono duplicate in diversi file CSS per ciascuna pagina. Pertanto, questa impostazione è consigliata solo quando si è interessati a elaborare in futuro ogni pagina HTML in modo indipendente, e quindi la dimensione del CSS di ogni singola pagina separata è la questione più critica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Imposta il flag che indica se ogni pagina del documento di origine sarà convertita nel proprio documento HTML di destinazione, cioè se l'HTML risultante sarà suddiviso in più pagine HTML.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTitle {#setTitle-java.lang.String-}
Ottiene o imposta il titolo della pagina HTML.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

Il PDF stesso non contiene marcatori di sottolineatura per i testi. È emulato con una linea situata sotto il testo. Questa opzione consente al convertitore di provare a indovinare se questa o quella linea è una sottolineatura del testo e inserire queste informazioni nel CSS invece di disegnare la sottolineatura graficamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | valore booleano |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

Se l'attributo UseZORder è impostato su true, le grafiche e il testo vengono aggiunti al documento HTML risultante secondo l'ordine Z nel documento PDF originale. Se questo attributo è false, tutte le grafiche vengono inserite come unico livello, il che può causare alcuni effetti indesiderati per gli oggetti sovrapposti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
