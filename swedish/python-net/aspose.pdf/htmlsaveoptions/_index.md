---
title: "HtmlSaveOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Spara alternativ för export till HTML-format"
type: docs
weight: 490
url: /sv/python-net/aspose.pdf/htmlsaveoptions/
---

## HtmlSaveOptions class

Spara alternativ för export till HTML-format

Typen HtmlSaveOptions exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| HtmlSaveOptions() | Initierar en ny instans av klassen [HtmlSaveOptions](/pdf/python-net/aspose.pdf/htmlsaveoptions/). |
| HtmlSaveOptions(document_type) | Initierar en ny instans av klassen HtmlSaveOptions |
| HtmlSaveOptions(fixed_layout) | Initierar en ny instans av klassen HtmlSaveOptions |
| HtmlSaveOptions(document_type, fixed_layout) | Initierar en ny instans av klassen HtmlSaveOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Återanrop för att hantera eventuella genererade varningar. <br/>            WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. <br/>            Continue är standardåtgärden och spara‑operationen fortsätter, men användaren kan också returnera Abort, varvid spara‑operationen ska avbrytas. |
| save_format | Format för datasparning. |
| close_response | Hämtar eller anger ett booleskt värde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| extract_ocr_sublayer_only | Ingen |
| try_merge_adjacent_same_background_images | Ingen |
| document_type | Hämtar eller anger [HtmlDocumentType](/pdf/python-net/aspose.pdf/htmldocumenttype/). |
| compress_svg_graphics_if_any | Hämtar eller anger flaggan som indikerar om<br/>            hittade SVG-grafik (om någon) kommer att komprimeras (zippas) <br/>            till SVGZ-format vid sparande |
| split_css_into_pages | När flersidigt läge är valt (dvs. 'SplitIntoPages' är 'true'), <br/>            definierar detta attribut om en separat CSS-fil ska skapas<br/>            för varje resulterande HTML-sida.<br/>            Som standard är detta attribut falskt, så en stor gemensam CSS skapas<br/>            för alla skapade sidor. Den sammanlagda storleken på alla<br/>            CSS-filer som genereras i detta läge (en CSS per sida) är vanligtvis<br/>            mycket större än storleken på en enda stor CSS-fil, eftersom i det första fallet <br/>            CSS-klasser dupliceras i flera CSS-filer för varje sida.<br/>            Så denna inställning bör endast användas när du är intresserad<br/>            av framtida bearbetning av varje HTML-sida separat, och därför är storleken<br/>            på CSS för varje enskild sida den mest kritiska faktorn. |
| split_into_pages | Hämtar eller anger flaggan som indikerar om varje sida i källdokumentet <br/>            kommer att konverteras till ett eget mål‑HTML‑dokument, <br/>            d.v.s. om resulterande HTML kommer att delas upp i flera HTML‑sidor. |
| explicit_list_of_saved_pages | Med den här egenskapen kan du explicit definiera <br/>            vilka sidor i dokumentet som ska konverteras.<br/>            Sidor i den här listan måste ha 1‑baserade nummer. Dvs. <br/>            giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument])<br/>            Ordningen på sidorna i listan påverkar inte deras<br/>            ordning i den resulterande HTML‑sidan/-sidorna – i resultatet kommer sidorna alltid att visas i den ordning de <br/>            förekommer i käll‑PDF‑filen.<br/>            Om listan är null (vilket är standard) konverteras alla sidor.<br/>            Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument])<br/>            kastas ett undantag. |
| fixed_layout | Hämtar eller anger ett värde som indikerar om HTML‑en skapas som fast layout. |
| image_resolution | Hämtar eller anger upplösning för bildrendering. |
| default_font_name | Anger namnet på ett installerat teckensnitt som används för att ersätta<br/>            alla dokumentteckensnitt som inte är inbäddade och inte är installerade i systemet. <br/>            Om null används standardersättningsteckensnittet. |
| batch_size | Definierar batch‑storlek om batch‑konvertering är tillämplig<br/>            för käll‑ och målformatpar. |
| font_sources | Teckensnittskällor för förhandslagrade teckensnitt. |
| additional_margin_width_in_points | Om attributet 'SplitOnPages=false', då kommer hela HTML som representerar alla inmatade PDF‑sidor inte<br/>            att delas upp i separata HTML‑sidor, utan placeras i en stor resultat‑HTML‑fil.<br/>            Men varje käll‑PDF‑sida kommer att representeras med sitt eget <br/>            rektangelområde i HTML (om nödvändigt kan dessa områden ramas in för att visa sidpapperskanter<br/>            med specialattributet 'PageBorderIfAny'.<br/>            Denna parameter definierar marginalens bredd som tvingas lämnas runt de utdata‑HTML‑områdena<br/>            som representerar sidor i käll‑PDF‑dokumentet. I huvudsak definierar den ett garanterat intervall mellan<br/>            HTML‑representationerna av PDF‑\"paper\"‑sidor i detta konverteringsläge. |
| use_z_order | Om attributet UseZORder är satt till true läggs grafik och text till det resulterande HTML‑dokumentet<br/>            enligt Z‑ordning i original‑PDF‑dokumentet. Om detta attribut är false placeras all grafik<br/>            som ett enda lager, vilket kan orsaka onödiga effekter för överlappande objekt. |
| convert_marked_content_to_layers | Om attributet ConvertMarkedContentToLayers är satt till true placeras alla element i ett PDF‑markerat<br/>            innehåll (lager) i en HTML‑div med attributet "data-pdflayer" som specificerar ett lagernamn.<br/>            Detta lagernamn hämtas från valfria egenskaper i det PDF‑markerade innehållet.<br/>            Om detta attribut är false (standard) skapas inga lager från PDF‑markerat innehåll. |
| minimal_line_width | Detta attribut anger minimal bredd för grafisk sökvägslinje.<br/>            Om linjens tjocklek är mindre än 1 px rundar Adobe Acrobat den till detta värde. Så kan detta attribut<br/>            användas för att efterlikna detta beteende i HTML‑webbläsare. |
| prevent_glyphs_grouping | Detta attribut aktiverar läget där textglyfer inte grupperas till ord och strängar<br/>            Detta läge möjliggör maximal precision vid placering av glyfer på sidan och kan<br/>            användas för konvertering av dokument med musiknoter eller glyfer som ska placeras separat från varandra.<br/>            Denna parameter tillämpas på dokumentet endast när värdet för attributet FixedLayout är sant. |
| simple_textbox_mode_grouping | Detta attribut specificerar en sekventiell gruppering av glyfer och ord till strängar<br/>            Till exempel har taggar och ord olika ordning i konverterad HTML och du vill att de ska matcha.<br/>            Denna parameter tillämpas på dokumentet endast när värdet för attributet FixedLayout är sant. |
| flow_layout_paragraph_full_width | Detta attribut specificerar fullbreddstext för stycke i Flow‑läge, FixedLayout = false |
| render_text_as_image | Om attributet RenderTextAsImage är satt till true blir texten från källan en bild i HTML.<br/>            Kan vara användbart för att göra texten omarkerbar<br/>            eller om HTML‑texten inte renderas korrekt. |
| save_full_font | Indikerar att hela teckensnittet kommer att sparas, stöder endast True Type‑teckensnitt.<br/>            Som standard är SaveFullFont = false och konverteraren sparar en delmängd av det ursprungliga teckensnittet<br/>            som behövs för att visa dokumentets text. |
| antialiasing_processing | Denna parameter definierar nödvändiga antialias‑åtgärder vid konvertering av sammansatta bakgrundsbilder från PDF till HTML |
| save_transparent_texts | Pdf kan innehålla transparenta texter som kan markeras till urklipp (vanligtvis sker det när dokumentet innehåller bilder och OCR‑extraherade texter).<br/>            Denna inställning talar om för konverteraren om vi behöver spara sådana texter som transparenta<br/>            markerbara texter i resulterande HTML |
| save_shadowed_texts_as_transparent_texts | Pdf kan innehålla texter som skuggas av andra element (t.ex. av bilder) men <br/>            kan markeras till urklipp i Acrobat Reader (vanligtvis sker det när dokumentet innehåller bilder och OCR‑extraherade texter).<br/>            Denna inställning talar om för konverteraren om vi behöver spara sådana texter som transparenta<br/>            markerbara texter i resulterande HTML för att efterlikna Acrobat Readers beteende (annars sparas sådana texter vanligtvis som dolda, inte tillgängliga för kopiering till urklipp) |
| font_saving_mode | Definierar teckensnittssparningsläge som kommer att användas vid sparning av PDF till önskat format |
| page_border_if_any | Detta attribut representerar en uppsättning inställningar som används för att rita en ram (om någon)<br/>            i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan.<br/>            I huvudsak handlar det om att visa sidans papperkanter,<br/>            inte sidramen som refereras i själva PDF‑sidan. |
| page_margin_if_any | Detta attribut representerar en uppsättning extra sidmarginaler (om några)<br/>            i det resulterande HTML‑dokumentet runt området som representerar käll‑PDF‑sidan. |
| letters_positioning_method | Ställer in lägesmetod för placering av bokstäver i ord i resulterande HTML |
| exclude_font_name_list | Lista över PDF-inbäddade teckensnittsnamn som inte ska bäddas in i HTML. |
| special_folder_for_svg_images | Hämtar eller anger sökväg till katalog där endast SVG-bilder ska sparas om de <br/>            påträffas under sparande av dokument som HTML. Om parametern är tom eller null<br/>            sparas SVG-filer (om några) tillsammans med andra bild-filer (nära utdatafilen)<br/>            eller i en speciell mapp för bilder (om den anges i alternativet SpecialImagesFolderIfAny).<br/>            Det påverkar inte något om egenskapen CustomImageSavingStrategy<br/>            framgångsrikt har använts för att bearbeta relevant bildfil. |
| special_folder_for_all_images | Hämtar eller anger sökväg till katalog där alla bilder ska sparas om de <br/>            påträffas under sparande av dokument som HTML. Om parametern är tom eller null<br/>            sparas bildfiler (om några) tillsammans med andra filer som länkas till HTML<br/>            Det påverkar inte något om egenskapen CustomImageSavingStrategy<br/>            framgångsrikt har använts för att bearbeta relevant bildfil. |
| css_class_names_prefix | När PDFtoHTML‑konverteraren genererar resultat‑CSS‑filer, skapas CSS‑klassnamn<br/>            (t.ex. ".stl_01 {}" ... ".stl_NN {}") och används i resultat‑CSS. Denna egenskap tillåter att tvinga fram ett prefix för klassnamn<br/>            Till exempel, om du vill att alla klassnamn ska börja med 'my_prefix_'<br/>            (dvs. vara något i stil med 'my_prefix_1' ... 'my_prefix_NNN'), <br/>            så tilldela helt enkelt 'my_prefix_' till denna egenskap innan konvertering.<br/>            Om denna egenskap lämnas orörd (dvs. null behålls som värde), så<br/>            kommer konverteraren att generera klassnamn själv <br/>            (det blir något i stil med ".stl_01 {}" ... ".stl_NN {}") |
| parts_embedding_mode | Den definierar om refererade filer (HTML, teckensnitt, bilder, CSS‑filer)<br/>            ska bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter |
| html_markup_generation_mode | Ibland finns specifika krav på generering av HTML‑markup.<br/>            Denna parameter definierar HTML‑förberedelselägen som kan användas<br/>            under konvertering av PDF till HTML för att uppfylla sådana specifika krav. |
| raster_images_saving_mode | Den konverterade PDF‑filen kan innehålla rasterbilder<br/>            Denna parameter definierar hur de ska hanteras<br/>            under konvertering av PDF till HTML |
| remove_empty_areas_on_top_and_bottom | Definierar om tomma områden högst upp och längst ner utan något innehåll (om några) ska tas bort i den skapade HTML‑filen. |
| font_encoding_strategy | Definierar en särskild kodningsregel för att finjustera PDF‑avkodning för det aktuella dokumentet |
| pages_flow_type_depends_on_viewers_screen_size | Om attributet 'SplitOnPages=false', kommer hela HTML som representerar alla inmatade PDF‑sidor att <br/>            placeras i en stor resultat‑HTML‑fil. <br/>            Denna flagga definierar om resultat‑HTML ska genereras på ett sätt<br/>            där flödet av områden som representerar PDF‑sidor i resultat‑HTML beror<br/>            på skärmupplösningen hos visaren. <br/>            Anta att skärmbredden på visarsidan är tillräckligt stor för att placera 2 eller fler sidor nära varandra i horisontell riktning. Om denna flagga är satt till true, kommer denna möjlighet<br/>            att användas (så många sidor som möjligt visas i horisontell riktning nära varandra<br/>            så det går, och sedan visas nästa horisontella grupp av sidor under den första).<br/>            Annars kommer sidorna att flöda på följande sätt: nästa sida placeras alltid under föregående. |
| try_save_text_underlining_and_strikeouting_in_css | PDF-filen i sig innehåller inte understrykningsmarkörer för texter. Det emuleras med en linje placerad under texten.<br/>            Detta alternativ låter konverteraren försöka gissa att denna eller den linjen är en texts understrykning<br/>            och placera denna information i CSS istället för att rita understrykningen grafiskt |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

