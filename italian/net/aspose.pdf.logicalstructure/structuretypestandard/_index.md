---
title: Class StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.StructureTypeStandard. Rappresenta i Tipi di Struttura Standard
type: docs
weight: 6730
url: /it/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## Classe StructureTypeStandard

Rappresenta i Tipi di Struttura Standard.

```csharp
public sealed class StructureTypeStandard
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Ottiene la categoria del Tipo di Struttura Standard. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Ottiene il nome del tag di [`StructureElement`](../structureelement/). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Esegue una conversione esplicita da String a `StructureTypeStandard`. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotazione; PDF 1.5) Un'associazione tra una porzione del contenuto dell'ILSE e una corrispondente annotazione PDF. Annot deve essere utilizzato per tutte le annotazioni PDF tranne le annotazioni di collegamento e le annotazioni widget. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Articolo) Un corpo di testo relativamente autonomo che costituisce una singola narrazione o esposizione. Gli articoli dovrebbero essere disgiunti; cioè, non dovrebbero contenere altri articoli come elementi costitutivi. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Voce bibliografica) Un riferimento che identifica la fonte esterna di alcuni contenuti citati. Può contenere un'etichetta (tipo di struttura Lbl) come figlio. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Citazione a blocco) Una porzione di testo costituita da uno o più paragrafi attribuiti a qualcuno diverso dall'autore del testo circostante. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Didascalia) Una breve porzione di testo che descrive una tabella o una figura. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Codice) Un frammento di testo di programma informatico. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Divisione) Un elemento generico a livello di blocco o gruppo di elementi. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Documento) Un documento completo. Questo è l'elemento radice di qualsiasi albero di struttura contenente più parti o più articoli. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figura) Un elemento di contenuto grafico. La sua posizione può essere specificata con l'attributo di layout Placement. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Modulo) Un'annotazione widget che rappresenta un campo modulo interattivo. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formula) Una formula matematica. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Intestazione) Un'etichetta per una suddivisione del contenuto di un documento. Dovrebbe essere il primo figlio della divisione che guida. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Intestazione di Livello 1, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Intestazione di Livello 2, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Intestazione di Livello 3, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Intestazione di Livello 4, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Intestazione di Livello 5, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Intestazione di Livello 6, da utilizzare in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Indice) Una sequenza di voci contenenti testo identificativo accompagnato da elementi di riferimento che indicano le occorrenze del testo specificato nel corpo principale di un documento. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (Elenco) Una sequenza di elementi di significato e importanza simili. I suoi figli immediati dovrebbero essere una didascalia opzionale (tipo di struttura Caption) seguita da uno o più elementi dell'elenco (tipo di struttura LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Etichetta) Un nome o numero che distingue un dato elemento dagli altri nella stessa lista o altro gruppo di elementi simili. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (Corpo dell'elenco) Il contenuto descrittivo di un elemento dell'elenco. In un elenco di dizionario, ad esempio, contiene la definizione del termine. Può contenere direttamente il contenuto o avere altri BLSE, forse includendo elenchi annidati, come figli. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (Elemento dell'elenco) Un membro individuale di un elenco. I suoi figli possono essere una o più etichette, corpi dell'elenco, o entrambi (tipi di struttura Lbl o LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Collegamento) Un'associazione tra una porzione del contenuto dell'ILSE e una corrispondente annotazione o annotazioni di collegamento. I suoi figli dovrebbero essere uno o più elementi di contenuto o ILSE figlio e uno o più riferimenti a oggetti che identificano le annotazioni di collegamento associate. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Elemento non strutturale) Un elemento di raggruppamento che non ha significato strutturale intrinseco; serve esclusivamente a scopi di raggruppamento. Questo tipo di elemento differisce da una divisione (tipo di struttura Div) in quanto non deve essere interpretato o esportato in altri formati di documento; tuttavia, i suoi discendenti devono essere elaborati normalmente. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Nota) Un elemento di testo esplicativo, come una nota a piè di pagina o una nota finale, a cui si fa riferimento all'interno del corpo del documento. Può avere un'etichetta (tipo di struttura Lbl) come figlio. La nota può essere inclusa come figlio dell'elemento di struttura nel testo del corpo che si riferisce ad essa, oppure può essere inclusa altrove (come in una sezione di note finali) e accessibile tramite un riferimento (tipo di struttura Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Paragrafo) Una suddivisione a basso livello di testo. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Parte) Una suddivisione su larga scala di un documento. Questo tipo di elemento è appropriato per raggruppare articoli o sezioni. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Elemento privato) Un elemento di raggruppamento contenente contenuti privati appartenenti all'applicazione che lo produce. Il significato strutturale di questo tipo di elemento non è specificato e deve essere determinato interamente dallo scrittore conforme. Né l'elemento Private né alcuno dei suoi discendenti devono essere interpretati o esportati in altri formati di documento. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Citazione) Una porzione di testo in linea attribuita a qualcuno diverso dall'autore del testo circostante. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Testo base Ruby) Il testo a grandezza normale a cui è applicata l'annotazione ruby. RB può contenere testo, altri elementi in linea, o una miscela di entrambi. Può avere l'attributo RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Riferimento) Una citazione a contenuti altrove nel documento. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Punteggiatura Ruby) Punteggiatura che circonda il testo dell'annotazione ruby. Viene utilizzato solo quando un'annotazione ruby non può essere formattata correttamente in uno stile ruby e invece è formattata come un normale commento, o quando è formattata come un warichu. Contiene testo (di solito una singola PARENTESI SINISTRA o DESTRA o un carattere di delimitazione simile). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Testo dell'annotazione Ruby) Il testo di dimensioni più piccole che deve essere posizionato accanto al testo base ruby. Può contenere testo, altri elementi in linea, o una miscela di entrambi. Può avere gli attributi RubyAlign e RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) Una nota a margine (annotazione) scritta in una dimensione di testo più piccola e posizionata accanto al testo base a cui si riferisce. Un elemento Ruby può anche contenere gli elementi RB, RT e RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Sezione) Un contenitore per raggruppare elementi di contenuto correlati. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) Una porzione di testo in linea generica che non ha caratteristiche intrinseche particolari. Può essere utilizzato, ad esempio, per delimitare un intervallo di testo con un dato insieme di attributi di stile. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Tabella) Un layout bidimensionale di celle di dati rettangolari, che può avere una sottostruttura complessa. Contiene una o più righe di tabella (tipo di struttura TR) come figli; oppure un'intestazione di tabella opzionale (tipo di struttura THead) seguita da uno o più elementi del corpo della tabella (tipo di struttura TBody) e un piè di pagina della tabella opzionale (tipo di struttura TFoot). Inoltre, una tabella può avere una didascalia (tipo di struttura Caption) come suo primo o ultimo figlio. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Gruppo di righe del corpo della tabella; PDF 1.5) Un gruppo di righe che costituiscono la porzione principale del corpo di una tabella. Se la tabella è divisa su più pagine, l'area del corpo può essere spezzata su un confine di riga. Una tabella può avere più elementi TBody per consentire il disegno di un bordo o uno sfondo per un insieme di righe. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Cella di dati della tabella) Una cella di tabella contenente dati che fanno parte del contenuto della tabella. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Gruppo di righe del piè di pagina della tabella; PDF 1.5) Un gruppo di righe che costituiscono il piè di pagina di una tabella. Se la tabella è divisa su più pagine, queste righe possono essere ridisegnate in fondo a ciascun frammento della tabella (anche se c'è solo un elemento TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Cella di intestazione della tabella) Una cella di tabella contenente testo di intestazione che descrive una o più righe o colonne della tabella. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Gruppo di righe di intestazione della tabella; PDF 1.5) Un gruppo di righe che costituiscono l'intestazione di una tabella. Se la tabella è divisa su più pagine, queste righe possono essere ridisegnate in cima a ciascun frammento della tabella (anche se c'è solo un elemento THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Indice) Un elenco composto da voci di elementi dell'indice (tipo di struttura TOCI) e/o altre voci di indice annidate (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Voce dell'indice) Un membro individuale di un indice. I figli di questa voce possono essere uno dei seguenti tipi di struttura: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Riga della tabella) Una riga di intestazioni o dati in una tabella. Può contenere celle di intestazione della tabella e celle di dati della tabella (tipi di struttura TH e TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) Un commento o annotazione in una dimensione di testo più piccola e formattato su due righe più piccole all'interno dell'altezza della riga di testo contenente e posizionato dopo (in linea) il testo base a cui si riferisce. Un elemento Warichu può anche contenere gli elementi WT e WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Punteggiatura Warichu) La punteggiatura che circonda il testo WT. Contiene testo (di solito una singola PARENTESI SINISTRA o DESTRA o un carattere di delimitazione simile). Secondo JIS X 4051-1995, le parentesi che circondano un warichu possono essere convertite in uno SPAZIO (nominalmente 1/4 EM di larghezza) a discrezione del formattatore. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Testo Warichu) Il testo di dimensioni più piccole di un commento warichu che è formattato in due righe e posizionato tra gli elementi WP circostanti. |

### Vedi Anche

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)