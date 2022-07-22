---
title: StructureTypeStandard
second_title: Aspose.PDF för .NET API Referens
description: Representerar standardstrukturtyper.
type: docs
weight: 4560
url: /sv/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

Representerar standardstrukturtyper.

```csharp
public sealed class StructureTypeStandard
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category) { get; } | Hämtar kategori av standardstrukturtyp. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag) { get; } | Hämtar taggnamn på[`StructureElement`](../structureelement) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit) | Utför en explicit konvertering frånString till[`StructureTypeStandard`](../structuretypestandard) . |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot) | (Anteckning; PDF 1.5) En koppling mellan en del av ILSE:s innehåll och en motsvarande PDF-anteckning. Annot ska användas för alla PDF-kommentarer utom länkkommentarer och widgetkommentarer. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art) | (Artikel) En relativt fristående textkropp som utgör en enda berättelse eller utläggning. Artiklar bör vara osammanhängande; det vill säga de ska inte innehålla andra artiklar som beståndsdelar. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry) | (Bibliografipost) En referens som identifierar den externa källan till visst citerat innehåll. Den kan innehålla en etikett (strukturtyp Lbl) som ett barn. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote) | (Blockcitattecken) En del av texten som består av ett eller flera stycken som tillskrivs någon annan än författaren till den omgivande texten. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption) | (Caption) En kort del av texten som beskriver en tabell eller figur. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code) | (kod) Ett fragment av datorprogramtext. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div) | (Division) Ett generiskt element på blocknivå eller grupp av element. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document) | (Dokument) Ett komplett dokument. Detta är rotelementet i ett strukturträd som innehåller flera delar eller flera artiklar. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure) | (Figur) Ett objekt med grafiskt innehåll. Dess placering kan anges med attributet Placeringslayout. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form) | (Form) En widgetanteckning som representerar ett interaktivt formulärfält. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula) | (Formel) En matematisk formel. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h) | (Rubrik) En etikett för en underavdelning av ett dokuments innehåll. Det bör vara det första barnet i divisionen som det leder. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1) | Nivå 1 Rubrik, för användning i konforma skribenter som inte kan hierarkiskt kapsla sina avsnitt och därför inte kan bestämma nivån på en rubrik utifrån dess kapslingsnivå. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2) | Nivå 2 Rubrik, för användning i konforma skribenter som inte kan hierarkiskt kapsla sina avsnitt och därför inte kan bestämma nivån på en rubrik utifrån dess kapslingsnivå. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3) | Nivå 3 Rubrik, för användning i konforma skribenter som inte kan hierarkiskt kapsla sina avsnitt och därför inte kan bestämma nivån på en rubrik utifrån dess kapslingsnivå. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4) | Nivå 4 Rubrik, för användning i konforma skribenter som inte kan hierarkiskt kapsla sina avsnitt och därför inte kan bestämma nivån på en rubrik utifrån dess kapslingsnivå. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5) | Nivå 5 Rubrik, för användning i konforma skribenter som inte kan hierarkiskt kapsla sina avsnitt och därför inte kan bestämma nivån på en rubrik utifrån dess kapslingsnivå. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6) | Nivå 6 Rubrik, för användning i konforma skribenter som inte kan hierarkiskt kapsla sina avsnitt och därför inte kan bestämma nivån på en rubrik utifrån dess kapslingsnivå. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index) | (Index) En sekvens av poster som innehåller identifierande text åtföljd av referenselement som pekar ut förekomster av den angivna texten i huvuddelen av ett dokument. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l) | (Lista) En sekvens av objekt av samma betydelse och betydelse. Dess omedelbara underordnade bör vara en valfri bildtext (strukturtyp Caption) följt av en eller flera listobjekt (strukturtyp LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl) | (Etikett) Ett namn eller nummer som skiljer ett givet objekt från andra i samma lista eller annan grupp av liknande objekt. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody) | (Listkropp) Det beskrivande innehållet i ett listobjekt. I en ordbokslista, till exempel, innehåller den definitionen av termen. Det kan antingen innehålla innehållet direkt eller ha andra BLSE, kanske inklusive kapslade listor, som barn. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li) | (Listobjekt) En enskild medlem av en lista. Dess underordnade kan vara en eller flera etiketter, listkroppar eller båda (strukturtyperna Lbl eller LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link) | (Länk) En koppling mellan en del av ILSE:s innehåll och en motsvarande länkanteckning eller -kommentarer. Dess underordnade bör vara ett eller flera innehållsobjekt eller underordnade ILSE:er och en eller flera objektreferenser som identifierar de associerade länkannoteringarna. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct) | (icke-strukturellt element) Ett grupperingselement som inte har någon inneboende strukturell betydelse; den tjänar enbart för grupperingsändamål. Denna typ av element skiljer sig från en division (strukturtyp Div) genom att den inte ska tolkas eller exporteras till andra dokumentformat; dock ska dess avkomlingar behandlas normalt. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note) | (Notera) En förklarande text, t.ex. en fotnot eller en slutnot, som hänvisas till från dokumentets brödtext. Den kan ha en etikett (strukturtyp Lbl) som barn. Anteckningen kan ingå som ett underordnat strukturelement i brödtexten som hänvisar till det, eller det kan inkluderas någon annanstans (som i en slutnotssektion) och nås med hjälp av en referens (strukturtyp Referens). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p) | (Paragraph) En indelning av text på låg nivå. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part) | (Del) En storskalig uppdelning av ett dokument. Den här typen av element är lämplig för att gruppera artiklar eller avsnitt. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private) | (Privat element) Ett grupperingselement som innehåller privat innehåll som tillhör applikationen som producerar det. Den strukturella betydelsen av denna typ av element är ospecificerad och ska helt och hållet bestämmas av den överensstämmande skrivaren. Varken det privata elementet eller någon av dess avkomlingar får tolkas eller exporteras till andra dokumentformat. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote) | (Citat) En inline-del av text som tillskrivs någon annan än författaren till den omgivande texten. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb) | (Rubybastext) Texten i full storlek som rubinkommentaren appliceras på. RB kan innehålla text, andra inline-element eller en blandning av båda. Den kan ha RubyAlignattribute. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference) | (Referens) En hänvisning till innehåll någon annanstans i dokumentet. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp) | (Ruby interpunktion) Skiljetecken som omger rubinkommentartexten. Den används endast när en rubinkommentar inte kan formateras korrekt i rubinstil och istället är formaterad som en normal kommentar, eller när den är formaterad som en warichu. Den innehåller text (vanligtvis en enda VÄNSTER eller HÖGER PARENTES eller liknande parentes). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt) | (Ruby annotation text) Den mindre texten som ska placeras intill rubinbastexten. Den kan innehålla text, andra inline-element eller en blandning av båda. Den kan ha attributen RubyAlign och RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby) | (Ruby; PDF 1.5) En sidoanteckning (anteckning) skriven i en mindre textstorlek och placerad i anslutning till grundtexten som den refererar till. Ett Ruby-element kan också innehålla RB-, RT- och RP-elementen. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect) | (avsnitt) En behållare för att gruppera relaterade innehållselement. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span) | (Span) En generisk inline-del av text som inte har några speciella inneboende egenskaper. Den kan till exempel användas för att avgränsa ett textintervall med en given uppsättning stilattribut. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table) | (Tabell) En tvådimensionell layout av rektangulära dataceller, som eventuellt har en komplex understruktur. Den innehåller antingen en eller flera tabellrader (strukturtyp TR) som underordnade; eller ett valfritt tabellhuvud (strukturtyp THead) följt av ett eller flera tabellkroppselement (strukturtyp TBody) och en valfri tabellsidfot (strukturtyp TFoot). Dessutom kan en tabell ha en bildtext (strukturtyp Caption) som sitt första eller sista underordnade. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody) | (Radgrupp för tabellkropp; PDF 1.5) En grupp rader som utgör huvuddelen av en tabell. Om tabellen är uppdelad på flera sidor kan brödtextområdet delas isär på en radgräns. En tabell kan ha flera TBody-element för att göra det möjligt att rita en ram eller bakgrund för en uppsättning rader. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td) | (tabelldatacell) En tabellcell som innehåller data som är en del av tabellens innehåll. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot) | (Radgrupp för tabellsidfot; PDF 1.5) En grupp rader som utgör sidfoten i en tabell. Om tabellen är uppdelad på flera sidor kan dessa rader ritas om längst ned i varje tabellfragment (även om det bara finns ett TFoot-element.) |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th) | (Tabellrubrikcell) En tabellcell som innehåller rubriktext som beskriver en eller flera rader eller kolumner i tabellen. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead) | (Radgrupp för tabellrubrik; PDF 1.5) En grupp rader som utgör rubriken i en tabell. Om tabellen är uppdelad på flera sidor kan dessa rader ritas om överst i varje tabellfragment (även om det bara finns ett THead-element). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc) | (Innehållsförteckning) En lista som består av poster i innehållsförteckningen (strukturtyp TOCI) och/eller andra kapslade innehållsförteckningar (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci) | (Innehållsförteckning) En enskild medlem av en innehållsförteckning. Den här postens barn kan vara någon av följande strukturtyper: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr) | (tabellrad) En rad med rubriker eller data i en tabell. Den kan innehålla tabellrubrikceller och tabelldataceller (strukturtyperna TH och TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu) | (Warichu; PDF 1.5) En kommentar eller anteckning i en mindre textstorlek och formaterad på två mindre rader inom höjden av den innehållande textraden och placerad efter (inline) bastexten som den refererar till. Ett Warichu-element kan också innehålla WT- och WP-elementen. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp) | (Warichu-interpunktion) Skiljetecken som omger WT-texten. Den innehåller text (vanligtvis en enda VÄNSTER eller HÖGER PARENTES eller liknande parentes). Enligt JIS X 4051-1995 kan parentesen som omger en warichu konverteras till ett MELLANSLAG (nominellt 1/4 EM i bredd) efter formaterarens gottfinnande. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt) | (Warichu-text) Den mindre texten i en warichu-kommentar som formateras till två rader och placeras mellan omgivande WP-element. |

### Se även

* namnutrymme [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
