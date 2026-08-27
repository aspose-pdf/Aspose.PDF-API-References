---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Spara alternativ för export till HTML‑format."
type: docs
weight: 1990
url: /sv/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

Spara alternativ för export till HTML‑format.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | Initierar en ny instans av HtmlSaveOptions-klassen. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | Initierar en ny instans av {@code HtmlSaveOptions}-klassen. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | Initierar en ny instans av HtmlSaveOptions-klassen. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | Initierar en ny instans av HtmlSaveOptions-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | Om attributet 'SplitOnPages=false', då kommer hela HTML som representerar alla inmatade PDF‑sidor inte att delas upp i separata HTML‑sidor, utan placeras i en stor resultat‑HTML‑fil. Men varje käll‑PDF‑sida kommer att representeras med sitt eget rektangelområde i HTML (om nödvändigt kan dessa områden ramas in för att visa sidans kant med det speciella attributet 'PageBorderIfAny'). Denna parameter definierar bredden på marginalen som tvingas lämnas runt de utdata‑HTML‑områden som representerar sidorna i källdokumentet. I grund och botten definierar den garanterat intervall mellan HTML‑representationer av PDF \"paper\"‑sidor i en sådan konverteringsmetod. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | Denna parameter definierar nödvändiga antialiasing‑åtgärder under konvertering av sammansatta bakgrundsbilder från PDF till HTML. |
| [getBatchSize](#getBatchSize--) | Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | När PDFtoHTML‑konverteraren genererar resultat‑CSS‑filer, skapas CSS‑klassnamn (något i stil med \".stl_01 {}\" … \".stl_NN {}\") och används i resultat‑CSS. Denna egenskap tillåter att tvinga fram ett prefix för klassnamn. Till exempel, om du vill att alla klassnamn ska börja med 'my_prefix_' (dvs. vara något i stil med 'my_prefix_1' … 'my_prefix_NNN'), tilldela bara 'my_prefix_' till denna egenskap före konverteringen. Om egenskapen lämnas orörd (dvs. null lämnas som värde), kommer konverteraren att generera klassnamnen själv (det blir något i stil med \".stl_01 {}\" … \".stl_NN {}\"). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konvertering av Pdf till Html för hantering av sparande av CSS‑filer som är relaterade till det skapade HTML‑dokumentet som helhet eller till dess sidor (om flera HTML‑sidor genereras). Om du vill hantera CSS‑filen på ett specifikt sätt, skapa bara en relevant metod och tilldela en delegat skapad från den till denna egenskap. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor. Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar bearbetning av en HTML‑sida (mer exakt – markup‑HTML, utan externa länkade filer om några) som skapades under konverteringen. I så fall kan bearbetning (t.ex. sparande av sidans HTML i en ström eller på disk) utföras i den anpassade koden. I sådant fall måste alla nödvändiga åtgärder för att spara HTML‑sidan utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens egen kod, inte i anpassad kod, sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo'‑parameter: den kommer att signalera till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad kod fanns för bearbetning. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Denna hanterare kan användas för att hantera konverteringsförloppshändelser t.ex. den kan användas för att visa en förloppsindikator eller meddelanden om det aktuella antalet bearbetade sidor, exempel på hanterarens kod som visar förloppet i konsolen är : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade resursfiler (som bilder och teckensnitt) relaterade till noder i sparad HTML. Strategin måste bearbeta resurserna och returnera en sträng som representerar önskad URL för den sparade resursen i den genererade HTML. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | Detta fält kan innehålla en anpassad metod som returnerar URL (eller URL‑mall om flersidig generering är på – se detaljer nedan) för den aktuella CSS‑filen som ska placeras i den genererade resultat‑HTML‑en. T.ex. om du vill att konverteraren ska sätta en specifik URL istället för standard‑CSS‑filnamnet i den genererade CSS‑en, bör du bara skapa och tilldela den här egenskapen en metod som genererar önskad URL. Om flaggan 'SplitCssIntoPages' är satt, måste denna anpassade strategi (om någon) returnera en mallsträng snarare än en exakt URL för CSS‑en, så att (efter ersättning av platshållaren med sidnummer med String.Format()-funktionen i konverteraren) den kan omvandlas till en URL för den aktuella sidans CSS‑URL. Exempel på förväntade retursträngar i sådant fall är: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 } ' ) |
| [getDefaultFontName](#getDefaultFontName--) | Anger namnet på ett installerat teckensnitt som används för att ersätta alla dokumentteckensnitt som inte är inbäddade och inte är installerade i systemet. Om null används standardersättningsteckensnittet. |
| [getDocumentType](#getDocumentType--) | Hämtar {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | Lista över PDF‑inbäddade teckensnittsnamn som inte ska bäddas in i HTML. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1-baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i den resulterande HTML‑sidan/-sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll‑PDF‑filen. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | Detta attribut specificerar fullbreddstext för stycket i flödesläge, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Definierar en speciell kodningsregel för att finjustera PDF‑avkodning för det aktuella dokumentet |
| [getFontSavingMode](#getFontSavingMode--) | Definierar teckensnittssparningsläge som kommer att användas vid sparande av PDF till önskat format |
| [getFontSources](#getFontSources--) | <p> Teckensnittskällor för förhandssparade teckensnitt. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | Ibland finns specifika krav på generering av HTML‑markup. Denna parameter definierar HTML‑förberedelselägen som kan användas vid konvertering av PDF till HTML för att uppfylla sådana specifika krav. |
| [getImageResolution](#getImageResolution--) | Hämtar eller anger upplösning för bildrendering. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Anger läge för placering av bokstäver i ord i resulterande HTML |
| [getMinimalLineWidth](#getMinimalLineWidth--) | Detta attribut anger minimal bredd för grafisk banlinje. Om linjetjockleken är mindre än 1 px rundar Adobe Acrobat den till detta värde. Så kan detta attribut användas för att emulera detta beteende i HTML‑webbläsare. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | Detta attribut representerar en uppsättning inställningar som används för att rita en ram (om någon) i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan. I huvudsak gäller det visning av sidans papperkanter, inte sidramen som refereras i PDF‑sidan själv. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | Detta attribut representerar en uppsättning extra sidmarginaler (om några) i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | Det definierar om refererade filer (HTML, teckensnitt, bilder, CSS‑filer) ska bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | Konverterad PDF kan innehålla rasterbilder. Denna parameter definierar hur de ska hanteras vid konvertering av PDF till HTML |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Hämtar eller anger sökväg till katalog där eventuella bilder som påträffas vid sparande av dokumentet som HTML ska sparas. Om parametern är tom eller null sparas bildfiler (om några) tillsammans med övriga filer som länkas till HTML. Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den aktuella bildfilen. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Hämtar eller anger sökväg till katalog där endast SVG‑bilder ska sparas om de påträffas vid sparande av dokumentet som HTML. Om parametern är tom eller null sparas SVG‑filer (om några) tillsammans med övriga bildfiler (i närheten av utdatafilen) eller i en särskild bildmapp (om den anges i alternativet SpecialImagesFolderIfAny). Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den aktuella bildfilen. |
| [getTitle](#getTitle--) | Hämtar eller anger HTML‑sidans titel. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Hämtar flaggan som indikerar om hittad SVG‑grafik (om någon) kommer att komprimeras (zippas) till SVGZ‑format vid sparande. Värde: {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | Om attributet ConvertMarkedContentToLayers är satt till true placeras alla element inom ett PDF‑markerat innehåll (lager) i en HTML‑div med attributet "data-pdflayer" som specificerar ett lagernamn. Detta lagernamn hämtas från valfria egenskaper för PDF‑markerat innehåll. Om detta attribut är false (standard) skapas inga lager från PDF‑markerat innehåll. |
| [isFixedLayout](#isFixedLayout--) | Hämtar ett värde som indikerar om HTML‑en skapas som fast layout. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel för avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | Om attributet 'SplitOnPages=false', placeras hela HTML‑en som representerar alla inmatade PDF‑sidor i en stor resultat‑HTML‑fil. Denna flagga bestämmer om resultat‑HTML genereras på ett sätt där flödet av områden som representerar PDF‑sidor beror på skärmupplösningen hos visaren. Anta att skärmbredden på visarsidan är tillräckligt stor för att placera två eller fler sidor bredvid varandra horisontellt. Om flaggan är satt till true utnyttjas detta (så många sidor som möjligt visas horisontellt bredvid varandra, och nästa horisontella grupp av sidor visas under den första). Annars flödar sidorna så att nästa sida alltid placeras under föregående. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | Detta attribut aktiverar läget där textglyfer inte grupperas till ord och strängar. Detta läge möjliggör maximal precision vid placering av glyfer på sidan och kan användas för konvertering av dokument med musiknotationer eller glyfer som ska placeras separat från varandra. Parametern tillämpas på dokumentet endast när värdet för attributet FixedLayout är true. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Definierar om tomt område högst upp och längst ner utan innehåll (om sådant finns) ska tas bort i den skapade HTML‑en. |
| [isRenderTextAsImage](#isRenderTextAsImage--) | Om attributet RenderTextAsImage är satt till true blir texten från källan en bild i HTML. Detta kan vara användbart för att göra texten omarkerbar eller när HTML‑text inte renderas korrekt. |
| [isSaveFullFont](#isSaveFullFont--) | Indikerar att hela teckensnittet sparas, stöder endast True Type‑teckensnitt. Som standard är SaveFullFont = false och konverteraren sparar en delmängd av det ursprungliga teckensnittet som behövs för att visa dokumentets text. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | Pdf kan innehålla texter som skuggas av andra element (t.ex. av bilder) men som kan markeras till urklipp i Acrobat Reader (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren om sådana texter ska sparas som transparenta, markerbara texter i resultat‑HTML för att efterlikna Acrobat Readers beteende (annars sparas sådana texter vanligtvis som dolda och kan inte kopieras till urklipp). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Pdf kan innehålla transparenta texter som kan markeras till urklipp (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren om sådana texter ska sparas som transparenta, markerbara texter i resultat‑HTML. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | Detta attribut specificerar en sekventiell gruppering av glyfer och ord i strängar. Till exempel har taggar och ord olika ordning i konverterad HTML och du vill att de ska matcha. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout-attributet är sant. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | När flersidigt läge är valt (dvs. 'SplitIntoPages' är 'true'), definierar detta attribut om en separat CSS-fil ska skapas för varje resulterande HTML-sida. Som standard är detta attribut falskt, så en stor gemensam CSS skapas för alla skapade sidor. Den sammanlagda storleken på alla CSS-filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS-fil, eftersom i det första fallet är CSS-klasser duplicerade i flera CSS-filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML-sida oberoende, och därmed är storleken på CSS för varje enskild sida den mest kritiska frågan. |
| [isSplitIntoPages](#isSplitIntoPages--) | Hämtar flaggan som indikerar om varje sida i källdokumentet kommer att konverteras till ett eget mål‑HTML‑dokument, d.v.s. om resulterande HTML kommer att delas upp i flera HTML‑sidor. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF-filen i sig innehåller inga understrykningsmarkörer för text. Det efterliknas med en linje placerad under texten. Detta alternativ låter konverteraren försöka gissa att en viss linje är en texts understrykning och placera denna information i CSS istället för att rita understrykningen grafiskt. |
| [isUseZOrder](#isUseZOrder--) | Om attributet UseZORder är satt till true läggs grafik och text till det resulterande HTML-dokumentet enligt Z‑ordningen i det ursprungliga PDF-dokumentet. Om detta attribut är false placeras all grafik som ett enda lager, vilket kan orsaka onödiga effekter för överlappande objekt. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | Om attributet 'SplitOnPages=false', då kommer hela HTML som representerar alla inmatade PDF‑sidor inte att delas upp i separata HTML‑sidor, utan placeras i en stor resultat‑HTML‑fil. Men varje käll‑PDF‑sida kommer att representeras med sitt eget rektangelområde i HTML (om nödvändigt kan dessa områden ramas in för att visa sidans kant med det speciella attributet 'PageBorderIfAny'). Denna parameter definierar bredden på marginalen som tvingas lämnas runt de utdata‑HTML‑områden som representerar sidorna i källdokumentet. I grund och botten definierar den garanterat intervall mellan HTML‑representationer av PDF \"paper\"‑sidor i en sådan konverteringsmetod. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | Denna parameter definierar nödvändiga antialiasing‑åtgärder under konvertering av sammansatta bakgrundsbilder från PDF till HTML. |
| [setBatchSize](#setBatchSize-int-) | Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Ställer in flaggan som indikerar om hittad SVG-grafik (om någon) kommer att komprimeras (zippas) till SVGZ-format vid sparande. Värde: {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | Om attributet ConvertMarkedContentToLayers är satt till true placeras alla element inom ett PDF‑markerat innehåll (lager) i en HTML‑div med attributet "data-pdflayer" som specificerar ett lagernamn. Detta lagernamn hämtas från valfria egenskaper för PDF‑markerat innehåll. Om detta attribut är false (standard) skapas inga lager från PDF‑markerat innehåll. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | När PDFtoHTML‑konverteraren genererar resultat‑CSS‑filer, skapas CSS‑klassnamn (något i stil med \".stl_01 {}\" … \".stl_NN {}\") och används i resultat‑CSS. Denna egenskap tillåter att tvinga fram ett prefix för klassnamn. Till exempel, om du vill att alla klassnamn ska börja med 'my_prefix_' (dvs. vara något i stil med 'my_prefix_1' … 'my_prefix_NNN'), tilldela bara 'my_prefix_' till denna egenskap före konverteringen. Om egenskapen lämnas orörd (dvs. null lämnas som värde), kommer konverteraren att generera klassnamnen själv (det blir något i stil med \".stl_01 {}\" … \".stl_NN {}\"). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konvertering av Pdf till Html för hantering av sparande av CSS‑filer som är relaterade till det skapade HTML‑dokumentet som helhet eller till dess sidor (om flera HTML‑sidor genereras). Om du vill hantera CSS‑filen på ett specifikt sätt, skapa bara en relevant metod och tilldela en delegat skapad från den till denna egenskap. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor. Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar bearbetning av en HTML‑sida (mer exakt – markup‑HTML, utan externa länkade filer om några) som skapades under konverteringen. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Detta fält kan innehålla en sparstrategi som måste användas (om närvarande) under konverteringen för anpassad hantering av skapade refererade resursfiler (som bilder och typsnitt) som är relaterade till noder i sparad HTML. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Detta fält kan innehålla en anpassad metod som returnerar URL (eller URL‑mall om flersidig generering är på – se detaljer nedan) för den aktuella CSS‑filen som ska placeras i den genererade resultat‑HTML‑en. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Anger namnet på ett installerat teckensnitt som används för att ersätta alla dokumentteckensnitt som inte är inbäddade och inte är installerade i systemet. Om null används standardersättningsteckensnittet. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | Ställer in {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | Lista över PDF‑inbäddade teckensnittsnamn som inte ska bäddas in i HTML. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1-baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i den resulterande HTML‑sidan/-sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll‑PDF‑filen. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag. |
| [setFixedLayout](#setFixedLayout-boolean-) | Ställer in ett värde som indikerar om HTML‑en skapas som fast layout. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | Detta attribut specificerar fullbreddstext för stycket i flödesläge, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Definierar en speciell kodningsregel för att finjustera PDF‑avkodning för det aktuella dokumentet |
| [setFontSavingMode](#setFontSavingMode-int-) | Definierar teckensnittssparningsläge som kommer att användas vid sparande av PDF till önskat format |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | Ibland finns specifika krav på generering av HTML‑markup. Denna parameter definierar HTML‑förberedelselägen som kan användas vid konvertering av PDF till HTML för att uppfylla sådana specifika krav. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel för avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [setImageResolution](#setImageResolution-int-) | Hämtar eller anger upplösning för bildrendering. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Anger läge för placering av bokstäver i ord i resulterande HTML |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | Detta attribut anger minimal bredd för grafisk banlinje. Om linjetjockleken är mindre än 1 px rundar Adobe Acrobat den till detta värde. Så kan detta attribut användas för att emulera detta beteende i HTML‑webbläsare. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Detta attribut representerar en uppsättning inställningar som används för att rita en ram (om någon) i resultat‑HTML‑dokumentet runt det område som representerar käll‑PDF‑sidan. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Detta attribut representerar en uppsättning extra sidmarginaler (om några) i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Om attributet 'SplitOnPages=false', placeras hela HTML‑en som representerar alla inmatade PDF‑sidor i en stor resultat‑HTML‑fil. Denna flagga bestämmer om resultat‑HTML genereras på ett sätt där flödet av områden som representerar PDF‑sidor beror på skärmupplösningen hos visaren. Anta att skärmbredden på visarsidan är tillräckligt stor för att placera två eller fler sidor bredvid varandra horisontellt. Om flaggan är satt till true utnyttjas detta (så många sidor som möjligt visas horisontellt bredvid varandra, och nästa horisontella grupp av sidor visas under den första). Annars flödar sidorna så att nästa sida alltid placeras under föregående. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | Det definierar om refererade filer (HTML, teckensnitt, bilder, CSS‑filer) ska bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | Detta attribut aktiverar läget där textglyfer inte grupperas till ord och strängar. Detta läge möjliggör maximal precision vid placering av glyfer på sidan och kan användas för konvertering av dokument med musiknotationer eller glyfer som ska placeras separat från varandra. Parametern tillämpas på dokumentet endast när värdet för attributet FixedLayout är true. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | Konverterad PDF kan innehålla rasterbilder. Denna parameter definierar hur de ska hanteras vid konvertering av PDF till HTML |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Definierar om tomt område högst upp och längst ner utan innehåll (om sådant finns) ska tas bort i den skapade HTML‑en. |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | Om attributet RenderTextAsImage är satt till true blir texten från källan en bild i HTML. Detta kan vara användbart för att göra texten omarkerbar eller när HTML‑text inte renderas korrekt. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Indikerar att hela teckensnittet sparas, stöder endast True Type‑teckensnitt. Som standard är SaveFullFont = false och konverteraren sparar en delmängd av det ursprungliga teckensnittet som behövs för att visa dokumentets text. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Pdf kan innehålla texter som skuggas av andra element (t.ex. av bilder) men som kan markeras till urklipp i Acrobat Reader (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren om sådana texter ska sparas som transparenta, markerbara texter i resultat‑HTML för att efterlikna Acrobat Readers beteende (annars sparas sådana texter vanligtvis som dolda och kan inte kopieras till urklipp). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Pdf kan innehålla transparenta texter som kan markeras till urklipp (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren om sådana texter ska sparas som transparenta, markerbara texter i resultat‑HTML. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | Detta attribut specificerar en sekventiell gruppering av glyfer och ord i strängar. Till exempel har taggar och ord olika ordning i konverterad HTML och du vill att de ska matcha. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout-attributet är sant. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Hämtar eller anger sökväg till katalog där eventuella bilder som påträffas vid sparande av dokumentet som HTML ska sparas. Om parametern är tom eller null sparas bildfiler (om några) tillsammans med övriga filer som länkas till HTML. Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den aktuella bildfilen. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Hämtar eller anger sökväg till katalog där endast SVG‑bilder ska sparas om de påträffas vid sparande av dokumentet som HTML. Om parametern är tom eller null sparas SVG‑filer (om några) tillsammans med övriga bildfiler (i närheten av utdatafilen) eller i en särskild bildmapp (om den anges i alternativet SpecialImagesFolderIfAny). Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den aktuella bildfilen. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | När flersidigt läge är valt (dvs. 'SplitIntoPages' är 'true'), definierar detta attribut om en separat CSS-fil ska skapas för varje resulterande HTML-sida. Som standard är detta attribut falskt, så en stor gemensam CSS skapas för alla skapade sidor. Den sammanlagda storleken på alla CSS-filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS-fil, eftersom i det första fallet är CSS-klasser duplicerade i flera CSS-filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML-sida oberoende, och därmed är storleken på CSS för varje enskild sida den mest kritiska frågan. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Ställer in flaggan som indikerar om varje sida i källdokumentet kommer att konverteras till ett eget mål‑HTML‑dokument, d.v.s. om resulterande HTML kommer att delas upp i flera HTML‑sidor. |
| [setTitle](#setTitle-java.lang.String-) | Hämtar eller anger HTML‑sidans titel. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF-filen i sig innehåller inga understrykningsmarkörer för text. Det efterliknas med en linje placerad under texten. Detta alternativ låter konverteraren försöka gissa att en viss linje är en texts understrykning och placera denna information i CSS istället för att rita understrykningen grafiskt. |
| [setUseZOrder](#setUseZOrder-boolean-) | Om attributet UseZORder är satt till true läggs grafik och text till det resulterande HTML-dokumentet enligt Z‑ordningen i det ursprungliga PDF-dokumentet. Om detta attribut är false placeras all grafik som ett enda lager, vilket kan orsaka onödiga effekter för överlappande objekt. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

Initierar en ny instans av HtmlSaveOptions-klassen.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

Initierar en ny instans av {@code HtmlSaveOptions}-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixedLayout |  | booleskt värde |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
Initierar en ny instans av HtmlSaveOptions-klassen.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
Initierar en ny instans av HtmlSaveOptions-klassen.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

Om attributet 'SplitOnPages=false', då kommer hela HTML som representerar alla inmatade PDF‑sidor inte att delas upp i separata HTML‑sidor, utan placeras i en stor resultat‑HTML‑fil. Men varje käll‑PDF‑sida kommer att representeras med sitt eget rektangelområde i HTML (om nödvändigt kan dessa områden ramas in för att visa sidans kant med det speciella attributet 'PageBorderIfAny'). Denna parameter definierar bredden på marginalen som tvingas lämnas runt de utdata‑HTML‑områden som representerar sidorna i källdokumentet. I grund och botten definierar den garanterat intervall mellan HTML‑representationer av PDF \"paper\"‑sidor i en sådan konverteringsmetod.

**Returns:**
int‑värde @deprecated AdditionalMarginWidthInPoints är föråldrat, vänligen använd PageMarginIfAny istället.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

Denna parameter definierar nödvändiga antialiasing‑åtgärder under konvertering av sammansatta bakgrundsbilder från PDF till HTML.

**Returns:**
AntialiasingProcessingType‑element @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet.

**Returns:**
int‑värde

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

När PDFtoHTML‑konverteraren genererar resultat‑CSS‑filer, skapas CSS‑klassnamn (något i stil med \".stl_01 {}\" … \".stl_NN {}\") och används i resultat‑CSS. Denna egenskap tillåter att tvinga fram ett prefix för klassnamn. Till exempel, om du vill att alla klassnamn ska börja med 'my_prefix_' (dvs. vara något i stil med 'my_prefix_1' … 'my_prefix_NNN'), tilldela bara 'my_prefix_' till denna egenskap före konverteringen. Om egenskapen lämnas orörd (dvs. null lämnas som värde), kommer konverteraren att generera klassnamnen själv (det blir något i stil med \".stl_01 {}\" … \".stl_NN {}\").

**Returns:**
String värde

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konvertering av Pdf till Html för hantering av sparande av CSS‑filer som är relaterade till det skapade HTML‑dokumentet som helhet eller till dess sidor (om flera HTML‑sidor genereras). Om du vill hantera CSS‑filen på ett specifikt sätt, skapa bara en relevant metod och tilldela en delegat skapad från den till denna egenskap.

**Returns:**
CssSavingStrategy‑instans

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor. Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar bearbetning av en HTML‑sida (mer exakt – markup‑HTML, utan externa länkade filer om några) som skapades under konverteringen. I så fall kan bearbetning (t.ex. sparande av sidans HTML i en ström eller på disk) utföras i den anpassade koden. I sådant fall måste alla nödvändiga åtgärder för att spara HTML‑sidan utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens egen kod, inte i anpassad kod, sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo'‑parameter: den kommer att signalera till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad kod fanns för bearbetning.

**Returns:**
HtmlPageMarkupSavingStrategy instans

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Denna hanterare kan användas för att hantera konverteringsförloppshändelser t.ex. den kan användas för att visa en förloppsindikator eller meddelanden om det aktuella antalet bearbetade sidor, exempel på hanterarens kod som visar förloppet i konsolen är : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler instans

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konverteringen för anpassad hantering av skapade refererade resursfiler (som bilder och teckensnitt) relaterade till noder i sparad HTML. Strategin måste bearbeta resurserna och returnera en sträng som representerar önskad URL för den sparade resursen i den genererade HTML.

**Returns:**
ResourceSavingStrategy instans

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

Detta fält kan innehålla en anpassad metod som returnerar URL (eller URL‑mall om flersidig generering är på – se detaljer nedan) för den aktuella CSS‑filen som ska placeras i den genererade resultat‑HTML‑en. T.ex. om du vill att konverteraren ska sätta en specifik URL istället för standard‑CSS‑filnamnet i den genererade CSS‑en, bör du bara skapa och tilldela den här egenskapen en metod som genererar önskad URL. Om flaggan 'SplitCssIntoPages' är satt, måste denna anpassade strategi (om någon) returnera en mallsträng snarare än en exakt URL för CSS‑en, så att (efter ersättning av platshållaren med sidnummer med String.Format()-funktionen i konverteraren) den kan omvandlas till en URL för den aktuella sidans CSS‑URL. Exempel på förväntade retursträngar i sådant fall är: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 } ' )

**Returns:**
CssUrlMakingStrategy instans

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Anger namnet på ett installerat teckensnitt som används för att ersätta alla dokumentteckensnitt som inte är inbäddade och inte är installerade i systemet. Om null används standardersättningsteckensnittet.

**Returns:**
Strängvärde: Fontnamn

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Hämtar {@code HtmlDocumentTypeInternal}.

**Returns:**
Den {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

Lista över PDF‑inbäddade teckensnittsnamn som inte ska bäddas in i HTML.

**Returns:**
array av String-element

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1-baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i den resulterande HTML‑sidan/-sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll‑PDF‑filen. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag.

**Returns:**
int-array

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

Detta attribut specificerar fullbreddstext för stycket i flödesläge, FixedLayout = false

**Returns:**
booleskt värde

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Definierar en speciell kodningsregel för att finjustera PDF‑avkodning för det aktuella dokumentet

**Returns:**
FontEncodingRules element @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

Definierar teckensnittssparningsläge som kommer att användas vid sparande av PDF till önskat format

**Returns:**
FontSavingModes element @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Teckensnittskällor för förhandssparade teckensnitt. </p>

**Returns:**
FontSourceCollection objekt <hr> <p> Typsnitt kan sparas preliminärt för cacheändamål och sedan skickas in i Html-konverteringsprocessen. Till exempel kan det vara användbart i ett dokumentdelningsscenario och vid bearbetning av dokumentsidor i flera trådar med en enda uppsättning typsnitt. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

Ibland finns specifika krav på generering av HTML‑markup. Denna parameter definierar HTML‑förberedelselägen som kan användas vid konvertering av PDF till HTML för att uppfylla sådana specifika krav.

**Returns:**
HtmlMarkupGenerationModes element @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Hämtar eller anger upplösning för bildrendering.

**Returns:**
Värde: Upplösning

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Anger läge för placering av bokstäver i ord i resulterande HTML

**Returns:**
LettersPositioningMethods element @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

Detta attribut anger minimal bredd för grafisk banlinje. Om linjetjockleken är mindre än 1 px rundar Adobe Acrobat den till detta värde. Så kan detta attribut användas för att emulera detta beteende i HTML‑webbläsare.

**Returns:**
flyttalsvärde

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

Detta attribut representerar en uppsättning inställningar som används för att rita en ram (om någon) i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan. I huvudsak gäller det visning av sidans papperkanter, inte sidramen som refereras i PDF‑sidan själv.

**Returns:**
BorderInfo instans

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

Detta attribut representerar en uppsättning extra sidmarginaler (om några) i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan.

**Returns:**
MarginInfo instans

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

Det definierar om refererade filer (HTML, teckensnitt, bilder, CSS‑filer) ska bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter

**Returns:**
PartsEmbeddingModes element @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

Konverterad PDF kan innehålla rasterbilder. Denna parameter definierar hur de ska hanteras vid konvertering av PDF till HTML

**Returns:**
RasterImagesSavingModes element @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Hämtar eller anger sökväg till katalog där eventuella bilder som påträffas vid sparande av dokumentet som HTML ska sparas. Om parametern är tom eller null sparas bildfiler (om några) tillsammans med övriga filer som länkas till HTML. Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den aktuella bildfilen.

**Returns:**
String värde

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Hämtar eller anger sökväg till katalog där endast SVG‑bilder ska sparas om de påträffas vid sparande av dokumentet som HTML. Om parametern är tom eller null sparas SVG‑filer (om några) tillsammans med övriga bildfiler (i närheten av utdatafilen) eller i en särskild bildmapp (om den anges i alternativet SpecialImagesFolderIfAny). Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den aktuella bildfilen.

**Returns:**
String värde

### getTitle {#getTitle--}
```
public final String getTitle()
```

Hämtar eller anger HTML‑sidans titel.

**Returns:**
String värde

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Hämtar flaggan som indikerar om hittad SVG‑grafik (om någon) kommer att komprimeras (zippas) till SVGZ‑format vid sparande. Värde: {@code HtmlDocumentType}.

**Returns:**
booleskt värde

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

Om attributet ConvertMarkedContentToLayers är satt till true placeras alla element inom ett PDF‑markerat innehåll (lager) i en HTML‑div med attributet "data-pdflayer" som specificerar ett lagernamn. Detta lagernamn hämtas från valfria egenskaper för PDF‑markerat innehåll. Om detta attribut är false (standard) skapas inga lager från PDF‑markerat innehåll.

**Returns:**
booleskt värde

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

Hämtar ett värde som indikerar om HTML‑en skapas som fast layout.

**Returns:**
värde: {@code true} om [fixed layout]; annars, {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel för avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard.

**Returns:**
booleskt värde

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

Om attributet 'SplitOnPages=false', placeras hela HTML‑en som representerar alla inmatade PDF‑sidor i en stor resultat‑HTML‑fil. Denna flagga bestämmer om resultat‑HTML genereras på ett sätt där flödet av områden som representerar PDF‑sidor beror på skärmupplösningen hos visaren. Anta att skärmbredden på visarsidan är tillräckligt stor för att placera två eller fler sidor bredvid varandra horisontellt. Om flaggan är satt till true utnyttjas detta (så många sidor som möjligt visas horisontellt bredvid varandra, och nästa horisontella grupp av sidor visas under den första). Annars flödar sidorna så att nästa sida alltid placeras under föregående.

**Returns:**
booleskt värde

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

Detta attribut aktiverar läget där textglyfer inte grupperas till ord och strängar. Detta läge möjliggör maximal precision vid placering av glyfer på sidan och kan användas för konvertering av dokument med musiknotationer eller glyfer som ska placeras separat från varandra. Parametern tillämpas på dokumentet endast när värdet för attributet FixedLayout är true.

**Returns:**
booleskt värde

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Definierar om tomt område högst upp och längst ner utan innehåll (om sådant finns) ska tas bort i den skapade HTML‑en.

**Returns:**
booleskt värde

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

Om attributet RenderTextAsImage är satt till true blir texten från källan en bild i HTML. Detta kan vara användbart för att göra texten omarkerbar eller när HTML‑text inte renderas korrekt.

**Returns:**
booleskt värde

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Indikerar att hela teckensnittet sparas, stöder endast True Type‑teckensnitt. Som standard är SaveFullFont = false och konverteraren sparar en delmängd av det ursprungliga teckensnittet som behövs för att visa dokumentets text.

**Returns:**
booleskt värde

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

Pdf kan innehålla texter som skuggas av andra element (t.ex. av bilder) men som kan markeras till urklipp i Acrobat Reader (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren om sådana texter ska sparas som transparenta, markerbara texter i resultat‑HTML för att efterlikna Acrobat Readers beteende (annars sparas sådana texter vanligtvis som dolda och kan inte kopieras till urklipp).

**Returns:**
booleskt värde

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Pdf kan innehålla transparenta texter som kan markeras till urklipp (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren om sådana texter ska sparas som transparenta, markerbara texter i resultat‑HTML.

**Returns:**
booleskt värde

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

Detta attribut specificerar en sekventiell gruppering av glyfer och ord i strängar. Till exempel har taggar och ord olika ordning i konverterad HTML och du vill att de ska matcha. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout-attributet är sant.

**Returns:**
booleskt värde

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

När flersidigt läge är valt (dvs. 'SplitIntoPages' är 'true'), definierar detta attribut om en separat CSS-fil ska skapas för varje resulterande HTML-sida. Som standard är detta attribut falskt, så en stor gemensam CSS skapas för alla skapade sidor. Den sammanlagda storleken på alla CSS-filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS-fil, eftersom i det första fallet är CSS-klasser duplicerade i flera CSS-filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML-sida oberoende, och därmed är storleken på CSS för varje enskild sida den mest kritiska frågan.

**Returns:**
booleskt värde

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Hämtar flaggan som indikerar om varje sida i källdokumentet kommer att konverteras till ett eget mål‑HTML‑dokument, d.v.s. om resulterande HTML kommer att delas upp i flera HTML‑sidor.

**Returns:**
booleskt värde

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

PDF-filen i sig innehåller inga understrykningsmarkörer för text. Det efterliknas med en linje placerad under texten. Detta alternativ låter konverteraren försöka gissa att en viss linje är en texts understrykning och placera denna information i CSS istället för att rita understrykningen grafiskt.

**Returns:**
booleskt värde

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

Om attributet UseZORder är satt till true läggs grafik och text till det resulterande HTML-dokumentet enligt Z‑ordningen i det ursprungliga PDF-dokumentet. Om detta attribut är false placeras all grafik som ett enda lager, vilket kan orsaka onödiga effekter för överlappande objekt.

**Returns:**
booleskt värde

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

Om attributet 'SplitOnPages=false', då kommer hela HTML som representerar alla inmatade PDF‑sidor inte att delas upp i separata HTML‑sidor, utan placeras i en stor resultat‑HTML‑fil. Men varje käll‑PDF‑sida kommer att representeras med sitt eget rektangelområde i HTML (om nödvändigt kan dessa områden ramas in för att visa sidans kant med det speciella attributet 'PageBorderIfAny'). Denna parameter definierar bredden på marginalen som tvingas lämnas runt de utdata‑HTML‑områden som representerar sidorna i källdokumentet. I grund och botten definierar den garanterat intervall mellan HTML‑representationer av PDF \"paper\"‑sidor i en sådan konverteringsmetod.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde @deprecated AdditionalMarginWidthInPoints är föråldrat, vänligen använd PageMarginIfAny istället. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

Denna parameter definierar nödvändiga antialiasing‑åtgärder under konvertering av sammansatta bakgrundsbilder från PDF till HTML.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| antialiasingProcessing |  | AntialiasingProcessingType‑element @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Ställer in flaggan som indikerar om hittad SVG-grafik (om någon) kommer att komprimeras (zippas) till SVGZ-format vid sparande. Värde: {@code HtmlDocumentType}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

Om attributet ConvertMarkedContentToLayers är satt till true placeras alla element inom ett PDF‑markerat innehåll (lager) i en HTML‑div med attributet "data-pdflayer" som specificerar ett lagernamn. Detta lagernamn hämtas från valfria egenskaper för PDF‑markerat innehåll. Om detta attribut är false (standard) skapas inga lager från PDF‑markerat innehåll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
När PDFtoHTML‑konverteraren genererar resultat‑CSS‑filer, skapas CSS‑klassnamn (något i stil med \".stl_01 {}\" … \".stl_NN {}\") och används i resultat‑CSS. Denna egenskap tillåter att tvinga fram ett prefix för klassnamn. Till exempel, om du vill att alla klassnamn ska börja med 'my_prefix_' (dvs. vara något i stil med 'my_prefix_1' … 'my_prefix_NNN'), tilldela bara 'my_prefix_' till denna egenskap före konverteringen. Om egenskapen lämnas orörd (dvs. null lämnas som värde), kommer konverteraren att generera klassnamnen själv (det blir något i stil med \".stl_01 {}\" … \".stl_NN {}\").

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
Detta fält kan innehålla en sparstrategi som måste användas (om den finns) under konvertering av Pdf till Html för hantering av sparande av CSS‑filer som är relaterade till det skapade HTML‑dokumentet som helhet eller till dess sidor (om flera HTML‑sidor genereras). Om du vill hantera CSS‑filen på ett specifikt sätt, skapa bara en relevant metod och tilldela en delegat skapad från den till denna egenskap.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor. Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar bearbetning av en HTML‑sida (mer exakt – markup‑HTML, utan externa länkade filer om några) som skapades under konverteringen.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
Detta fält kan innehålla en sparstrategi som måste användas (om närvarande) under konverteringen för anpassad hantering av skapade refererade resursfiler (som bilder och typsnitt) som är relaterade till noder i sparad HTML.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
Detta fält kan innehålla en anpassad metod som returnerar URL (eller URL‑mall om flersidig generering är på – se detaljer nedan) för den aktuella CSS‑filen som ska placeras i den genererade resultat‑HTML‑en.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Anger namnet på ett installerat teckensnitt som används för att ersätta alla dokumentteckensnitt som inte är inbäddade och inte är installerade i systemet. Om null används standardersättningsteckensnittet.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
Ställer in {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
Lista över PDF‑inbäddade teckensnittsnamn som inte ska bäddas in i HTML.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1-baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i den resulterande HTML‑sidan/-sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll‑PDF‑filen. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

Ställer in ett värde som indikerar om HTML‑en skapas som fast layout.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | : {@code true} om [fixed layout]; annars, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

Detta attribut specificerar fullbreddstext för stycket i flödesläge, FixedLayout = false

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Definierar en speciell kodningsregel för att finjustera PDF‑avkodning för det aktuella dokumentet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontEncodingStrategy |  | FontEncodingRules element @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

Definierar teckensnittssparningsläge som kommer att användas vid sparande av PDF till önskat format

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontSavingMode |  | FontSavingModes element @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

Ibland finns specifika krav på generering av HTML‑markup. Denna parameter definierar HTML‑förberedelselägen som kan användas vid konvertering av PDF till HTML för att uppfylla sådana specifika krav.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | HtmlMarkupGenerationModes element @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel för avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Hämtar eller anger upplösning för bildrendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Värde: Upplösning |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Anger läge för placering av bokstäver i ord i resulterande HTML

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

Detta attribut anger minimal bredd för grafisk banlinje. Om linjetjockleken är mindre än 1 px rundar Adobe Acrobat den till detta värde. Så kan detta attribut användas för att emulera detta beteende i HTML‑webbläsare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
Detta attribut representerar en uppsättning inställningar som används för att rita en ram (om någon) i resultat‑HTML‑dokumentet runt det område som representerar käll‑PDF‑sidan.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
Detta attribut representerar en uppsättning extra sidmarginaler (om några) i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

Om attributet 'SplitOnPages=false', placeras hela HTML‑en som representerar alla inmatade PDF‑sidor i en stor resultat‑HTML‑fil. Denna flagga bestämmer om resultat‑HTML genereras på ett sätt där flödet av områden som representerar PDF‑sidor beror på skärmupplösningen hos visaren. Anta att skärmbredden på visarsidan är tillräckligt stor för att placera två eller fler sidor bredvid varandra horisontellt. Om flaggan är satt till true utnyttjas detta (så många sidor som möjligt visas horisontellt bredvid varandra, och nästa horisontella grupp av sidor visas under den första). Annars flödar sidorna så att nästa sida alltid placeras under föregående.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | booleskt värde |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

Det definierar om refererade filer (HTML, teckensnitt, bilder, CSS‑filer) ska bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| partsEmbeddingMode |  | PartsEmbeddingModes element @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

Detta attribut aktiverar läget där textglyfer inte grupperas till ord och strängar. Detta läge möjliggör maximal precision vid placering av glyfer på sidan och kan användas för konvertering av dokument med musiknotationer eller glyfer som ska placeras separat från varandra. Parametern tillämpas på dokumentet endast när värdet för attributet FixedLayout är true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

Konverterad PDF kan innehålla rasterbilder. Denna parameter definierar hur de ska hanteras vid konvertering av PDF till HTML

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImagesSavingMode |  | RasterImagesSavingModes element @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Definierar om tomt område högst upp och längst ner utan innehåll (om sådant finns) ska tas bort i den skapade HTML‑en.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | booleskt värde |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

Om attributet RenderTextAsImage är satt till true blir texten från källan en bild i HTML. Detta kan vara användbart för att göra texten omarkerbar eller när HTML‑text inte renderas korrekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Indikerar att hela teckensnittet sparas, stöder endast True Type‑teckensnitt. Som standard är SaveFullFont = false och konverteraren sparar en delmängd av det ursprungliga teckensnittet som behövs för att visa dokumentets text.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

Pdf kan innehålla texter som skuggas av andra element (t.ex. av bilder) men som kan markeras till urklipp i Acrobat Reader (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren om sådana texter ska sparas som transparenta, markerbara texter i resultat‑HTML för att efterlikna Acrobat Readers beteende (annars sparas sådana texter vanligtvis som dolda och kan inte kopieras till urklipp).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | booleskt värde |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Pdf kan innehålla transparenta texter som kan markeras till urklipp (vanligtvis sker detta när dokumentet innehåller bilder och OCR‑extraherade texter). Denna inställning talar om för konverteraren om sådana texter ska sparas som transparenta, markerbara texter i resultat‑HTML.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| saveTransparentTexts |  | booleskt värde |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

Detta attribut specificerar en sekventiell gruppering av glyfer och ord i strängar. Till exempel har taggar och ord olika ordning i konverterad HTML och du vill att de ska matcha. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout-attributet är sant.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Hämtar eller anger sökväg till katalog där eventuella bilder som påträffas vid sparande av dokumentet som HTML ska sparas. Om parametern är tom eller null sparas bildfiler (om några) tillsammans med övriga filer som länkas till HTML. Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den aktuella bildfilen.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Hämtar eller anger sökväg till katalog där endast SVG‑bilder ska sparas om de påträffas vid sparande av dokumentet som HTML. Om parametern är tom eller null sparas SVG‑filer (om några) tillsammans med övriga bildfiler (i närheten av utdatafilen) eller i en särskild bildmapp (om den anges i alternativet SpecialImagesFolderIfAny). Detta påverkar inte något om egenskapen CustomImageSavingStrategy har använts framgångsrikt för att bearbeta den aktuella bildfilen.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

När flersidigt läge är valt (dvs. 'SplitIntoPages' är 'true'), definierar detta attribut om en separat CSS-fil ska skapas för varje resulterande HTML-sida. Som standard är detta attribut falskt, så en stor gemensam CSS skapas för alla skapade sidor. Den sammanlagda storleken på alla CSS-filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS-fil, eftersom i det första fallet är CSS-klasser duplicerade i flera CSS-filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML-sida oberoende, och därmed är storleken på CSS för varje enskild sida den mest kritiska frågan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Ställer in flaggan som indikerar om varje sida i källdokumentet kommer att konverteras till ett eget mål‑HTML‑dokument, d.v.s. om resulterande HTML kommer att delas upp i flera HTML‑sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTitle {#setTitle-java.lang.String-}
Hämtar eller anger HTML‑sidans titel.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

PDF-filen i sig innehåller inga understrykningsmarkörer för text. Det efterliknas med en linje placerad under texten. Detta alternativ låter konverteraren försöka gissa att en viss linje är en texts understrykning och placera denna information i CSS istället för att rita understrykningen grafiskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | booleskt värde |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

Om attributet UseZORder är satt till true läggs grafik och text till det resulterande HTML-dokumentet enligt Z‑ordningen i det ursprungliga PDF-dokumentet. Om detta attribut är false placeras all grafik som ett enda lager, vilket kan orsaka onödiga effekter för överlappande objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
