---
title: Class StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.StructureTypeStandard klass. Representerar Standard Strukturtyper
type: docs
weight: 6730
url: /sv/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard klass

Representerar Standard Strukturtyper.

```csharp
public sealed class StructureTypeStandard
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Hämtar kategori av Standard Strukturtyp. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Hämtar taggnamn av [`StructureElement`](../structureelement/). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Utför en explicit konvertering från String till `StructureTypeStandard`. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation; PDF 1.5) En koppling mellan en del av ILSE:s innehåll och en motsvarande PDF-anteckning. Annot ska användas för alla PDF-anteckningar utom länkanteckningar och widgetanteckningar. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Artikel) En relativt självständig text som utgör en enda berättelse eller redogörelse. Artiklar bör vara åtskilda; det vill säga, de bör inte innehålla andra artiklar som beståndsdelar. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Bibliografi post) En referens som identifierar den externa källan till något citerat innehåll. Den kan innehålla en etikett (strukturtyp Lbl) som ett barn. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Blockcitat) En del av text som består av ett eller flera stycken som tillskrivs någon annan än författaren till den omgivande texten. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Rubrik) En kort del av text som beskriver en tabell eller figur. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Kod) Ett fragment av dataprogramtext. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) Ett generiskt blocknivåelement eller en grupp av element. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Dokument) Ett komplett dokument. Detta är rot-elementet i vilken strukturträd som helst som innehåller flera delar eller flera artiklar. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figur) Ett objekt av grafiskt innehåll. Dess placering kan specificeras med attributet Placering layout. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Form) En widgetanteckning som representerar ett interaktivt formulärfält. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formel) En matematisk formel. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Rubrik) En etikett för en underavdelning av ett dokuments innehåll. Den bör vara det första barnet av den division som den leder. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Nivå 1 Rubrik, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därmed inte kan bestämma nivån på en rubrik utifrån dess nivå av nästling. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Nivå 2 Rubrik, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därmed inte kan bestämma nivån på en rubrik utifrån dess nivå av nästling. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Nivå 3 Rubrik, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därmed inte kan bestämma nivån på en rubrik utifrån dess nivå av nästling. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Nivå 4 Rubrik, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därmed inte kan bestämma nivån på en rubrik utifrån dess nivå av nästling. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Nivå 5 Rubrik, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därmed inte kan bestämma nivån på en rubrik utifrån dess nivå av nästling. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Nivå 6 Rubrik, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därmed inte kan bestämma nivån på en rubrik utifrån dess nivå av nästling. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) En sekvens av poster som innehåller identifierande text åtföljd av referenselement som pekar ut förekomster av den angivna texten i huvuddelen av ett dokument. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (Lista) En sekvens av objekt med liknande betydelse och vikt. Dess omedelbara barn bör vara en valfri rubrik (strukturtyp Caption) följt av en eller flera listobjekt (strukturtyp LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Etikett) Ett namn eller nummer som särskiljer ett givet objekt från andra i samma lista eller annan grupp av liknande objekt. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (Lista kropp) Det beskrivande innehållet i ett listobjekt. I en ordbokslista, till exempel, innehåller det definitionen av termen. Det kan antingen innehålla innehållet direkt eller ha andra BLSE:er, kanske inklusive nästlade listor, som barn. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (Listobjekt) En individuell medlem av en lista. Dess barn kan vara en eller flera etiketter, listkroppar, eller båda (strukturtyper Lbl eller LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Länk) En koppling mellan en del av ILSE:s innehåll och en motsvarande länkanteckning eller anteckningar. Dess barn bör vara ett eller flera innehållsobjekt eller barn ILSE:er och en eller flera objektreferenser som identifierar de associerade länkanteckningarna. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Icke-strukturelement) Ett grupperande element utan inneboende strukturell betydelse; det tjänar enbart för grupperingsändamål. Denna typ av element skiljer sig från en division (strukturtyp Div) genom att den inte ska tolkas eller exporteras till andra dokumentformat; dock ska dess ättlingar behandlas normalt. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Not) Ett objekt av förklarande text, såsom en fotnot eller en slutnot, som hänvisas till från texten i dokumentet. Det kan ha en etikett (strukturtyp Lbl) som ett barn. Noten kan inkluderas som ett barn av struktur-elementet i brödtexten som hänvisar till den, eller den kan inkluderas någon annanstans (som i en slutnot-sektion) och nås genom en referens (strukturtyp Referens). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Stycke) En låg nivå av textindelning. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Del) En storskalig indelning av ett dokument. Denna typ av element är lämplig för att gruppera artiklar eller sektioner. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Privat element) Ett grupperande element som innehåller privat innehåll som tillhör den applikation som producerar det. Den strukturella betydelsen av denna typ av element är ospecificerad och ska bestämmas helt av den konformerande skribenten. Varken det privata elementet eller någon av dess ättlingar ska tolkas eller exporteras till andra dokumentformat. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Citat) En inline-del av text som tillskrivs någon annan än författaren till den omgivande texten. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Ruby bastext) Den fullstora texten som ruby-anteckningen tillämpas på. RB kan innehålla text, andra inline-element, eller en blandning av båda. Det kan ha attributet RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Referens) En citation till innehåll någon annanstans i dokumentet. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ruby interpunktion) Interpunktion som omger ruby-anteckningstexten. Den används endast när en ruby-anteckning inte kan formateras korrekt i en ruby-stil och istället formateras som en normal kommentar, eller när den formateras som en warichu. Den innehåller text (vanligtvis en enda VÄNSTER eller HÖGER PARANTES eller liknande inramande tecken). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Ruby anteckningstext) Den mindre storleken text som ska placeras intill ruby bastext. Den kan innehålla text, andra inline-element, eller en blandning av båda. Den kan ha attributen RubyAlign och RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) En sidanteckning (anteckning) skriven i en mindre textstorlek och placerad intill den bastext som den hänvisar till. Ett Ruby-element kan också innehålla RB, RT och RP-elementen. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Sektion) En behållare för att gruppera relaterade innehållselement. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) En generisk inline-del av text utan några särskilda inneboende egenskaper. Den kan användas, till exempel, för att avgränsa ett textområde med en given uppsättning stilattribut. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Tabell) En tvådimensionell layout av rektangulära dataceller, som eventuellt har en komplex understruktur. Den innehåller antingen en eller flera tabellrader (strukturtyp TR) som barn; eller en valfri tabellhuvud (strukturtyp THead) följt av en eller flera tabellkroppselement (strukturtyp TBody) och en valfri tabellfot (strukturtyp TFoot). Dessutom kan en tabell ha en rubrik (strukturtyp Caption) som sitt första eller sista barn. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Tabell kroppsradsgrupp; PDF 1.5) En grupp av rader som utgör den huvudsakliga kroppsdelen av en tabell. Om tabellen är uppdelad över flera sidor kan kroppsområdet brytas vid en radgräns. En tabell kan ha flera TBody-element för att möjliggöra ritning av en kant eller bakgrund för en uppsättning rader. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Tabell datacell) En tabellcell som innehåller data som är en del av tabellens innehåll. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Tabell fotradsgrupp; PDF 1.5) En grupp av rader som utgör foten av en tabell. Om tabellen är uppdelad över flera sidor kan dessa rader ritas om i botten av varje tabellfragment (även om det bara finns ett TFoot-element). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Tabell headercell) En tabellcell som innehåller rubriktext som beskriver en eller flera rader eller kolumner i tabellen. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Tabell header radsgrupp; PDF 1.5) En grupp av rader som utgör rubriken av en tabell. Om tabellen är uppdelad över flera sidor kan dessa rader ritas om i toppen av varje tabellfragment (även om det bara finns ett THead-element). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Innehållsförteckning) En lista som består av poster för innehållsförteckning (strukturtyp TOCI) och/eller andra nästlade innehållsförteckningsposter (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Innehållsförteckningspost) En individuell medlem av en innehållsförteckning. Denna postens barn kan vara någon av följande strukturtyper: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Tabellrad) En rad av rubriker eller data i en tabell. Den kan innehålla tabellhuvudceller och tabell dataceller (strukturtyper TH och TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) En kommentar eller anteckning i en mindre textstorlek och formaterad på två mindre rader inom höjden av den omgivande textlinjen och placerad efter (inline) den bastext som den hänvisar till. Ett Warichu-element kan också innehålla WT och WP-elementen. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Warichu interpunktion) Den interpunktion som omger WT-texten. Den innehåller text (vanligtvis en enda VÄNSTER eller HÖGER PARANTES eller liknande inramande tecken). Enligt JIS X 4051-1995 kan parenteserna som omger en warichu konverteras till ett UTRYMME (nominalt 1/4 EM i bredd) efter formatterarens gottfinnande. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Warichu text) Den mindre storleken text av en warichu-kommentar som formateras i två rader och placeras mellan omgivande WP-element. |

### Se Även

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)