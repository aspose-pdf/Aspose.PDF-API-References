---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar standardstrukturtyper."
type: docs
weight: 130
url: /sv/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

Representerar standardstrukturtyper.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Annot](#Annot) | (Annotation; PDF 1.5) En association mellan en del av ILSE:s innehåll och en motsvarande PDF-annotation. Annot ska användas för alla PDF-annotationer förutom länkanotationer och widgetannotationer. |
| [Art](#Art) | (Article) En relativt självständig textmassa som utgör en enda berättelse eller exposition. Artiklar bör vara åtskilda; det vill säga, de bör inte innehålla andra artiklar som beståndsdelar. |
| [BibEntry](#BibEntry) | (Bibliography entry) En referens som identifierar den externa källan till något citerat innehåll. Den kan innehålla en etikett (strukturtyp Lbl) som ett underordnat element. Även om ett bibliografipost sannolikt inkluderar komponentdelar som identifierar det citerade innehållets författare, verk, förlag osv., definieras inga standardstrukturtyper på denna detaljnivå. |
| [BlockQuote](#BlockQuote) | (Block quotation) En del av text som består av ett eller flera stycken som tillskrivs någon annan än författaren till den omgivande texten. |
| [Caption](#Caption) | (Caption) En kort textdel som beskriver en tabell eller figur. |
| [Code](#Code) | (Code) Ett fragment av datorprogramtext. |
| [Div](#Div) | (Division) Ett generiskt blocknivåelement eller en grupp av element. |
| [Document](#Document) | (Document) Ett komplett dokument. Detta är rot‑elementet i vilket strukturträd som helst som innehåller flera delar eller flera artiklar. |
| [Figure](#Figure) | (Figure) Ett objekt av grafiskt innehåll. Dess placering kan specificeras med layoutattributet Placement. |
| [Form](#Form) | (Form) En widget‑annotation som representerar ett interaktivt formulärfält. |
| [Formula](#Formula) | (Formula) En matematisk formel. Denna strukturtyp är endast användbar för att identifiera ett helt innehållselement som en formel. Inga standardstrukturtyper är definierade för att identifiera enskilda komponenter inom formeln. Ur ett formateringsperspektiv ska formeln behandlas på liknande sätt som en figur (strukturtyp Figure). |
| [H](#H) | (Heading) En etikett för en underindelning av ett dokuments innehåll. Den bör vara det första barnet i den division som den rubriker. |
| [H1](#H1) | Rubrik nivå 1, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| [H2](#H2) | Rubrik nivå 2, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| [H3](#H3) | Rubrik nivå 3, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| [H4](#H4) | Rubrik nivå 4, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| [H5](#H5) | Rubrik nivå 5, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| [H6](#H6) | Rubrik nivå 6, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| [Index](#Index) | (Index) En sekvens av poster som innehåller identifierande text följd av referenselement som pekar på förekomster av den angivna texten i dokumentets huvudtext. |
| [L](#L) | (List) En sekvens av objekt med liknande betydelse och vikt. Dess omedelbara underordnade bör vara en valfri bildtext (strukturtyp Caption) följt av ett eller flera listobjekt (strukturtyp LI). |
| [Lbl](#Lbl) | (Label) Ett namn eller nummer som särskiljer ett givet objekt från andra i samma lista eller annan grupp av liknande objekt. |
| [LBody](#LBody) | (List body) Det beskrivande innehållet i ett listobjekt. I en ordboklista, till exempel, innehåller det definitionen av termen. Det kan antingen innehålla innehållet direkt eller ha andra BLSE:er, eventuellt inklusive nästlade listor, som barn. |
| [LI](#LI) | (List item) En enskild medlem i en lista. Dess barn kan vara en eller flera etiketter, listinnehåll eller båda (strukturtyper Lbl eller LBody). |
| [Link](#Link) | (Link) En association mellan en del av ILSE:s innehåll och en motsvarande länkanmärkning eller -anmärkningar. Dess barn bör vara ett eller flera innehållselement eller underordnade ILSE:er samt ett eller flera objektreferenser som identifierar de associerade länkanmärkningarna. |
| [NonStruct](#NonStruct) | (Nonstructural element) Ett grupperingselement utan inneboende strukturell betydelse; det tjänar enbart för gruppering. Denna typ av element skiljer sig från en division (strukturtyp Div) genom att det inte får tolkas eller exporteras till andra dokumentformat; däremot ska dess underordnade element behandlas normalt. |
| [Note](#Note) | (Note) Ett objekt med förklarande text, såsom en fotnot eller slutnot, som refereras till från dokumentets brödtext. Det kan ha en etikett (strukturtyp Lbl) som barn. Noten kan inkluderas som ett barn till strukturelementet i brödtexten som refererar till den, eller den kan placeras någon annanstans (t.ex. i en slutnotsektion) och nås via en referens (strukturtyp Reference). Tagged PDF föreskriver inte placeringen av fotnoter i sidans innehållsordning. De kan vara antingen inline eller i slutet av sidan, enligt den konformerande författarens bedömning. |
| [P](#P) | (Paragraph) En låg nivå division av text. |
| [Part](#Part) | (Part) En storskalig indelning av ett dokument. Denna typ av element är lämplig för att gruppera artiklar eller sektioner. |
| [Private](#Private) | (Private element) Ett grupperingselement som innehåller privat innehåll som tillhör den applikation som skapar det. Den strukturella betydelsen av denna typ av element är ospecificerad och ska helt bestämmas av den konformerande författaren. Varken Private‑elementet eller någon av dess underordnade får tolkas eller exporteras till andra dokumentformat. |
| [Quote](#Quote) | (Quotation) En inline‑del av text som tillskrivs någon annan än författaren till den omgivande texten. Det citerade texten bör finnas inline inom ett enda stycke. Detta skiljer sig från blocknivåelementet BlockQuote, som består av ett eller flera kompletta stycken (eller andra element som presenteras som om de vore kompletta stycken). |
| [RB](#RB) | (Ruby base text) Den fullstora texten som ruby‑annoteringen appliceras på. RB kan innehålla text, andra inline‑element eller en blandning av båda. Den kan ha RubyAlign‑attributet. |
| [Reference](#Reference) | (Reference) En hänvisning till innehåll någon annanstans i dokumentet. |
| [RP](#RP) | (Ruby punctuation) Interpunktion som omger ruby‑annoteringstexten. Den används endast när en ruby‑annotering inte kan formateras korrekt i ruby‑stil och istället formateras som en vanlig kommentar, eller när den formateras som en warichu. Den innehåller text (vanligtvis ett enda VÄNSTER‑ eller HÖGER‑PARANTES‑tecken eller liknande parentesliknande tecken). |
| [RT](#RT) | (Ruby annotation text) Den mindre texten som ska placeras intill ruby-bastexten. Den kan innehålla text, andra inline‑element eller en blandning av båda. Den kan ha attributen RubyAlign och RubyPosition. |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) En sidnotering (annotation) skriven i en mindre textstorlek och placerad intill bastexten den hänvisar till. Ett Ruby‑element kan också innehålla RB-, RT- och RP‑elementen. (Ruby) Omslaget runt hela ruby‑samlingen. Det ska innehålla ett RB‑element följt av antingen ett RT‑element eller en grupp med tre element bestående av RP, RT och RP. Ruby‑element och deras innehållselement får inte brytas över flera rader. |
| [Sect](#Sect) | (Section) En behållare för att gruppera relaterade innehållselement. |
| [Span](#Span) | (Span) En generisk inline‑textdel utan särskilda inneboende egenskaper. Den kan exempelvis användas för att avgränsa ett textintervall med en viss uppsättning stilattribut. |
| [Table](#Table) | (Table) En tvådimensionell layout av rektangulära dataceller, eventuellt med en komplex understruktur. Den innehåller antingen en eller flera tabellrader (strukturtyp TR) som barn; eller ett valfritt tabellhuvud (strukturtyp THead) följt av en eller flera tabellkropps‑element (strukturtyp TBody) och ett valfritt tabellfot (strukturtyp TFoot). Dessutom kan en tabell ha en rubrik (strukturtyp Caption) som sitt första eller sista barn. |
| [TBody](#TBody) | (Table body row group; PDF 1.5) En grupp rader som utgör huvudkropps­delen av en tabell. Om tabellen delas över flera sidor kan kropps­området brytas vid en radgräns. En tabell kan ha flera TBody‑element för att möjliggöra ritning av en ram eller bakgrund för en uppsättning rader. |
| [TD](#TD) | (Table data cell) En tabellcell som innehåller data som är en del av tabellens innehåll. |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) En grupp rader som utgör foten på en tabell. Om tabellen delas över flera sidor kan dessa rader återges längst ner i varje tabellfragment (även om det bara finns ett TFoot‑element.) |
| [TH](#TH) | (Table header cell) En tabellcell som innehåller rubriktext som beskriver en eller flera rader eller kolumner i tabellen. |
| [THead](#THead) | (Table header row group; PDF 1.5) En grupp rader som utgör tabellens huvud. Om tabellen delas över flera sidor kan dessa rader återges högst upp i varje tabellfragment (även om det bara finns ett THead‑element). |
| [TOC](#TOC) | (Table of contents) En lista bestående av innehållsförteckningspost‑poster (strukturtyp TOCI) och/eller andra nästlade innehållsförteckningsposter (TOC). En TOC‑post som bara innehåller TOCI‑poster representerar en platt hierarki. En TOC‑post som innehåller andra nästlade TOC‑poster (och eventuellt TOCI‑poster) representerar en mer komplex hierarki. Idealiskt speglar hierarkin för en TOC‑post på toppnivå strukturen i dokumentets huvuddel. |
| [TOCI](#TOCI) | (Table of contents item) En enskild medlem i en innehållsförteckning. Denna posts barn kan vara någon av följande strukturtyper: Lbl – En etikett Reference – En referens till titeln och sidnumret NonStruct – Icke‑struktur‑element för att omsluta ett ledartelement P – Beskrivande text TOC – Innehållsförteckningselement för hierarkiska innehållsförteckningar, enligt beskrivningen för TOC‑posten. |
| [TR](#TR) | (Table row) En rad med rubriker eller data i en tabell. Den kan innehålla tabellrubricerceller och tabelldataceller (strukturtyper TH och TD). |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) En kommentar eller annotation i en mindre textstorlek och formaterad på två mindre rader inom höjden av den innehållande textraden och placerad efter (inline) bastexten som den hänvisar till. Ett Warichu‑element kan också innehålla WT‑ och WP‑elementen. (Warichu) Omslaget runt hela warichu‑samlingen. Det kan innehålla en grupp med tre element bestående av WP, WT och WP. Warichu‑element (och deras innehållselement) kan radbrytas över flera rader enligt warichu‑brytningsreglerna beskrivna i den japanska industristandarden (JIS) X 4051-1995. |
| [WP](#WP) | (Warichu punctuation) Interpunktionen som omger WT‑texten. Den innehåller text (vanligtvis en ensam VÄNSTER‑ eller HÖGER‑PARANTES eller liknande parentesliknande tecken). Enligt JIS X 4051-1995 kan parenteserna som omger ett warichu konverteras till ett MELLANSLAG (nominalt 1/4 EM i bredd) efter formatterarens gottfinnande. |
| [WT](#WT) | (Warichu text) Den mindre textstorleken för en warichu‑kommentar som formateras i två rader och placeras mellan omgivande WP‑element. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | Hämtar kategori för Standard Structure Type. |
| [getTag](#getTag--) | Hämtar taggnamn för {@code StructureElement}. |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | Utför en explicit konvertering från {@link String} till {@link StructureTypeStandard}. |
| [toString](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotation; PDF 1.5) En association mellan en del av ILSE:s innehåll och en motsvarande PDF-annotation. Annot ska användas för alla PDF-annotationer förutom länkanotationer och widgetannotationer.

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Article) En relativt självständig textmassa som utgör en enda berättelse eller exposition. Artiklar bör vara åtskilda; det vill säga, de bör inte innehålla andra artiklar som beståndsdelar.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Bibliography entry) En referens som identifierar den externa källan till något citerat innehåll. Den kan innehålla en etikett (strukturtyp Lbl) som ett underordnat element. Även om ett bibliografipost sannolikt inkluderar komponentdelar som identifierar det citerade innehållets författare, verk, förlag osv., definieras inga standardstrukturtyper på denna detaljnivå.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Block quotation) En del av text som består av ett eller flera stycken som tillskrivs någon annan än författaren till den omgivande texten.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Caption) En kort textdel som beskriver en tabell eller figur.

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Code) Ett fragment av datorprogramtext.

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Division) Ett generiskt blocknivåelement eller en grupp av element.

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Document) Ett komplett dokument. Detta är rot‑elementet i vilket strukturträd som helst som innehåller flera delar eller flera artiklar.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Figure) Ett objekt av grafiskt innehåll. Dess placering kan specificeras med layoutattributet Placement.

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Form) En widget‑annotation som representerar ett interaktivt formulärfält.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) En matematisk formel. Denna strukturtyp är endast användbar för att identifiera ett helt innehållselement som en formel. Inga standardstrukturtyper är definierade för att identifiera enskilda komponenter inom formeln. Ur ett formateringsperspektiv ska formeln behandlas på liknande sätt som en figur (strukturtyp Figure).

### H {#H}
```
public static final StructureTypeStandard H
```

(Heading) En etikett för en underindelning av ett dokuments innehåll. Den bör vara det första barnet i den division som den rubriker.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

Rubrik nivå 1, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

Rubrik nivå 2, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Rubrik nivå 3, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Rubrik nivå 4, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Rubrik nivå 5, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Rubrik nivå 6, för användning i kompatibla skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå.

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Index) En sekvens av poster som innehåller identifierande text följd av referenselement som pekar på förekomster av den angivna texten i dokumentets huvudtext.

### L {#L}
```
public static final StructureTypeStandard L
```

(List) En sekvens av objekt med liknande betydelse och vikt. Dess omedelbara underordnade bör vara en valfri bildtext (strukturtyp Caption) följt av ett eller flera listobjekt (strukturtyp LI).

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Label) Ett namn eller nummer som särskiljer ett givet objekt från andra i samma lista eller annan grupp av liknande objekt.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(List body) Det beskrivande innehållet i ett listobjekt. I en ordboklista, till exempel, innehåller det definitionen av termen. Det kan antingen innehålla innehållet direkt eller ha andra BLSE:er, eventuellt inklusive nästlade listor, som barn.

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(List item) En enskild medlem i en lista. Dess barn kan vara en eller flera etiketter, listinnehåll eller båda (strukturtyper Lbl eller LBody).

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Link) En association mellan en del av ILSE:s innehåll och en motsvarande länkanmärkning eller -anmärkningar. Dess barn bör vara ett eller flera innehållselement eller underordnade ILSE:er samt ett eller flera objektreferenser som identifierar de associerade länkanmärkningarna.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Nonstructural element) Ett grupperingselement utan inneboende strukturell betydelse; det tjänar enbart för gruppering. Denna typ av element skiljer sig från en division (strukturtyp Div) genom att det inte får tolkas eller exporteras till andra dokumentformat; däremot ska dess underordnade element behandlas normalt.

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Note) Ett objekt med förklarande text, såsom en fotnot eller slutnot, som refereras till från dokumentets brödtext. Det kan ha en etikett (strukturtyp Lbl) som barn. Noten kan inkluderas som ett barn till strukturelementet i brödtexten som refererar till den, eller den kan placeras någon annanstans (t.ex. i en slutnotsektion) och nås via en referens (strukturtyp Reference). Tagged PDF föreskriver inte placeringen av fotnoter i sidans innehållsordning. De kan vara antingen inline eller i slutet av sidan, enligt den konformerande författarens bedömning.

### P {#P}
```
public static final StructureTypeStandard P
```

(Paragraph) En låg nivå division av text.

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Part) En storskalig indelning av ett dokument. Denna typ av element är lämplig för att gruppera artiklar eller sektioner.

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Private element) Ett grupperingselement som innehåller privat innehåll som tillhör den applikation som skapar det. Den strukturella betydelsen av denna typ av element är ospecificerad och ska helt bestämmas av den konformerande författaren. Varken Private‑elementet eller någon av dess underordnade får tolkas eller exporteras till andra dokumentformat.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Quotation) En inline‑del av text som tillskrivs någon annan än författaren till den omgivande texten. Det citerade texten bör finnas inline inom ett enda stycke. Detta skiljer sig från blocknivåelementet BlockQuote, som består av ett eller flera kompletta stycken (eller andra element som presenteras som om de vore kompletta stycken).

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Ruby base text) Den fullstora texten som ruby‑annoteringen appliceras på. RB kan innehålla text, andra inline‑element eller en blandning av båda. Den kan ha RubyAlign‑attributet.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Reference) En hänvisning till innehåll någon annanstans i dokumentet.

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Ruby punctuation) Interpunktion som omger ruby‑annoteringstexten. Den används endast när en ruby‑annotering inte kan formateras korrekt i ruby‑stil och istället formateras som en vanlig kommentar, eller när den formateras som en warichu. Den innehåller text (vanligtvis ett enda VÄNSTER‑ eller HÖGER‑PARANTES‑tecken eller liknande parentesliknande tecken).

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Ruby annotation text) Den mindre texten som ska placeras intill ruby-bastexten. Den kan innehålla text, andra inline‑element eller en blandning av båda. Den kan ha attributen RubyAlign och RubyPosition.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) En sidnotering (annotation) skriven i en mindre textstorlek och placerad intill bastexten den hänvisar till. Ett Ruby‑element kan också innehålla RB-, RT- och RP‑elementen. (Ruby) Omslaget runt hela ruby‑samlingen. Det ska innehålla ett RB‑element följt av antingen ett RT‑element eller en grupp med tre element bestående av RP, RT och RP. Ruby‑element och deras innehållselement får inte brytas över flera rader.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) En behållare för att gruppera relaterade innehållselement.

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) En generisk inline‑textdel utan särskilda inneboende egenskaper. Den kan exempelvis användas för att avgränsa ett textintervall med en viss uppsättning stilattribut.

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) En tvådimensionell layout av rektangulära dataceller, eventuellt med en komplex understruktur. Den innehåller antingen en eller flera tabellrader (strukturtyp TR) som barn; eller ett valfritt tabellhuvud (strukturtyp THead) följt av en eller flera tabellkropps‑element (strukturtyp TBody) och ett valfritt tabellfot (strukturtyp TFoot). Dessutom kan en tabell ha en rubrik (strukturtyp Caption) som sitt första eller sista barn.

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) En grupp rader som utgör huvudkropps­delen av en tabell. Om tabellen delas över flera sidor kan kropps­området brytas vid en radgräns. En tabell kan ha flera TBody‑element för att möjliggöra ritning av en ram eller bakgrund för en uppsättning rader.

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) En tabellcell som innehåller data som är en del av tabellens innehåll.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) En grupp rader som utgör foten på en tabell. Om tabellen delas över flera sidor kan dessa rader återges längst ner i varje tabellfragment (även om det bara finns ett TFoot‑element.)

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) En tabellcell som innehåller rubriktext som beskriver en eller flera rader eller kolumner i tabellen.

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) En grupp rader som utgör tabellens huvud. Om tabellen delas över flera sidor kan dessa rader återges högst upp i varje tabellfragment (även om det bara finns ett THead‑element).

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) En lista bestående av innehållsförteckningspost‑poster (strukturtyp TOCI) och/eller andra nästlade innehållsförteckningsposter (TOC). En TOC‑post som bara innehåller TOCI‑poster representerar en platt hierarki. En TOC‑post som innehåller andra nästlade TOC‑poster (och eventuellt TOCI‑poster) representerar en mer komplex hierarki. Idealiskt speglar hierarkin för en TOC‑post på toppnivå strukturen i dokumentets huvuddel.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) En enskild medlem i en innehållsförteckning. Denna posts barn kan vara någon av följande strukturtyper: Lbl – En etikett Reference – En referens till titeln och sidnumret NonStruct – Icke‑struktur‑element för att omsluta ett ledartelement P – Beskrivande text TOC – Innehållsförteckningselement för hierarkiska innehållsförteckningar, enligt beskrivningen för TOC‑posten.

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) En rad med rubriker eller data i en tabell. Den kan innehålla tabellrubricerceller och tabelldataceller (strukturtyper TH och TD).

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) En kommentar eller annotation i en mindre textstorlek och formaterad på två mindre rader inom höjden av den innehållande textraden och placerad efter (inline) bastexten som den hänvisar till. Ett Warichu‑element kan också innehålla WT‑ och WP‑elementen. (Warichu) Omslaget runt hela warichu‑samlingen. Det kan innehålla en grupp med tre element bestående av WP, WT och WP. Warichu‑element (och deras innehållselement) kan radbrytas över flera rader enligt warichu‑brytningsreglerna beskrivna i den japanska industristandarden (JIS) X 4051-1995.

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) Interpunktionen som omger WT‑texten. Den innehåller text (vanligtvis en ensam VÄNSTER‑ eller HÖGER‑PARANTES eller liknande parentesliknande tecken). Enligt JIS X 4051-1995 kan parenteserna som omger ett warichu konverteras till ett MELLANSLAG (nominalt 1/4 EM i bredd) efter formatterarens gottfinnande.

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu text) Den mindre textstorleken för en warichu‑kommentar som formateras i två rader och placeras mellan omgivande WP‑element.

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

Hämtar kategori för Standard Structure Type.

**Returns:**
Värde: Kategori för Standard Structure Type.

### getTag {#getTag--}
```
public final String getTag()
```

Hämtar taggnamn för {@code StructureElement}.

**Returns:**
Taggnamn för {@code StructureElement}.

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
Utför en explicit konvertering från {@link String} till {@link StructureTypeStandard}.

### toString {#toString--}
```
public String toString()
```

Returnerar en sträng som representerar det aktuella objektet.

**Returns:**
Sträng som representerar det aktuella objektet.
