---
title: "Klass StructureTypeStandard"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LogicalStructure.StructureTypeStandard-klass. Representerar standardstrukturtyper"
type: docs
weight: 6870
url: /sv/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

Representerar standardstrukturtyper.

```csharp
public sealed class StructureTypeStandard
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Hämtar kategori för standardstrukturtyp. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Hämtar taggnamn för [`StructureElement`](../structureelement/). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Utför en explicit konvertering från String till `StructureTypeStandard`. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation; PDF 1.5) En association mellan en del av ILSE:s innehåll och en motsvarande PDF-annotation. Annot ska användas för alla PDF-annotationer förutom länkannotationer och widget-annotationer. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Article) En relativt självständig textkropp som utgör en enskild berättelse eller exposition. Artiklar bör vara åtskilda; det vill säga, de bör inte innehålla andra artiklar som beståndsdelar. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Bibliography entry) En referens som identifierar den externa källan till något citerat innehåll. Den kan innehålla en etikett (strukturtyp Lbl) som ett underobjekt. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Block quotation) En textdel bestående av ett eller flera stycken som tillskrivs någon annan än författaren till den omgivande texten. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Caption) En kort text som beskriver en tabell eller figur. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Code) Ett fragment av datorprogramtext. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) Ett generiskt blocknivåelement eller en grupp av element. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Document) Ett komplett Document. Detta är rot-elementet i alla strukturträd som innehåller flera delar eller flera artiklar. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figure) Ett grafiskt innehållsobjekt. Dess placering kan specificeras med layoutattributet Placement. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Form) En widget-annotation som representerar ett interaktivt formulärfält. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formula) En matematisk formel. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Heading) En etikett för en underindelning av ett dokuments innehåll. Den bör vara det första underobjektet i den division som den rubriker. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Rubrik nivå 1, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Rubrik nivå 2, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Rubrik nivå 3, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Rubrik nivå 4, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Rubrik nivå 5, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Rubrik nivå 6, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) En sekvens av poster som innehåller identifierande text följd av referenselement som pekar på förekomster av den specificerade texten i huvudtexten i ett dokument. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (List) En sekvens av objekt med liknande betydelse och vikt. Dess omedelbara underobjekt bör vara en valfri caption (strukturtyp Caption) följt av ett eller flera listobjekt (strukturtyp LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Label) Ett namn eller nummer som särskiljer ett givet objekt från andra i samma lista eller annan grupp av liknande objekt. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (List body) Det beskrivande innehållet i ett listobjekt. I en ordbokslista, till exempel, innehåller det definitionen av termen. Det kan antingen innehålla innehållet direkt eller ha andra BLSE:er, eventuellt inklusive nästlade listor, som barn. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (List item) En enskild medlem i en lista. Dess barn kan vara en eller flera etiketter, listkroppar, eller båda (strukturtyper Lbl eller LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Link) En association mellan en del av ILSE:s innehåll och en motsvarande länkanmärkning eller länkanmärkningar. Dess barn bör vara en eller flera innehållselement eller underordnade ILSE:er samt en eller flera objektreferenser som identifierar de associerade länkanmärkningarna. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Nonstructural element) Ett grupperingselement utan inneboende strukturell betydelse; det tjänar enbart för gruppering. Denna typ av element skiljer sig från en division (strukturtyp Div) genom att det inte får tolkas eller exporteras till andra dokumentformat; däremot ska dess underordnade bearbetas normalt. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Note) Ett objekt med förklarande text, såsom en fotnot eller slutnot, som refereras till från dokumentets brödtext. Det kan ha en etikett (strukturtyp Lbl) som barn. Noten kan inkluderas som ett barn till strukturelementet i brödtexten som refererar till den, eller så kan den placeras någon annanstans (t.ex. i en slutnotsektion) och nås via en referens (strukturtyp Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Paragraph) En låg nivå division av text. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Part) En storskalig division av ett dokument. Denna typ av element är lämplig för att gruppera artiklar eller sektioner. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Private element) Ett grupperingselement som innehåller privat innehåll som tillhör den applikation som skapar det. Den strukturella betydelsen av denna typ av element är ospecificerad och ska bestämmas helt av den konformerande författaren. Varken Private-elementet eller någon av dess underordnade får tolkas eller exporteras till andra dokumentformat. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Quotation) En infogad textdel som tillskrivs någon annan än författaren till den omgivande texten. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Ruby base text) Den fullstora texten som ruby‑annoteringen appliceras på. RB kan innehålla text, andra infogade element eller en blandning av båda. Den kan ha RubyAlign‑attributet. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Reference) En hänvisning till innehåll någon annanstans i dokumentet. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ruby punctuation) Interpunktion som omger ruby‑annoteringstexten. Den används endast när en ruby‑annotering inte kan formateras korrekt i ruby‑stil och i stället formateras som en vanlig kommentar, eller när den formateras som en warichu. Den innehåller text (vanligtvis ett enda VÄNSTER‑ eller HÖGER‑PARANTES eller liknande avgränsningstecken). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Ruby annotation text) Den mindre texten som ska placeras intill ruby‑bastexten. Den kan innehålla text, andra infogade element eller en blandning av båda. Den kan ha RubyAlign‑ och RubyPosition‑attributen. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) En sidokommentar (annotering) skriven i mindre textstorlek och placerad intill bastexten den refererar till. Ett Ruby‑element kan också innehålla RB-, RT- och RP‑elementen. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Section) En behållare för att gruppera relaterade innehållselement. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) En generell infogad textdel utan särskilda inneboende egenskaper. Den kan exempelvis användas för att avgränsa ett textområde med en viss uppsättning stilattribut. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Table) En tvådimensionell layout av rektangulära dataceller, eventuellt med en komplex understruktur. Den innehåller antingen en eller flera tabellrader (strukturtyp TR) som barn; eller ett valfritt tabellhuvud (strukturtyp THead) följt av en eller flera tabellkroppsdelar (strukturtyp TBody) och ett valfritt tabellfot (strukturtyp TFoot). Dessutom kan en tabell ha en rubrik (strukturtyp Caption) som dess första eller sista barn. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Table body row group; PDF 1.5) En grupp rader som utgör huvudkroppsdelarna i en tabell. Om tabellen delas över flera sidor kan kroppsområdet brytas upp vid en radgräns. En tabell kan ha flera TBody-element för att möjliggöra ritning av en ram eller bakgrund för en uppsättning rader. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Table data cell) En tabellcell som innehåller data som är en del av tabellens innehåll. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Table footer row group; PDF 1.5) En grupp rader som utgör foten i en tabell. Om tabellen delas över flera sidor kan dessa rader ritas om längst ner i varje tabellfragment (även om det bara finns ett TFoot-element.) |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Table header cell) En tabellcell som innehåller rubriktext som beskriver en eller flera rader eller kolumner i tabellen. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Table header row group; PDF 1.5) En grupp rader som utgör tabellens huvud. Om tabellen delas över flera sidor kan dessa rader ritas om högst upp i varje tabellfragment (även om det bara finns ett THead-element). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Table of contents) En lista bestående av innehållsförteckningspostposter (strukturtyp TOCI) och/eller andra nästlade innehållsförteckningsposter (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Table of contents item) En enskild medlem i en innehållsförteckning. Detta posts barn kan vara någon av följande strukturtyper: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Table row) En rad med rubriker eller data i en tabell. Den kan innehålla tabellhuvudceller och tabelldataceller (strukturtyper TH och TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) En kommentar eller annotation i en mindre textstorlek och formaterad på två mindre rader inom höjden av den omgivande textraden och placerad efter (inline) bastexten som den refererar till. Ett Warichu-element kan också innehålla WT- och WP-element. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Warichu punctuation) Den interpunktion som omger WT-texten. Den innehåller text (vanligtvis en ensam VÄNSTER eller HÖGER PARENTES eller liknande klammertecken). Enligt JIS X 4051-1995 kan parenteserna som omger ett warichu konverteras till ett SPACE (nominalt 1/4 EM i bredd) enligt formaterarens bedömning. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Warichu text) Den mindre storlekens text för en warichu-kommentar som är formaterad i två rader och placerad mellan omgivande WP-element. |

### Se även

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


