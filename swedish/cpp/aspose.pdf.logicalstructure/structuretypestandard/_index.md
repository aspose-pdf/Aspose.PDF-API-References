---
title: "Aspose::Pdf::LogicalStructure::StructureTypeStandard class"
linktitle: "StructureTypeStandard"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::StructureTypeStandard class. Representerar standardstrukturtyper i C++."
type: docs
weight: 5900
url: /sv/cpp/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class


Representerar standard [Structure](../../aspose.pdf.structure/) typer.

```cpp
class StructureTypeStandard : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Category](./get_category/)() const | Hämtar kategori för standard [Structure](../../aspose.pdf.structure/) typ. |
| [get_Tag](./get_tag/)() const | Hämtar taggnamnet för [Aspose::Pdf::LogicalStructure::StructureElement](../structureelement/). |
| static [to_StructureTypeStandard](./to_structuretypestandard/)(const System::String\&) | Utför en explicit konvertering från [System::String](../../system/string/) till [Aspose::Pdf::LogicalStructure::StructureTypeStandard](./). |
| [ToString](./tostring/)() const override | Returnerar en sträng som representerar det aktuella objektet. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Annot](./annot/) | (Annotation; PDF 1.5) En association mellan en del av ILSE:s innehåll och en motsvarande PDF-annotation. Annot ska användas för alla PDF-annotationer förutom länkanotationer och widget-annotationer. |
| static [Art](./art/) | (Article) En relativt självständig textkropp som utgör en enskild berättelse eller exposition. Artiklar bör vara disjunkta; det vill säga, de bör inte innehålla andra artiklar som beståndsdelar. |
| static [BibEntry](./bibentry/) |  |
| static [BlockQuote](./blockquote/) | (Block quotation) En del av text som består av ett eller flera stycken som tillskrivs någon annan än författaren till den omgivande texten. |
| static [Caption](./caption/) | (Caption) En kort textdel som beskriver en tabell eller figur. |
| static [Code](./code/) | (Code) Ett fragment av datorprogramtext. |
| static [Div](./div/) | (Division) Ett generiskt blocknivåelement eller en grupp av element. |
| static [Document](./document/) | ([Document](../../aspose.pdf/document/)) Ett komplett dokument. Detta är rot‑elementet i alla strukturträd som innehåller flera delar eller flera artiklar. |
| static [Figure](./figure/) | (Figure) Ett objekt av grafiskt innehåll. Dess placering kan specificeras med layoutattributet Placement. |
| static [Form](./form/) | (Form) En widget-annotation som representerar ett interaktivt formulärfält. |
| static [Formula](./formula/) |  |
| static [H](./h/) | ([Heading](../../aspose.pdf/heading/)) En etikett för en underindelning av ett dokuments innehåll. Den bör vara det första barnet i den division som den rubriker. |
| static [H1](./h1/) | Nivå 1 [Heading](../../aspose.pdf/heading/), för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma en rubriknivå utifrån dess nästlingsnivå. |
| static [H2](./h2/) | Nivå 2 [Heading](../../aspose.pdf/heading/), för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma en rubriknivå utifrån dess nästlingsnivå. |
| static [H3](./h3/) | Nivå 3 [Heading](../../aspose.pdf/heading/), för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma en rubriknivå utifrån dess nästlingsnivå. |
| static [H4](./h4/) | Nivå 4 [Heading](../../aspose.pdf/heading/), för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma en rubriknivå utifrån dess nästlingsnivå. |
| static [H5](./h5/) | Nivå 5 [Heading](../../aspose.pdf/heading/), för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma en rubriknivå utifrån dess nästlingsnivå. |
| static [H6](./h6/) | Nivå 6 [Heading](../../aspose.pdf/heading/), för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma en rubriknivå utifrån dess nästlingsnivå. |
| static [Index](./index/) | (Index) En sekvens av poster som innehåller identifierande text tillsammans med referenselement som pekar på förekomster av den angivna texten i dokumentets huvudtext. |
| static [L](./l/) | (List) En sekvens av objekt med liknande betydelse och vikt. Dess omedelbara underordnade bör vara en valfri rubrik (strukturtyp Caption) följt av ett eller flera listobjekt (strukturtyp LI). |
| static [Lbl](./lbl/) | (Label) Ett namn eller nummer som särskiljer ett givet objekt från andra i samma lista eller annan grupp av liknande objekt. |
| static [LBody](./lbody/) | (List body) Det beskrivande innehållet i ett listobjekt. I en ordbokslista, till exempel, innehåller det definitionen av termen. Det kan antingen innehålla innehållet direkt eller ha andra BLSE:er, eventuellt inklusive nästlade listor, som underordnade. |
| static [LI](./li/) | (List item) En individuell medlem i en lista. Dess underordnade kan vara ett eller flera etiketter, listkroppar eller båda (strukturtyper Lbl eller LBody). |
| static [Link](./link/) | (Link) En association mellan en del av ILSE:s innehåll och en motsvarande länkanotering eller länkanoteringar. Dess underordnade bör vara ett eller flera innehållsobjekt eller barn-ILSE:er samt ett eller flera objektreferenser som identifierar de associerade länkanoteringarna. |
| static [NonStruct](./nonstruct/) | (Nonstructural element) Ett grupperande element utan inneboende strukturell betydelse; det tjänar enbart för gruppering. Denna typ av element skiljer sig från en division (strukturtyp Div) genom att det inte ska tolkas eller exporteras till andra dokumentformat; däremot ska dess efterkommande behandlas normalt. |
| static [Note](./note/) |  |
| static [P](./p/) | (Paragraph) En låg nivå division av text. |
| static [Part](./part/) | (Part) En storskalig indelning av ett dokument. Denna typ av element är lämplig för att gruppera artiklar eller sektioner. |
| static [Private](./private/) | (Private element) Ett grupperande element som innehåller privat innehåll som tillhör den applikation som producerar det. Den strukturella betydelsen av denna typ av element är ospecificerad och ska bestämmas helt av den konformerande författaren. Varken det privata elementet eller någon av dess underordnade får tolkas eller exporteras till andra dokumentformat. |
| static [Quote](./quote/) |  |
| static [RB](./rb/) | (Ruby base text) Den fullstora texten som ruby‑annoteringen appliceras på. RB kan innehålla text, andra inline‑element eller en blandning av båda. Den kan ha RubyAlign‑attributet. |
| static [Reference](./reference/) | (Reference) En hänvisning till innehåll någon annanstans i dokumentet. |
| static [RP](./rp/) | (Ruby punctuation) Interpunktion som omger ruby‑annoteringstexten. Den används endast när en ruby‑annotering inte kan formateras korrekt i ruby‑stil och istället formateras som en vanlig kommentar, eller när den formateras som en warichu. Den innehåller text (vanligtvis ett enda VÄNSTER‑ eller HÖGER‑PARANTES eller liknande parentesliknande tecken). |
| static [RT](./rt/) | (Ruby annotation text) Den mindre texten som ska placeras intill ruby‑bastexten. Den kan innehålla text, andra inline‑element eller en blandning av båda. Den kan ha RubyAlign‑ och RubyPosition‑attributen. |
| static [Ruby](./ruby/) |  |
| static [Sect](./sect/) | (Section) En behållare för att gruppera relaterade innehållselement. |
| static [Span](./span/) | (Span) En generisk inline‑del av text utan särskilda inneboende egenskaper. Den kan till exempel användas för att avgränsa ett textintervall med en given uppsättning stilattribut. |
| static [Table](./table/) | ([Table](../../aspose.pdf/table/)) En tvådimensionell layout av rektangulära dataceller, eventuellt med en komplex understruktur. Den innehåller antingen en eller flera tabellrader (strukturtyp TR) som barn; eller ett valfritt tabellhuvud (strukturtyp THead) följt av en eller flera tabellkropps‑element (strukturtyp TBody) och ett valfritt tabellfot (strukturtyp TFoot). Dessutom kan en tabell ha en bildtext (strukturtyp Caption) som sitt första eller sista barn. |
| static [TBody](./tbody/) | ([Table](../../aspose.pdf/table/) body row group; PDF 1.5) En grupp rader som utgör huvudkropps‑delen av en tabell. Om tabellen delas över flera sidor kan kropps‑området brytas upp vid en radgräns. En tabell kan ha flera TBody‑element för att möjliggöra ritning av en ram eller bakgrund för en uppsättning rader. |
| static [TD](./td/) | ([Table](../../aspose.pdf/table/) data cell) En tabellcell som innehåller data som är en del av tabellens innehåll. |
| static [TFoot](./tfoot/) | ([Table](../../aspose.pdf/table/) footer row group; PDF 1.5) En grupp rader som utgör foten på en tabell. Om tabellen delas över flera sidor kan dessa rader återritas längst ner i varje tabellfragment (även om det bara finns ett TFoot‑element.) |
| static [TH](./th/) | ([Table](../../aspose.pdf/table/) header cell) En tabellcell som innehåller rubriktext som beskriver en eller flera rader eller kolumner i tabellen. |
| static [THead](./thead/) | ([Table](../../aspose.pdf/table/) header row group; PDF 1.5) En grupp rader som utgör tabellens rubrik. Om tabellen delas över flera sidor kan dessa rader återritas högst upp i varje tabellfragment (även om det bara finns ett THead‑element). |
| static [TOC](./toc/) |  |
| static [TOCI](./toci/) |  |
| static [TR](./tr/) | ([Table](../../aspose.pdf/table/) row) En rad med rubriker eller data i en tabell. Den kan innehålla tabellrubrikceller och tabelldataceller (strukturtyperna TH och TD). |
| static [Warichu](./warichu/) |  |
| static [WP](./wp/) | (Warichu punctuation) Interpunktionen som omger WT‑texten. Den innehåller text (vanligtvis ett enda VÄNSTER‑ eller HÖGER‑PARANTES eller liknande parentesliknande tecken). Enligt JIS X 4051-1995 kan parenteserna som omger en warichu konverteras till ett MELLANSLAG (nominalt 1/4 EM i bredd) efter formatterarens gottfinnande. |
| static [WT](./wt/) | (Warichu text) Den mindre texten i en warichu‑kommentar som formateras i två rader och placeras mellan omgivande WP‑element. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
