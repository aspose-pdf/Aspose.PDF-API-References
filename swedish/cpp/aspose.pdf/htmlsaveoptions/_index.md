---
title: "Aspose::Pdf::HtmlSaveOptions-klass"
linktitle: "HtmlSaveOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions-klass. Spara alternativ för export till Html-format i C++."
type: docs
weight: 7300
url: /sv/cpp/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class


Spara alternativ för export till HTML‑format.

```cpp
class HtmlSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                        public Aspose::Pdf::IPageSetOptions,
                        public Aspose::Pdf::IPipelineOptions
```

## Nested classes

* Class [CssSavingInfo](./csssavinginfo/)
* Class [CssUrlRequestInfo](./cssurlrequestinfo/)
* Class [HtmlImageSavingInfo](./htmlimagesavinginfo/)
* Class [HtmlPageMarkupSavingInfo](./htmlpagemarkupsavinginfo/)
## Enums

| Enum | Beskrivning |
| --- | --- |
| [AntialiasingProcessingType](./antialiasingprocessingtype/) | Denna enum beskriver möjliga antialiasing-åtgärder under konvertering. |
| [FontEncodingRules](./fontencodingrules/) | Denna uppräkning definierar regler som finjusterar kodningslogiken. |
| [FontSavingModes](./fontsavingmodes/) | Enumererar lägen som kan användas för att spara teckensnitt som refereras i sparad PDF. |
| [HtmlImageType](./htmlimagetype/) | enumererar möjliga typer av bildfiler som kan sparas som externa resurser under [Pdf](../) till Html-konvertering |
| [HtmlMarkupGenerationModes](./htmlmarkupgenerationmodes/) | Ibland finns specifika krav på den skapade HTML:n. Denna enum definierar HTML-förberedelselägen som kan användas under konvertering av PDF till HTML för att matcha sådana specifika krav. |
| [ImageParentTypes](./imageparenttypes/) | Enumererar möjliga typer av bildföräldrar som [Image](../image/) kan tillhöra, antingen HTML-sida eller SVG-föräldrabild. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Den enumererar möjliga lägen för placering av bokstäver i ord i den resulterande HTML:n. |
| [PartsEmbeddingModes](./partsembeddingmodes/) | Denna enum enumererar möjliga lägen för inbäddning av filer som refereras i HTML. Den låter dig kontrollera om refererade filer (HTML, teckensnitt, bilder, CSS-filer) kommer att bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter. |
| [RasterImagesSavingModes](./rasterimagessavingmodes/) | Konverterad PDF kan innehålla rasterbilder (.png, *.jpeg etc.). Denna enum definierar metoder för hur rasterbilder kan hanteras under konvertering av PDF till HTML. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AdditionalMarginWidthInPoints](./get_additionalmarginwidthinpoints/)() const | Om attributet 'SplitOnPages=false', så kommer hela HTML som representerar alla inmatade PDF‑sidor inte att delas upp i olika HTML‑sidor, utan placeras i en stor resultat‑HTML‑fil. Men varje käll‑PDF‑sida kommer att representeras med sitt eget rektangelområde i HTML (om så behövs kan dessa områden omges av en kant för att visa sidans papperkanter med det speciella attributet 'PageBorderIfAny'). Denna parameter definierar bredden på marginalen som tvingas lämnas runt de utdata‑HTML‑områden som representerar sidorna i käll‑PDF‑dokumentet. I huvudsak definierar den ett garanterat intervall mellan HTML‑representationerna av PDF‑"pappers"‑sidor i ett sådant konverteringsläge. |
| [get_BatchSize](./get_batchsize/)() override | Definierar batch‑storlek om batch‑konvertering är tillämplig för käll‑ och destinationsformatparet. |
| [get_CompressSvgGraphicsIfAny](./get_compresssvggraphicsifany/)() const | Hämtar flaggan som indikerar om hittade SVG‑grafik (om någon) kommer att komprimeras (zippas) till SVGZ‑format vid sparande. |
| [get_ConvertMarkedContentToLayers](./get_convertmarkedcontenttolayers/)() const | Om attributet ConvertMarkedContentToLayers är satt till true placeras alla element inom ett PDF‑markerat innehåll (lager) i en HTML‑div med attributet "data-pdflayer" som specificerar ett lagernamn. Detta lagernamn extraheras från valfria egenskaper för PDF‑markerat innehåll. Om detta attribut är false (standard) skapas inga lager från PDF‑markerat innehåll. |
| [get_DefaultFontName](./get_defaultfontname/)() const | Anger namnet på ett installerat teckensnitt som används för att ersätta alla dokumentteckensnitt som inte är inbäddade och inte är installerade i systemet. Om null används standardersättningsteckensnittet. |
| [get_DocumentType](./get_documenttype/)() const | Hämtar [HtmlDocumentType](../htmldocumenttype/). |
| [get_ExplicitListOfSavedPages](./get_explicitlistofsavedpages/)() override | Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1‑baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i de resulterande HTML‑sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll‑PDF‑filen. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag. |
| [get_FixedLayout](./get_fixedlayout/)() const | Hämtar ett värde som indikerar om HTML‑en skapas som fast layout. |
| [get_FlowLayoutParagraphFullWidth](./get_flowlayoutparagraphfullwidth/)() const | Detta attribut specificerar paragraftext med full bredd för [Flow](../../aspose.pdf.flow/)-läge, FixedLayout = false. |
| [get_FontSources](./get_fontsources/)() const | Teckensnittskällor för förhandssparade teckensnitt. |
| [get_IgnoredTextFontSize](./get_ignoredtextfontsize/)() const | [Text](../../aspose.pdf.text/) med den angivna storleken eller mindre kommer att ignoreras under konverteringen. Vi tar inte bort denna text, vi ignorerar den och överför den inte till utdatafilen. |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Hämtar indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras. true – betyder att fel på grund av avsaknad av teckensnitt ignoreras. [Text](../../aspose.pdf.text/)-segment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [get_ImageResolution](./get_imageresolution/)() const | Hämtar upplösning för bildrendering. |
| [get_MinimalLineWidth](./get_minimallinewidth/)() const | Detta attribut anger minimal bredd för grafisk banlinje. Om linjetjockleken är mindre än 1 px rundar Adobe Acrobat upp till detta värde. Så kan detta attribut användas för att emulera detta beteende i HTML‑webbläsare. |
| [get_PreventGlyphsGrouping](./get_preventglyphsgrouping/)() const | Detta attribut aktiverar läget där textglyphs inte grupperas till ord och strängar. Detta läge möjliggör maximal precision vid placering av glyphs på sidan och kan användas för konvertering av dokument med musiknoter eller glyphs som ska placeras separat från varandra. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout‑attributet är true. |
| [get_RenderTextAsImage](./get_rendertextasimage/)() const | Om attributet RenderTextAsImage är satt till true blir texten från källan en bild i HTML. Kan vara användbart för att göra texten omarkerbar eller om HTML‑text inte renderas korrekt. |
| [get_SaveFullFont](./get_savefullfont/)() const | Indikerar att hela teckensnittet kommer att sparas, stöder endast True Type‑teckensnitt. Som standard är SaveFullFont = false och konverteraren sparar den delmängd av det ursprungliga teckensnittet som behövs för att visa dokumentets text. |
| [get_SimpleTextboxModeGrouping](./get_simpletextboxmodegrouping/)() const | Detta attribut specificerar en sekventiell gruppering av glyphs och ord i strängar. Till exempel har taggar och ord olika ordning i konverterad HTML och du vill att de ska matcha. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout‑attributet är true. |
| [get_SplitCssIntoPages](./get_splitcssintopages/)() const | När flersidigt läge är valt (dvs. 'SplitIntoPages' är true) definierar detta attribut om en separat CSS‑fil ska skapas för varje resulterande HTML‑sida. Som standard är detta attribut false, så en stor gemensam CSS‑fil skapas för alla sidor. Den sammanlagda storleken på alla CSS‑filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS‑fil, eftersom i det första fallet dupliceras CSS‑klasser i flera CSS‑filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML‑sida separat, och därmed är storleken på CSS för varje enskild sida det mest kritiska. |
| [get_SplitIntoPages](./get_splitintopages/)() const | Hämtar flaggan som indikerar om varje sida i källdokumentet ska konverteras till ett eget mål‑HTML‑dokument, d.v.s. om resultat‑HTML‑en ska delas upp i flera HTML‑sidor. |
| [get_Title](./get_title/)() const | Hämtar HTML‑sidans titel. |
| [get_TryMergeFragments](./get_trymergefragments/)() const | Flaggan för att kombinera bildfragment till en bild. |
| [get_UseZOrder](./get_usezorder/)() const | Om attributet UseZORder är satt till true läggs grafik och text till det resulterande HTML‑dokumentet enligt Z‑ordning i den ursprungliga PDF‑filen. Om detta attribut är false placeras all grafik som ett enda lager, vilket kan orsaka onödiga effekter för överlappande objekt. |
| [HtmlSaveOptions](./htmlsaveoptions/)() | Initierar en ny instans av klassen [HtmlSaveOptions](./). |
| [HtmlSaveOptions](./htmlsaveoptions/)(HtmlDocumentType) | Initierar en ny instans av klassen [HtmlSaveOptions](./). |
| [HtmlSaveOptions](./htmlsaveoptions/)(bool) | Initierar en ny instans av klassen [HtmlSaveOptions](./). |
| [HtmlSaveOptions](./htmlsaveoptions/)(HtmlDocumentType, bool) | Initierar en ny instans av klassen [HtmlSaveOptions](./). |
| [set_AdditionalMarginWidthInPoints](./set_additionalmarginwidthinpoints/)(int32_t) | Om attributet 'SplitOnPages=false', så kommer hela HTML som representerar alla inmatade PDF‑sidor inte att delas upp i olika HTML‑sidor, utan placeras i en stor resultat‑HTML‑fil. Men varje käll‑PDF‑sida kommer att representeras med sitt eget rektangelområde i HTML (om så behövs kan dessa områden omges av en kant för att visa sidans papperkanter med det speciella attributet 'PageBorderIfAny'). Denna parameter definierar bredden på marginalen som tvingas lämnas runt de utdata‑HTML‑områden som representerar sidorna i käll‑PDF‑dokumentet. I huvudsak definierar den ett garanterat intervall mellan HTML‑representationerna av PDF‑"pappers"‑sidor i ett sådant konverteringsläge. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Definierar batch‑storlek om batch‑konvertering är tillämplig för käll‑ och destinationsformatparet. |
| [set_CompressSvgGraphicsIfAny](./set_compresssvggraphicsifany/)(bool) | Ställer in flaggan som indikerar om hittad SVG‑grafik (om någon) ska komprimeras (zippas) till SVGZ‑format vid sparande. |
| [set_ConvertMarkedContentToLayers](./set_convertmarkedcontenttolayers/)(bool) | Om attributet ConvertMarkedContentToLayers är satt till true placeras alla element inom ett PDF‑markerat innehåll (lager) i en HTML‑div med attributet "data-pdflayer" som specificerar ett lagernamn. Detta lagernamn extraheras från valfria egenskaper för PDF‑markerat innehåll. Om detta attribut är false (standard) skapas inga lager från PDF‑markerat innehåll. |
| [set_DefaultFontName](./set_defaultfontname/)(const System::String\&) | Anger namnet på ett installerat teckensnitt som används för att ersätta alla dokumentteckensnitt som inte är inbäddade och inte är installerade i systemet. Om null används standardersättningsteckensnittet. |
| [set_DocumentType](./set_documenttype/)(HtmlDocumentType) | Ställer in [HtmlDocumentType](../htmldocumenttype/). |
| [set_ExplicitListOfSavedPages](./set_explicitlistofsavedpages/)(System::ArrayPtr\<int32_t\>) override | Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1‑baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i de resulterande HTML‑sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll‑PDF‑filen. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag. |
| [set_FixedLayout](./set_fixedlayout/)(bool) | Ställer in ett värde som indikerar om HTML‑en skapas som fast layout. |
| [set_FlowLayoutParagraphFullWidth](./set_flowlayoutparagraphfullwidth/)(bool) | Detta attribut specificerar paragraftext med full bredd för [Flow](../../aspose.pdf.flow/)-läge, FixedLayout = false. |
| [set_IgnoredTextFontSize](./set_ignoredtextfontsize/)(System::Nullable\<float\>) | [Text](../../aspose.pdf.text/) med den angivna storleken eller mindre kommer att ignoreras under konverteringen. Vi tar inte bort denna text, vi ignorerar den och överför den inte till utdatafilen. |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Ställer in indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel på grund av avsaknad av teckensnitt ignoreras. [Text](../../aspose.pdf.text/)-segment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [set_ImageResolution](./set_imageresolution/)(int32_t) | Ställer in upplösning för bildrendering. |
| [set_MinimalLineWidth](./set_minimallinewidth/)(float) | Detta attribut anger minimal bredd för grafisk banlinje. Om linjetjockleken är mindre än 1 px rundar Adobe Acrobat upp till detta värde. Så kan detta attribut användas för att emulera detta beteende i HTML‑webbläsare. |
| [set_PreventGlyphsGrouping](./set_preventglyphsgrouping/)(bool) | Detta attribut aktiverar läget där textglyphs inte grupperas till ord och strängar. Detta läge möjliggör maximal precision vid placering av glyphs på sidan och kan användas för konvertering av dokument med musiknoter eller glyphs som ska placeras separat från varandra. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout‑attributet är true. |
| [set_RenderTextAsImage](./set_rendertextasimage/)(bool) | Om attributet RenderTextAsImage är satt till true blir texten från källan en bild i HTML. Kan vara användbart för att göra texten omarkerbar eller om HTML‑text inte renderas korrekt. |
| [set_SaveFullFont](./set_savefullfont/)(bool) | Indikerar att hela teckensnittet kommer att sparas, stöder endast True Type‑teckensnitt. Som standard är SaveFullFont = false och konverteraren sparar den delmängd av det ursprungliga teckensnittet som behövs för att visa dokumentets text. |
| [set_SimpleTextboxModeGrouping](./set_simpletextboxmodegrouping/)(bool) | Detta attribut specificerar en sekventiell gruppering av glyphs och ord i strängar. Till exempel har taggar och ord olika ordning i konverterad HTML och du vill att de ska matcha. Denna parameter tillämpas på dokumentet endast när värdet för FixedLayout‑attributet är true. |
| [set_SplitCssIntoPages](./set_splitcssintopages/)(bool) | När flersidigt läge är valt (dvs. 'SplitIntoPages' är true) definierar detta attribut om en separat CSS‑fil ska skapas för varje resulterande HTML‑sida. Som standard är detta attribut false, så en stor gemensam CSS‑fil skapas för alla sidor. Den sammanlagda storleken på alla CSS‑filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS‑fil, eftersom i det första fallet dupliceras CSS‑klasser i flera CSS‑filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML‑sida separat, och därmed är storleken på CSS för varje enskild sida det mest kritiska. |
| [set_SplitIntoPages](./set_splitintopages/)(bool) | Ställer in flaggan som indikerar om varje sida i källdokumentet kommer att konverteras till ett eget mål‑HTML‑dokument, d.v.s. om resultat‑HTML kommer att delas upp i flera HTML‑sidor. |
| [set_Title](./set_title/)(const System::String\&) | Ställer in HTML‑sidans titel. |
| [set_TryMergeFragments](./set_trymergefragments/)(bool) | Flaggan för att kombinera bildfragment till en bild. |
| [set_UseZOrder](./set_usezorder/)(bool) | Om attributet UseZORder är satt till true läggs grafik och text till det resulterande HTML‑dokumentet enligt Z‑ordning i den ursprungliga PDF‑filen. Om detta attribut är false placeras all grafik som ett enda lager, vilket kan orsaka onödiga effekter för överlappande objekt. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [CssSavingStrategy](./csssavingstrategy/) | Du kan tilldela den här egenskapen en anpassad strategi som implementerar bearbetning och/eller sparande av en del av CSS som skapades under konvertering av PDF till HTML. I så fall måste bearbetning (t.ex. sparande till ström eller disk) göras i den anpassade koden. |
| [CssUrlMakingStrategy](./cssurlmakingstrategy/) | Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar skapandet av URL för CSS som refereras i det genererade HTML‑dokumentet. T.ex. om du vill att CSS refereras i HTML t.ex. som "otherPage.ASPX?CssID=zjjkklj" måste en sådan anpassad strategi returnera "otherPage.ASPX?CssID=zjjkklj". |
| [HtmlPageMarkupSavingStrategy](./htmlpagemarkupsavingstrategy/) | Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor (som också kan referera till externa filer som bilder eller teckensnitt). Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar bearbetning av den erhållna HTML‑sidan (HTML‑innehållet) som skapades under konverteringen. I så fall kan bearbetning (t.ex. sparande till ström eller disk) göras i den anpassade koden. I så fall måste alla nödvändiga åtgärder för att spara HTML‑sidans markup utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo' : den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad sparkod fanns. |
| [ResourceSavingStrategy](./resourcesavingstrategy/) | Till den här egenskapen kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av en extern resurs (teckensnitt eller bild) som extraherades från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I så fall kan bearbetning (t.ex. sparande till ström eller disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade HTML‑koden i stället för den ursprungliga antagna sökvägen till bildresursen. I så fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'resourceSavingInfo'. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns. |
## Se även

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPageSetOptions](../ipagesetoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
