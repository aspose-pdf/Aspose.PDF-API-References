---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptions klass. Spara alternativ för export till Html-format
type: docs
weight: 5560
url: /sv/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions klass

Spara alternativ för export till Html-format

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Initierar en ny instans av `HtmlSaveOptions` klassen. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Initierar en ny instans av `HtmlSaveOptions` klassen. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Initierar en ny instans av `HtmlSaveOptions` klassen. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Initierar en ny instans av `HtmlSaveOptions` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Definierar batchstorlek om batchkonvertering är tillämplig för käll- och destinationsformatpar. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Hämtar eller ställer in ett booleanvärde som indikerar om teckensnittsglypher kommer att cachas medan aps-sidor förbereds. Förbättrar prestanda för konvertering av pdf till andra format men ökar minnesanvändningen. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Hämtar eller ställer in ett booleanvärde som indikerar om Response-objektet kommer att stängas efter att dokumentet har sparats i svaret. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Hämtar eller ställer in flaggan som indikerar om funna SVG-grafik (om någon) kommer att komprimeras (zipas) till SVGZ-format under sparande |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Om attributet ConvertMarkedContentToLayers är inställt på true kommer alla element inuti en PDF markerad innehåll (lager) att placeras i en HTML div med "data-pdflayer" attribut som specificerar ett lagernamn. Detta lagernamn kommer att extraheras från valfria egenskaper för PDF markerat innehåll. Om detta attribut är false (som standard) kommer inga lager att skapas från PDF markerat innehåll. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Anger namnet på ett installerat teckensnitt som används för att ersätta något dokumentteckensnitt som inte är inbäddat och inte installerat i systemet. Om null används standardersättningsteckensnitt. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Hämtar eller ställer in [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Med denna egenskap kan du uttryckligen definiera vilka sidor av dokumentet som ska konverteras. Sidor i denna lista måste ha 1-baserade nummer. D.v.s. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]) Ordningen av sidor i denna lista påverkar inte deras ordning i resultat HTML-sidan (sidorna kommer alltid att gå i den ordning de finns i käll-PDF). Om denna lista är null (som den är som standard), kommer alla sidor att konverteras. Om något sidnummer i denna lista går utanför intervallet av befintliga sidor (1-[amountOfPagesInDocument]) kommer ett undantag att kastas. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Detta attribut aktiverar funktionalitet för att extrahera bild eller text för PDF-dokument med OCR-sublager. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om HTML skapas som fast layout. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Detta attribut specificerar full bredd på stycke text för Flödesläge, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Teckensnittskällor för för-sparade teckensnitt. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Text med angiven storlek eller mindre kommer att ignoreras under konvertering. Vi tar inte bort denna text, vi ignorerar den och överför den inte till utdatafilen |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Hämtar eller ställer in indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras. true - betyder att fel av avsaknad av teckensnitt kommer att ignoreras. Textsegment som hänvisar till felaktiga resurser kommer att hoppas över under bearbetning. false som standard |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Hämtar eller ställer in upplösning för bildrendering. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Detta attribut ställer in minimal bredd på grafisk väg linje. Om tjockleken på linjen är mindre än 1px rundar Adobe Acrobat det till detta värde. Så detta attribut kan användas för att efterlikna detta beteende för HTML-webbläsare. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Detta attribut aktiverar läget när textglypher inte kommer att grupperas i ord och strängar. Detta läge gör att maximal precision kan bibehållas under positionering av glypher på sidan och kan användas för konvertering av dokument med musiknoter eller glypher som ska placeras separat från varandra. Denna parameter kommer att tillämpas på dokumentet endast när värdet av attributet FixedLayout är true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Om attributet RenderTextAsImage är inställt på true, blir texten från källan en bild i HTML. Kan vara användbart för att göra texten icke-valbar eller om HTML-texten inte renderas korrekt. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format för datalagring. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Indikerar att hela teckensnittet kommer att sparas, stöder endast True Type Fonts. Som standard är SaveFullFont = false och konverteraren sparar delmängden av det ursprungliga teckensnittet som behövs för att visa texten i dokumentet. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Detta attribut specificerar en sekventiell gruppering av glypher och ord i strängar. Till exempel har taggar och ord olika ordning i den konverterade HTML och du vill att de ska matcha. Denna parameter kommer att tillämpas på dokumentet endast när värdet av attributet FixedLayout är true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | När multipage-läget är valt (d.v.s. 'SplitIntoPages' är 'true'), definierar detta attribut om en separat CSS-fil ska skapas för varje resultat HTML-sida. Som standard är detta attribut false, så en stor gemensam CSS kommer att skapas för alla skapade sidor. Sammanlagd storlek av alla CSS:er som genereras i detta läge (en CSS per sida) är vanligtvis mycket mer än storleken på en stor CSS-fil, eftersom i det tidigare fallet är CSS-klasser dubbletter i flera CSS-filer för varje sida. Så, denna inställning är sämre att använda endast när du är intresserad av framtida bearbetning av varje HTML-sida oberoende, och därför är storleken på CSS för varje enskild sida det mest kritiska problemet. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Hämtar eller ställer in flaggan som indikerar om varje sida av källdokumentet kommer att konverteras till sitt eget mål HTML-dokument, d.v.s. om resultat HTML kommer att delas upp i flera HTML-sidor. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Hämtar eller ställer in HTML-sidans titel. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Flaggan för att kombinera bildfragment till en bild. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Om attributet UseZOrder är inställt på true, läggs grafik och text till den resulterande HTML-dokumentet enligt Z-ordningen i det ursprungliga PDF-dokumentet. Om detta attribut är false placeras all grafik som ett enda lager vilket kan orsaka vissa onödiga effekter för överlappande objekt. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och spara operationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall spara operationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Denna parameter definierar nödvändiga antialiasingåtgärder under konvertering av sammansatta bakgrundsbilder från PDF till HTML |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | När PDFtoHTML-konverteraren genererar resultat CSS:er, genereras CSS-klassnamn (något som ".stl_01 {}" ... ".stl_NN {}") och används i resultat CSS. Denna egenskap tillåter att tvinga klassnamn prefix. Till exempel, om du vill att alla klassnamn ska börja med 'my_prefix_' (d.v.s. vara något som 'my_prefix_1' ... 'my_prefix_NNN'), tilldela bara 'my_prefix_' till denna egenskap innan konvertering. Om denna egenskap lämnas orörd (d.v.s. null lämnas som värde), kommer konverteraren att generera klassnamn själv (det kommer att vara något som ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Detta fält kan innehålla sparstrategi som måste användas (om den finns) under konvertering av Pdf till Html för hantering av sparande av CSS:er relaterade till det skapade HTML-dokumentet som helhet eller till dess sidor (om flera HTML-sidor genereras). Om du vill hantera CSS-filen på något specifikt sätt, vänligen skapa relevant metod och tilldela delegat skapad från den till denna egenskap. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Resultatet av konverteringen kan innehålla en eller flera HTML-sidor. Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar bearbetning av en HTML-sida (för att vara exakt - markup-HTML, utan externa länkade filer om några) som skapades under konverteringen. I sådana fall kan bearbetning (som att spara sidans HTML i ström eller disk) göras i den anpassade koden. I sådana fall måste alla nödvändiga åtgärder för att spara HTML-sidan vidtas i koden för den tillhandahållna metoden, eftersom sparande av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen ställ in i den anpassade koden flaggan 'CustomProcessingCancelled' av 'htmlSavingInfo' parameterns variabel: det kommer att signalera till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv på samma sätt som om det inte fanns någon extern anpassad kod för bearbetning. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Denna hanterare kan användas för att hantera konverteringsframstegshändelser, t.ex. den kan användas för att visa en framstegsindikator eller meddelanden om aktuellt antal bearbetade sidor, exempel på hanterarens kod som visar framsteg på konsolen är: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Detta fält kan innehålla sparstrategi som måste användas (om den finns) under konvertering för anpassad hantering av skapade referensresursfiler (som bilder och teckensnitt) relaterade till noder av sparad HTML. Den strategin måste bearbeta resurser och returnera en sträng som representerar önskad URL för den sparade resursen i den genererade HTML. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Detta fält kan innehålla en anpassad metod som returnerar URL (eller URL-mall om multipage-generering är på - se detaljer nedan) för den aktuella CSS som den ska sättas in i den genererade resultat HTML. T.ex. om du vill att konverteraren ska sätta en specifik URL istället för standard CSS-filnamn i den genererade CSS, bör du bara skapa och sätta in denna egenskap metod som genererar önskad URL. Om flaggan 'SplitCssIntoPages' är inställd, måste denna anpassade strategi (om någon) returnera inte exakt URL för CSS utan snarare en mallsträng som (efter substitution av platshållaren med sidnummer med string.Format() funktionen inuti konverteraren) kan lösas till URL för denna eller den sidans CSS' URL. Exempel på förväntad retursträng i sådana fall är: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Lista över PDF inbäddade teckensnittsnamn som inte ska inbäddas i HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Definierar kodningsspecifik regel för att justera PDF-avkodning för det aktuella dokumentet |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Definierar teckensnittssparläge som kommer att användas under sparande av PDF till önskat format |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Ibland finns specifika krav på generation av HTML-markup. Denna parameter definierar HTML-förberedelselägen som kan användas under konvertering av PDF till HTML för att matcha sådana specifika krav. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Bearbeta sidor i flera trådar. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Ställer in läget för positionering av bokstäver i ord i resultat HTML |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Detta attribut representerar en uppsättning inställningar som används för att rita kant (om någon) i det resulterande HTML-dokumentet runt området som representerar käll-PDF-sidan. I huvudsak handlar det om att visa sidans papperskanter, inte sidgränsen som refereras i PDF-sidan själv. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Detta attribut representerar en uppsättning extra sidmarginal (om någon) i det resulterande HTML-dokumentet runt området som representerar käll-PDF-sidan. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Om attributet 'SplitOnPages=false', kommer hela HTML som representerar alla ingående PDF-sidor att placeras i en stor resultat HTML-fil. Denna flagga definierar om resultat HTML kommer att genereras på ett sådant sätt att flödet av områden som representerar PDF-sidor i resultat HTML kommer att bero på skärmupplösningen hos visaren. Anta att bredden på skärmen på visarsidan är tillräckligt stor för att placera 2 eller fler sidor bredvid varandra i horisontell riktning. Om denna flagga är inställd på true, kommer denna möjlighet att användas (så många sidor som möjligt kommer att visas i horisontell riktning bredvid varandra, nästa horisontella grupp av sidor kommer att visas under den första). Annars kommer sidorna att flöda på följande sätt: nästa sida går alltid under den föregående. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Det definierar om refererade filer (HTML, Teckensnitt, Bilder, CSS) kommer att inbäddas i huvud HTML-filen eller genereras som separata binära enheter |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Den konverterade PDF:en kan innehålla rasterbilder. Denna parameter definierar hur de ska hanteras under konvertering av PDF till HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Definierar om i den skapade HTML kommer att tas bort övre och nedre tomt område utan något innehåll (om något). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF kan innehålla texter som skuggas av andra element (t.ex. av bilder) men kan väljas till urklipp i Acrobat Reader (vanligtvis händer det när dokumentet innehåller bilder och OCR:ade texter som extraherats från det). Denna inställning talar om för konverteraren om vi behöver spara sådana texter som transparenta valbara texter i resultat HTML för att efterlikna beteendet hos Acrobat Reader (annars sparas sådana texter vanligtvis som dolda, inte tillgängliga för kopiering till urklipp) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF kan innehålla transparenta texter som kan väljas till urklipp (vanligtvis händer det när dokumentet innehåller bilder och OCR:ade texter som extraherats från det). Denna inställning talar om för konverteraren om vi behöver spara sådana texter som transparenta valbara texter i resultat HTML |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Hämtar eller ställer in sökväg till katalogen där alla bilder måste sparas om de stöter på under sparande av dokumentet som HTML. Om parametern är tom eller null kommer bildfiler (om några) att sparas tillsammans med andra filer kopplade till HTML. Det påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta relevant bildfil. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Hämtar eller ställer in sökväg till katalogen där endast SVG-bilder måste sparas om de stöter på under sparande av dokumentet som HTML. Om parametern är tom eller null kommer SVG-filer (om några) att sparas tillsammans med andra bildfiler (nära utdatafilen) eller i en speciell mapp för bilder (om det anges i alternativet SpecialImagesFolderIfAny). Det påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta relevant bildfil. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Ibland innehåller PDF:er bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera samma kakelbakgrundsbilder placerade bredvid varandra. I sådana fall genererar målfomatens renderare (t.ex. MsWord för DOCS-format) ibland synliga gränser mellan delarna av bakgrundsbilderna, eftersom deras tekniker för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som att det exporterade dokumentet innehåller sådana synliga gränser mellan delarna av samma bakgrundsbilder, vänligen försök använda denna inställning för att bli av med den oönskade effekten. OBS! Denna optimering av kvalitet saktar vanligtvis ner konverteringen avsevärt, så använd denna alternativ endast när det verkligen är nödvändigt. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF:en innehåller inte understrykningstecken för texter. Det emuleras med en linje som ligger under texten. Detta alternativ gör att konverteraren kan försöka gissa att denna eller den linjen är en texts understrykning och sätta denna information i CSS istället för att rita understrykningen grafiskt |

## Exempel

Följande exempel visar hur man konverterar en PDF-fil till en HTML-fil

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

### Se Även

* klass [UnifiedSaveOptions](../unifiedsaveoptions/)
* gränssnitt [IPageSetOptions](../ipagesetoptions/)
* gränssnitt [IPipelineOptions](../ipipelineoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)