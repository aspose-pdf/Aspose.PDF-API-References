---
title: "StructureTypeStandard"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar standardstrukturtyper."
type: docs
weight: 560
url: /sv/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Representerar standardstrukturtyper.

Typen StructureTypeStandard exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| tag | Hämtar taggnamnet för [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/). |
| kategori | Hämtar kategori för Standard Structure Type. |
| DOCUMENT | (Document) Ett komplett dokument. Detta är rot‑elementet i alla strukturelementträd som innehåller flera delar eller flera artiklar. |
| PART | (Part) En storskalig indelning av ett dokument. Denna typ av element är lämplig för att gruppera artiklar eller sektioner. |
| ART | (Article) En relativt självständig textkropp som utgör en enskild berättelse eller exposition. Artiklar bör vara separata; det vill säga, de bör inte innehålla andra artiklar som beståndsdelar. |
| SECT | (Section) En behållare för att gruppera relaterade innehållselement. |
| DIV | (Division) Ett generiskt blocknivåelement eller en grupp av element. |
| BLOCK_QUOTE | (Block quotation) En del av text bestående av ett eller flera stycken som tillskrivs någon annan än författaren till den omgivande texten. |
| CAPTION | (Caption) En kort textdel som beskriver en tabell eller figur. |
| TOC | (Innehållsförteckning) En lista bestående av poster för innehållsförteckningsobjekt (strukturtyp TOCI) och/eller andra nästlade innehållsförteckningsposter (TOC). |
| TOCI | (Innehållsförteckningsobjekt) Enskild medlem i en innehållsförteckning. Detta posts barn kan vara någon av följande strukturtyper: |
| INDEX | (Index) En sekvens av poster som innehåller identifierande text tillsammans med referenselement som pekar på förekomster av den angivna texten i dokumentets huvudtext. |
| NON_STRUCT | (Icke‑strukturellt element) Ett grupperingselement utan inneboende strukturell betydelse; det tjänar enbart för gruppering. Denna typ av element skiljer sig från en division (strukturtyp Div) genom att det inte får tolkas eller exporteras till andra dokumentformat; däremot ska dess underordnade behandlas normalt. |
| PRIVATE | (Privat element) Ett grupperingselement som innehåller privat innehåll som tillhör den applikation som producerar det. Den strukturella betydelsen av denna typ av element är ospecificerad och ska bestämmas helt av den konformerande skribenten. Varken det privata elementet eller någon av dess underordnade får tolkas eller exporteras till andra dokumentformat. |
| P | (Stycke) En låg nivå indelning av text. |
| H | (Rubrik) En etikett för en underindelning av ett dokuments innehåll. Den bör vara det första barnet till den division som den rubriker. |
| H1 | Rubrik nivå 1, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| H2 | Rubrik nivå 2, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| H3 | Rubrik nivå 3, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| H4 | Rubrik nivå 4, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| H5 | Rubrik nivå 5, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| H6 | Rubrik nivå 6, för användning i konformerande skribenter som inte kan hierarkiskt nästla sina sektioner och därför inte kan bestämma rubriknivån utifrån dess nästlingsnivå. |
| L | (List) En sekvens av objekt med liknande betydelse och vikt. Dess omedelbara barn bör vara en valfri rubrik (strukturtyp Caption) följt av ett eller flera listobjekt (strukturtyp LI). |
| LI | (List item) En enskild medlem i en lista. Dess barn kan vara en eller flera etiketter, listkroppar eller båda (strukturtyper Lbl eller LBody). |
| LBL | (Label) Ett namn eller nummer som särskiljer ett givet objekt från andra i samma lista eller annan grupp av liknande objekt. |
| L_BODY | (List body) Det beskrivande innehållet för ett listobjekt. I en ordboklista, till exempel, innehåller den definitionen av termen. Den kan antingen innehålla innehållet direkt eller ha andra BLSEs, eventuellt inklusive nästlade listor, som barn. |
| TABLE | (Table) En tvådimensionell layout av rektangulära dataceller, eventuellt med en komplex understruktur. Den innehåller antingen en eller flera tabellrader (strukturtyp TR) som barn; eller en valfri tabellhuvud (strukturtyp THead) följt av en eller flera tabellkropps‑element (strukturtyp TBody) och ett valfritt tabellfot (strukturtyp TFoot). Dessutom kan en tabell ha en rubrik (strukturtyp Caption) som sitt första eller sista barn. |
| T_HEAD | (Table header row group; PDF 1.5) En grupp rader som utgör tabellens rubrik. Om tabellen delas över flera sidor kan dessa rader ritas om högst upp på varje tabellfragment (även om det bara finns ett THead‑element). |
| T_BODY | (Table body row group; PDF 1.5) En grupp rader som utgör huvuddelen av en tabell. Om tabellen delas över flera sidor kan kroppsområdet brytas upp vid en radgräns. En tabell kan ha flera TBody‑element för att möjliggöra ritning av en ram eller bakgrund för en uppsättning rader. |
| T_FOOT | (Table footer row group; PDF 1.5) En grupp rader som utgör tabellens fot. Om tabellen delas över flera sidor kan dessa rader ritas om längst ner på varje tabellfragment (även om det bara finns ett TFoot‑element.) |
| TR | (Table row) En rad med rubriker eller data i en tabell. Den kan innehålla tabellrubrikceller och tabelldataceller (strukturtyper TH och TD). |
| TH | (Table header cell) En tabellcell som innehåller rubriktext som beskriver en eller flera rader eller kolumner i tabellen. |
| TD | (Table data cell) En tabellcell som innehåller data som är en del av tabellens innehåll. |
| SPAN | (Span) En generell inline‑del av text utan särskilda inneboende egenskaper. Den kan till exempel användas för att avgränsa ett textintervall med en given uppsättning stilattribut. |
| QUOTE | (Quotation) En inline‑del av text som tillskrivs någon annan än författaren till den omgivande texten. |
| NOTERING | (Note) Ett föremål av förklarande text, såsom en fotnot eller slutnot, som refereras till från dokumentets brödtext. Det kan ha en etikett (strukturtyp Lbl) som barn. Noten kan inkluderas som ett barn till strukturelementet i brödtexten som refererar till den, eller så kan den inkluderas någon annanstans (t.ex. i en slutnotsektion) och nås via en referens (strukturtyp Reference). |
| REFERENCE | (Reference) En citering till innehåll någon annanstans i dokumentet. |
| BIB_ENTRY | (Bibliography entry) En referens som identifierar den externa källan till något citerat innehåll. Den kan innehålla en etikett (strukturtyp Lbl) som ett underordnat element. |
| CODE | (Code) Ett fragment av datorprogramtext. |
| LINK | (Link) En association mellan en del av ILSE:s innehåll och en motsvarande länkanmärkning eller länkanmärkningar. Dess barn bör vara ett eller flera innehållselement eller underordnade ILSE:er samt ett eller flera objektreferenser som identifierar de associerade länkanmärkningarna. |
| ANNOT | (Annotation; PDF 1.5) En association mellan en del av ILSE:s innehåll och en motsvarande PDF-annotation. Annot ska användas för alla PDF-annotationer förutom länkanmärkningar och widget-annotationer. |
| RUBY | (Ruby; PDF 1.5) En fotnot (annotation) skriven i en mindre textstorlek och placerad intill bastexten som den hänvisar till. Ett Ruby-element kan också innehålla RB-, RT- och RP-elementen. |
| RB | (Ruby base text) Den fullstora texten som ruby-annotation appliceras på. RB kan innehålla text, andra inline-element eller en blandning av båda. Den kan ha RubyAlign-attributet. |
| RT | (Ruby annotation text) Den mindre texten som ska placeras intill ruby-bastexten. Den kan innehålla text, andra inline-element eller en blandning av båda. Den kan ha RubyAlign- och RubyPosition-attributen. |
| RP | (Ruby punctuation) Interpunktion som omger ruby-annotationstexten. Den används endast när en ruby-annotation inte kan formateras korrekt i ruby-stil och istället formateras som en vanlig kommentar, eller när den formateras som en warichu. Den innehåller text (vanligtvis ett enda VÄNSTER- eller HÖGER-PARENTES eller liknande avgränsningstecken). |
| WARICHU | (Warichu; PDF 1.5) En kommentar eller annotation i en mindre textstorlek och formaterad på två mindre rader inom höjden av den omgivande textraden och placerad efter (inline) bastexten som den hänvisar till. Ett Warichu-element kan också innehålla WT- och WP-elementen. |
| WT | (Warichu text) Den mindre texten i en warichu-kommentar som formateras i två rader och placeras mellan omgivande WP-element. |
| WP | (Warichu punctuation) Interpunktionen som omger WT-texten. Den innehåller text (vanligtvis ett enda VÄNSTER- eller HÖGER-PARENTES eller liknande avgränsningstecken). Enligt JIS X 4051-1995 kan parenteserna som omger en warichu omvandlas till ett MELLANSLAG (normalt 1/4 EM i bredd) efter formatterarens gottfinnande. |
| FIGURE | (Figure) Ett grafiskt innehållselement. Dess placering kan specificeras med layoutattributet Placement. |
| FORMEL | (Formel) En matematisk formel. |
| FORM | (Formulär) En widget-annotation som representerar ett interaktivt formulärfält. |

### Se även

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

