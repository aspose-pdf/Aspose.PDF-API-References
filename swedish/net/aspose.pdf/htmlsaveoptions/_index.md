---
title: "Klass HtmlSaveOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlSaveOptions-klass. Spara alternativ för export till Html-format."
type: docs
weight: 5690
url: /sv/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Spara alternativ för export till Html-format

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Initierar en ny instans av klassen `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Initierar en ny instans av klassen `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Initierar en ny instans av klassen `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Initierar en ny instans av klassen `HtmlSaveOptions`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Definierar batch-storlek om batch-konvertering är tillämplig för käll- och destinationsformatparet. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om Response‑objektet ska stängas efter att dokumentet har sparats i svaret. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Hämtar eller anger flaggan som indikerar om hittad SVG-grafik (om någon) ska komprimeras (zippas) till SVGZ-format vid sparande. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Om attributet ConvertMarkedContentToLayers är satt till true placeras alla element inom ett PDF-märkt innehåll (lager) i en HTML-div med attributet "data-pdflayer" som specificerar ett lagernamn. Detta lagernamn extraheras från valfria egenskaper för PDF-märkt innehåll. Om detta attribut är false (standard) skapas inga lager från PDF-märkt innehåll. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Anger namnet på ett installerat teckensnitt som används för att ersätta alla dokumentteckensnitt som inte är inbäddade och inte är installerade i systemet. Om null används standardersättningsteckensnittet. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Hämtar eller anger [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1-baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i de resulterande HTML-sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll-PDF:en. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF‑dokument med OCR‑undervärld. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Hämtar eller anger ett värde som indikerar om HTML skapas som fast layout. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Detta attribut specificerar fullbreddstext för stycke i flödesläge, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Teckensnittskällor för förhandssparade teckensnitt. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Text med den angivna storleken eller mindre kommer att ignoreras under konvertering. Vi tar inte bort denna text, vi ignorerar den och överför den inte till utdatafilen. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel på avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Hämtar eller anger upplösning för bildrendering. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Detta attribut anger minimal bredd för grafisk banlinje. Om linjetjockleken är mindre än 1 px rundar Adobe Acrobat den till detta värde. Så kan detta attribut användas för att emulera detta beteende i HTML‑webbläsare. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Detta attribut aktiverar läget där textglyphs inte grupperas till ord och strängar. Detta läge möjliggör maximal precision vid placering av glyphs på sidan och kan användas för konvertering av dokument med musiknoter eller glyphs som ska placeras separat från varandra. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout‑attributet är true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Om attributet RenderTextAsImage är satt till true, blir texten från källan en bild i HTML. Kan vara användbart för att göra texten omarkerbar eller om HTML-texten inte renderas korrekt. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datasparning. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Indikerar att hela teckensnittet kommer att sparas, stöder endast True Type-teckensnitt. Som standard är SaveFullFont = false och konverteraren sparar en delmängd av det ursprungliga teckensnittet som behövs för att visa dokumentets text. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Detta attribut specificerar en sekventiell gruppering av glyfer och ord i strängar. Till exempel har taggar och ord olika ordning i konverterad HTML och du vill att de ska matcha. Denna parameter tillämpas på dokumentet endast när värdet för attributet FixedLayout är true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | När flersidigt läge är valt (dvs. 'SplitIntoPages' är 'true'), definierar detta attribut om en separat CSS-fil ska skapas för varje resulterande HTML-sida. Som standard är detta attribut false, så en stor gemensam CSS skapas för alla skapade sidor. Den sammanlagda storleken på alla CSS-filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS-fil, eftersom i det första fallet är CSS-klasser duplicerade i flera CSS-filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av att bearbeta varje HTML-sida separat i framtiden, och därför är storleken på CSS för varje enskild sida det mest kritiska problemet. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Hämtar eller anger flaggan som indikerar om varje sida i källdokumentet ska konverteras till ett eget mål‑HTML‑dokument, dvs. om det resulterande HTML‑dokumentet kommer att delas upp i flera HTML‑sidor. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Hämtar eller anger HTML‑sidans titel. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Flaggan för att kombinera bildfragment till en bild. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Om attributet UseZORder är satt till true läggs grafik och text till det resulterande HTML‑dokumentet enligt Z‑ordningen i det ursprungliga PDF‑dokumentet. Om detta attribut är false placeras all grafik som ett enda lager, vilket kan orsaka onödiga effekter för överlappande objekt. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction‑enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, varvid Save‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Denna parameter definierar de nödvändiga antialiasing‑åtgärderna under konvertering av sammansatta bakgrundsbilder från PDF till HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | När PDFtoHTML‑konverteraren genererar resultat‑CSS‑filer, skapas CSS‑klassnamn (t.ex. \".stl_01 {}\" … \".stl_NN {}\") och används i resultat‑CSS. Denna egenskap möjliggör att tvingande ange ett prefix för klassnamnen. Till exempel, om du vill att alla klassnamn ska börja med 'my_prefix_' (dvs. vara något i stil med 'my_prefix_1' … 'my_prefix_NNN'), tilldela helt enkelt 'my_prefix_' till denna egenskap före konverteringen. Om denna egenskap lämnas orörd (dvs. null som värde), kommer konverteraren att generera klassnamnen själv (det blir något som \".stl_01 {}\" … \".stl_NN {}\"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Detta fält kan innehålla en sparstrategi som ska användas (om den finns) under konvertering av Pdf till Html för hantering av sparande av CSS‑filer som är relaterade till det skapade HTML‑dokumentet som helhet eller till dess sidor (om flera HTML‑sidor genereras). Om du vill hantera CSS‑filen på ett specifikt sätt, skapa bara en relevant metod och tilldela en delegat skapad från den till denna egenskap. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor. Du kan tilldela den här egenskapen en delegat som skapats från en anpassad metod som implementerar bearbetning av en HTML‑sida (för att vara exakt – markup‑HTML, utan externa länkade filer om några) som skapades under konverteringen. I sådant fall kan bearbetning (t.ex. sparande av sidans HTML i en ström eller på disk) göras i den anpassade koden. I sådant fall måste alla nödvändiga åtgärder för att spara HTML‑sidan utföras i den medföljande metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo' : den kommer att signalera till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad kod fanns för bearbetning. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex. kan den användas för att visa en förloppsindikator eller meddelanden om det aktuella antalet bearbetade sidor. Exempel på hanterarens kod som visar förloppet i konsolen är: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade resursfiler (såsom bilder och teckensnitt) relaterade till noder i sparad HTML. Strategin måste bearbeta resurserna och returnera en sträng som representerar önskad URL för den sparade resursen i den genererade HTML‑koden. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Detta fält kan innehålla en anpassad metod som returnerar URL (eller URL‑mall om flersidig generering är på – se detaljer nedan) för den aktuella CSS‑filen som ska placeras i den genererade resultat‑HTML‑koden. T.ex. om du vill att konverteraren ska sätta en specifik URL istället för standard‑CSS‑filnamnet i den genererade CSS‑en, bör du helt enkelt skapa och tilldela den här egenskapen en metod som genererar önskad URL. Om flaggan 'SplitCssIntoPages' är satt, måste denna anpassade strategi (om någon) returnera inte den exakta URL‑en för CSS utan snarare en mallsträng som (efter ersättning av platshållaren med sidnummer via string.Format()-funktionen i konverteraren) kan omvandlas till en URL för den aktuella sidans CSS‑URL. Exempel på förväntade retursträngar i ett sådant fall är: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Lista över PDF‑inbäddade teckensnittsnamn som inte ska bäddas in i HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Definierar en speciell kodningsregel för att finjustera PDF‑avkodning för det aktuella dokumentet. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Definierar teckensnittssparläge som kommer att användas vid sparande av PDF till önskat format. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Ibland finns specifika krav på generering av HTML‑markup. Denna parameter definierar HTML‑förberedelselägen som kan användas under konvertering av PDF till HTML för att uppfylla sådana specifika krav. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i några trådar. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Ställer in lägesläge för bokstäver i ord i den resulterande HTML‑koden. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Detta attribut representerar en uppsättning inställningar som används för att rita en ram (om någon) i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan. I huvudsak handlar det om att visa sidans papperkanter, inte sidramen som refereras i PDF‑sidan själv. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Detta attribut representerar en uppsättning extra sidmarginaler (om några) i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Om attributet 'SplitOnPages=false', kommer hela HTML som representerar alla inmatade PDF‑sidor att placeras i en stor resultat‑HTML‑fil. Detta flagga definierar huruvida resultat‑HTML ska genereras på ett sätt så att flödet av områden som representerar PDF‑sidor i resultat‑HTML beror på skärmupplösningen hos visaren. Anta att skärmbredden på visarsidan är tillräckligt stor för att placera 2 eller fler sidor nära varandra i horisontell riktning. Om detta flagga sätts till true, kommer denna möjlighet att användas (så många sidor som möjligt visas i horisontell riktning nära varandra, sedan visas nästa horisontella grupp av sidor under den första). Annars flödar sidorna på följande sätt: nästa sida placeras alltid under föregående. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Den definierar huruvida refererade filer (HTML, Fonts, Images, CSS‑filer) kommer att bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter. |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Konverterad PDF kan innehålla rasterbilder. Denna parameter definierar hur de ska hanteras under konvertering av PDF till HTML. |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Definierar huruvida tomt område högst upp och längst ner utan något innehåll (om något) ska tas bort i den skapade HTML‑filen. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF kan innehålla texter som skuggas av andra element (t.ex. av bilder) men som kan markeras till urklipp i Acrobat Reader (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren huruvida vi ska spara sådana texter som transparenta markerbara texter i resultat‑HTML för att efterlikna Acrobat Readers beteende (annars sparas sådana texter vanligtvis som dolda, ej tillgängliga för kopiering till urklipp). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF kan innehålla transparenta texter som kan markeras till urklipp (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren huruvida vi ska spara sådana texter som transparenta markerbara texter i resultat‑HTML. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Hämtar eller anger sökvägen till den katalog där eventuella bilder måste sparas om de påträffas under sparande av dokumentet som HTML. Om parametern är tom eller null sparas bildfiler (om några) tillsammans med övriga filer som länkas till HTML. Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den relevanta bildfilen. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Hämtar eller anger sökvägen till den katalog där endast SVG‑bilder måste sparas om de påträffas under sparande av dokumentet som HTML. Om parametern är tom eller null sparas SVG‑filer (om några) tillsammans med övriga bildfiler (nära utdatafilen) eller i en särskild bildmapp (om den anges i alternativet SpecialImagesFolderIfAny). Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den relevanta bildfilen. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF‑filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS‑format) ibland generera synliga gränser mellan delar av bakgrundsbilder, eftersom deras teknik för kantutjämning (anti‑aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. ATTENTION! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF i sig innehåller inga understrykningsmarkörer för texter. Det efterliknas med en linje placerad under texten. Detta alternativ låter konverteraren försöka gissa att denna eller den linjen är en texts understrykning och placera denna information i CSS istället för att rita understrykningen grafiskt. |

## Exempel

Följande exempel visar hur man konverterar en PDF‑fil till en HTML‑fil.

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Sökvägen till din PDF‑fil.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// Sökvägen till utdata‑HTML‑filen.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initiera HtmlSaveOptions \t
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Spara HTML‑fil
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

### Se även

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


