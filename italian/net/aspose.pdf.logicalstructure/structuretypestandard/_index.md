---
title: "Classe StructureTypeStandard"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.LogicalStructure.StructureTypeStandard classe. Rappresenta i tipi di struttura standard"
type: docs
weight: 6870
url: /it/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

Rappresenta i Tipi di Struttura Standard.

```csharp
public sealed class StructureTypeStandard
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Ottiene la categoria del tipo di struttura standard. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Ottiene il nome del tag di [`StructureElement`](../structureelement/). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Esegue una conversione esplicita da String a `StructureTypeStandard`. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation; PDF 1.5) Un'associazione tra una parte del contenuto dell'ILSE e una annotazione PDF corrispondente. Annot deve essere usato per tutte le annotazioni PDF eccetto le annotazioni di collegamento e le annotazioni widget. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Article) Un corpo di testo relativamente autonomo che costituisce una singola narrazione o esposizione. Gli articoli dovrebbero essere disgiunti; cioè, non dovrebbero contenere altri articoli come elementi costitutivi. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Bibliography entry) Un riferimento che identifica la fonte esterna di un contenuto citato. Può contenere un'etichetta (tipo di struttura Lbl) come figlio. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Block quotation) Una porzione di testo composta da uno o più paragrafi attribuiti a qualcuno diverso dall'autore del testo circostante. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Caption) Una breve porzione di testo che descrive una tabella o una figura. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Code) Un frammento di testo di programma informatico. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) Un elemento generico a livello di blocco o un gruppo di elementi. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Document) Un documento completo. Questo è l'elemento radice di qualsiasi albero di struttura contenente più parti o più articoli. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figure) Un elemento di contenuto grafico. Il suo posizionamento può essere specificato con l'attributo di layout Placement. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Form) Un'annotazione widget che rappresenta un campo modulo interattivo. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formula) Una formula matematica. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Heading) Un'etichetta per una suddivisione del contenuto di un documento. Dovrebbe essere il primo figlio della divisione che introduce. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Intestazione di livello 1, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Intestazione di livello 2, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Intestazione di livello 3, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Intestazione di livello 4, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Intestazione di livello 5, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Intestazione di livello 6, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) Una sequenza di voci contenenti testo identificativo accompagnato da elementi di riferimento che indicano le occorrenze del testo specificato nel corpo principale di un documento. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (List) Una sequenza di elementi di significato e importanza simili. I suoi figli immediati dovrebbero essere una didascalia opzionale (tipo di struttura Caption) seguita da uno o più elementi di lista (tipo di struttura LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Label) Un nome o un numero che distingue un dato elemento dagli altri nella stessa lista o in altro gruppo di elementi simili. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (List body) Il contenuto descrittivo di un elemento di lista. In una lista dizionario, ad esempio, contiene la definizione del termine. Può contenere direttamente il contenuto o avere altri BLSE, forse includendo liste annidate, come figli. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (List item) Un membro individuale di una lista. I suoi figli possono essere una o più etichette, corpi di lista o entrambi (tipi di struttura Lbl o LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Link) Un'associazione tra una parte del contenuto dell'ILSE e una o più annotazioni di collegamento corrispondenti. I suoi figli dovrebbero essere uno o più elementi di contenuto o ILSE figli e uno o più riferimenti a oggetti che identificano le annotazioni di collegamento associate. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Nonstructural element) Un elemento di raggruppamento privo di significato strutturale intrinseco; serve esclusivamente a scopi di raggruppamento. Questo tipo di elemento differisce da una divisione (tipo di struttura Div) perché non deve essere interpretato o esportato in altri formati di documento; tuttavia, i suoi discendenti devono essere elaborati normalmente. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Note) Un elemento di testo esplicativo, come una nota a piè di pagina o una nota finale, a cui si fa riferimento dal corpo del documento. Può avere un'etichetta (tipo di struttura Lbl) come figlio. La nota può essere inclusa come figlio dell'elemento strutturale nel testo principale che la richiama, oppure può essere inserita altrove (ad esempio in una sezione di note finali) e accessibile tramite un riferimento (tipo di struttura Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Paragraph) Una divisione di testo a basso livello. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Part) Una divisione su larga scala di un documento. Questo tipo di elemento è appropriato per raggruppare articoli o sezioni. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Private element) Un elemento di raggruppamento contenente contenuto privato appartenente all'applicazione che lo produce. Il significato strutturale di questo tipo di elemento non è specificato e sarà determinato interamente dallo scrittore conforme. Né l'elemento Private né alcuno dei suoi discendenti dovranno essere interpretati o esportati in altri formati di documento. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Quotation) Una porzione di testo in linea attribuita a qualcuno diverso dall'autore del testo circostante. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Ruby base text) Il testo a grandezza piena a cui viene applicata l'annotazione ruby. RB può contenere testo, altri elementi in linea o una combinazione di entrambi. Può avere l'attributo RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Reference) Una citazione a contenuto presente altrove nel documento. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ruby punctuation) Punteggiatura che circonda il testo dell'annotazione ruby. Viene usata solo quando un'annotazione ruby non può essere formattata correttamente in stile ruby e invece è formattata come commento normale, o quando è formattata come warichu. Contiene testo (di solito una singola parentesi SINISTRA o DESTRA o un carattere di parentesi simile). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Ruby annotation text) Il testo di dimensione più piccola che deve essere posizionato adiacente al testo base ruby. Può contenere testo, altri elementi in linea o una combinazione di entrambi. Può avere gli attributi RubyAlign e RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) Una nota laterale (annotazione) scritta in una dimensione di testo più piccola e posizionata adiacente al testo base a cui si riferisce. Un elemento Ruby può contenere anche gli elementi RB, RT e RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Section) Un contenitore per raggruppare elementi di contenuto correlati. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) Una porzione di testo in linea generica priva di caratteristiche intrinseche particolari. Può essere usata, ad esempio, per delimitare un intervallo di testo con un determinato insieme di attributi di stile. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Table) Un layout bidimensionale di celle dati rettangolari, possibilmente con una struttura secondaria complessa. Contiene una o più righe di tabella (tipo di struttura TR) come figli; oppure un'intestazione di tabella opzionale (tipo di struttura THead) seguita da una o più sezioni di corpo tabella (tipo di struttura TBody) e un piè di pagina di tabella opzionale (tipo di struttura TFoot). Inoltre, una tabella può avere una didascalia (tipo di struttura Caption) come suo primo o ultimo figlio. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Table body row group; PDF 1.5) Un gruppo di righe che costituiscono la parte principale del corpo di una tabella. Se la tabella è divisa su più pagine, l'area del corpo può essere interrotta su un confine di riga. Una tabella può avere più elementi TBody per consentire il disegno di un bordo o di uno sfondo per un insieme di righe. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Table data cell) Una cella di tabella contenente dati che fanno parte del contenuto della tabella. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Table footer row group; PDF 1.5) Un gruppo di righe che costituiscono il piè di pagina di una tabella. Se la tabella è divisa su più pagine, queste righe possono essere ridisegnate nella parte inferiore di ogni frammento di tabella (anche se esiste un solo elemento TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Table header cell) Una cella di tabella contenente testo di intestazione che descrive una o più righe o colonne della tabella. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Table header row group; PDF 1.5) Un gruppo di righe che costituiscono l'intestazione di una tabella. Se la tabella è divisa su più pagine, queste righe possono essere ridisegnate nella parte superiore di ogni frammento di tabella (anche se esiste un solo elemento THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Table of contents) Un elenco composto da voci di elementi dell'indice (tipo di struttura TOCI) e/o altre voci di indice annidate (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Table of contents item) Un membro individuale di un indice. I figli di questa voce possono essere uno dei seguenti tipi di struttura: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Table row) Una riga di intestazioni o dati in una tabella. Può contenere celle di intestazione della tabella e celle di dati della tabella (tipi di struttura TH e TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) Un commento o annotazione in una dimensione di testo più piccola e formattata su due linee più piccole all'interno dell'altezza della riga di testo contenente e posizionata subito dopo (inline) il testo base a cui si riferisce. Un elemento Warichu può anche contenere gli elementi WT e WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Warichu punctuation) La punteggiatura che circonda il testo WT. Contiene testo (di solito una singola parentesi SINISTRA o DESTRA o un carattere di parentesi simile). Secondo JIS X 4051-1995, le parentesi che circondano un warichu possono essere convertite in uno SPAZIO (nominalmente 1/4 EM in larghezza) a discrezione del formattatore. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Warichu text) Il testo di dimensione più piccola di un commento warichu che è formattato in due linee e posizionato tra gli elementi WP circostanti. |

### Vedi anche

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


