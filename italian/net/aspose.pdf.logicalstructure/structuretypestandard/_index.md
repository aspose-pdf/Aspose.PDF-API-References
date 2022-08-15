---
title: StructureTypeStandard
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta i tipi di struttura standard.
type: docs
weight: 4560
url: /it/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

Rappresenta i tipi di struttura standard.

```csharp
public sealed class StructureTypeStandard
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category) { get; } | Ottiene la categoria del tipo di struttura standard. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag) { get; } | Ottiene il nome del tag di[`StructureElement`](../structureelement) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit) | Esegue una conversione esplicita daString a[`StructureTypeStandard`](../structuretypestandard) . |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot) | (Annotazione; PDF 1.5) Un'associazione tra una parte del contenuto di ILSE e un'annotazione PDF corrispondente. Annot deve essere utilizzato per tutte le annotazioni PDF ad eccezione delle annotazioni dei collegamenti e delle annotazioni dei widget. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art) | (Articolo) Un corpo di testo relativamente autonomo che costituisce una singola narrazione o esposizione. Gli articoli dovrebbero essere disgiunti; cioè, non dovrebbero contenere altri articoli come elementi costitutivi. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry) | (Voce bibliografica) Un riferimento che identifica la fonte esterna di alcuni contenuti citati. Può contenere un'etichetta (tipo di struttura Lbl) da bambino. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote) | (Citazione in blocco) Una porzione di testo composta da uno o più paragrafi attribuiti a una persona diversa dall'autore del testo circostante. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption) | (Didascalia) Una breve porzione di testo che descrive una tabella o una figura. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code) | (Codice) Un frammento di testo del programma per computer. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div) | (Divisione) Un elemento generico a livello di blocco o un gruppo di elementi. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document) | (Documento) Un documento completo. Questo è l'elemento radice di qualsiasi struttura ad albero contenente più parti o più articoli. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure) | (Figura) Un elemento di contenuto grafico. Il suo posizionamento può essere specificato con l'attributo Layout posizionamento. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form) | (Modulo) Un'annotazione del widget che rappresenta un campo modulo interattivo. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula) | (Formula) Una formula matematica. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h) | (Intestazione) Un'etichetta per una suddivisione del contenuto di un documento. Dovrebbe essere il primo figlio della divisione che dirige. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1) | Intestazione di livello 1, da utilizzare nei writer conformi che non possono nidificare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di nidificazione. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2) | Intestazione di livello 2, da utilizzare nei writer conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3) | Intestazione di livello 3, da utilizzare nei writer conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4) | Intestazione di livello 4, da utilizzare nei writer conformi che non possono nidificare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di nidificazione. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5) | Intestazione di livello 5, da utilizzare nei writer conformi che non possono nidificare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di nidificazione. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6) | Intestazione di livello 6, da utilizzare nei writer conformi che non possono nidificare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di nidificazione. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index) | (Indice) Sequenza di voci contenenti testo identificativo accompagnato da elementi di riferimento che indicano le occorrenze del testo specificato nel corpo principale di un documento. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l) | (Elenco) Una sequenza di elementi di significato e importanza simili. I suoi figli immediati dovrebbero essere una didascalia facoltativa (tipo di struttura Didascalia) seguita da uno o più elementi dell'elenco (tipo di struttura LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl) | (Etichetta) Un nome o un numero che distingue un dato elemento da altri nello stesso elenco o in un altro gruppo di elementi simili. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody) | (Corpo elenco) Il contenuto descrittivo di una voce di elenco. In un elenco di dizionari, ad esempio, contiene la definizione del termine. Può contenere direttamente il contenuto o avere altri BLSE, magari includendo elenchi nidificati, come figli. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li) | (Elenco elenco) Un singolo membro di un elenco. I suoi figli possono essere una o più etichette, corpi di elenchi o entrambi (tipi di struttura Lbl o LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link) | (Link) Un'associazione tra una parte del contenuto di ILSE e una o più annotazioni di collegamento corrispondenti. I suoi figli dovrebbero essere uno o più elementi di contenuto o ILSE figlio e uno o più riferimenti a oggetti che identificano le annotazioni di collegamento associate. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct) | (Elemento non strutturale) Un elemento di raggruppamento senza significato strutturale intrinseco; serve esclusivamente per scopi di raggruppamento. Questo tipo di elemento differisce da una divisione (tipo di struttura Div) in quanto non deve essere interpretato o esportato in altri formati di documento; tuttavia, i suoi discendenti verranno elaborati normalmente. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note) | (Nota) Un elemento di testo esplicativo, come una nota a piè di pagina o una nota di chiusura, a cui si fa riferimento dall'interno del corpo del documento. Può avere un'etichetta (tipo di struttura Lbl) da bambino. La nota può essere inclusa come figlia dell'elemento struttura nel corpo del testo che fa riferimento ad essa, oppure può essere inclusa altrove (ad esempio in una sezione di note di chiusura) e vi si accede tramite un riferimento (tipo di struttura Riferimento). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p) | (Paragrafo) Una divisione di basso livello del testo. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part) | (Parte) Una divisione su larga scala di un documento. Questo tipo di elemento è appropriato per raggruppare articoli o sezioni. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private) | (Elemento privato) Un elemento di raggruppamento contenente contenuto privato appartenente all'applicazione che lo produce. Il significato strutturale di questo tipo di elemento non è specificato e sarà determinato interamente dal scrivente conforme. Né l'elemento Private né alcuno dei suoi discendenti devono essere interpretati o esportati in altri formati di documento. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote) | (Citazione) Una parte in linea di testo attribuita a qualcuno diverso dall'autore del testo circostante. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb) | (Testo di base Ruby) Il testo a grandezza naturale a cui viene applicata l'annotazione Ruby. RB può contenere testo, altri elementi inline o una combinazione di entrambi. Potrebbe avere l'attributo RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference) | (Riferimento) Una citazione a contenuti in altre parti del documento. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp) | (punteggiatura rubino) Punteggiatura che circonda il testo dell'annotazione rubino. Viene utilizzato solo quando un'annotazione rubino non può essere formattata correttamente in uno stile rubino e viene invece formattata come un normale commento o quando è formattata come warichu. Contiene testo (solitamente una singola PARENTESI SINISTRA o DESTRA o un carattere di parentesi simile). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt) | (testo di annotazione Ruby) Il testo di dimensioni inferiori che deve essere posizionato accanto al testo di base Ruby. Può contenere testo, altri elementi in linea o una combinazione di entrambi. Potrebbe avere gli attributi RubyAlign e RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby) | (Ruby; PDF 1.5) Una nota a margine (annotazione) scritta in una dimensione del testo più piccola e posizionata adiacente al testo di base a cui si riferisce. Un elemento Ruby può contenere anche gli elementi RB, RT e RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect) | (Sezione) Un contenitore per raggruppare elementi di contenuto correlati. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span) | (Span) Una porzione generica di testo in linea senza particolari caratteristiche intrinseche. Può essere utilizzato, ad esempio, per delimitare un intervallo di testo con un determinato insieme di attributi di stile. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table) | (Tabella) Un layout bidimensionale di celle di dati rettangolari, possibilmente con una sottostruttura complessa. Contiene una o più righe di tabella (tipo di struttura TR) come figli; oppure una testata tabella opzionale (tipo di struttura THead) seguita da uno o più elementi del corpo della tabella (tipo di struttura TBody) e un piè di pagina opzionale (tipo di struttura TFoot). Inoltre, una tabella può avere una didascalia (tipo di struttura Didascalia) come primo o ultimo figlio. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody) | (Gruppo di righe del corpo della tabella; PDF 1.5) Un gruppo di righe che costituisce la parte del corpo principale di una tabella. Se la tabella è suddivisa su più pagine, l'area del corpo potrebbe essere suddivisa su un limite di riga. Una tabella può avere più elementi TBody per consentire il disegno di un bordo o di uno sfondo per un insieme di righe. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td) | (cella dati tabella) Una cella di tabella contenente dati che fanno parte del contenuto della tabella. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot) | (Gruppo di righe del piè di pagina della tabella; PDF 1.5) Un gruppo di righe che costituisce il piè di pagina di una tabella. Se la tabella è suddivisa su più pagine, queste righe possono essere ridisegnate nella parte inferiore di ogni frammento di tabella (sebbene sia presente un solo elemento TFoot.) |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th) | (Cella dell'intestazione della tabella) Una cella della tabella contenente il testo dell'intestazione che descrive una o più righe o colonne della tabella. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead) | (Gruppo di righe di intestazione tabella; PDF 1.5) Un gruppo di righe che costituisce l'intestazione di una tabella. Se la tabella è suddivisa su più pagine, queste righe possono essere ridisegnate nella parte superiore di ogni frammento di tabella (sebbene sia presente un solo elemento THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc) | (Sommario) Un elenco composto da voci di voci di sommario (tipo di struttura TOCI) e/o altre voci di sommario nidificate (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci) | (Voce del sommario) Un singolo membro di un sommario. I figli di questa voce possono essere uno qualsiasi dei seguenti tipi di struttura: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr) | (Riga tabella) Una riga di intestazioni o dati in una tabella. Può contenere celle di intestazione di tabella e celle di dati di tabella (tipi di struttura TH e TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu) | (Warichu; PDF 1.5) Un commento o un'annotazione in una dimensione del testo più piccola e formattata su due righe più piccole entro l'altezza della riga di testo contenente e posizionata dopo (in linea) il testo di base a cui si riferisce. Un elemento Warichu può contenere anche gli elementi WT e WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp) | (punteggiatura Warichu) La punteggiatura che circonda il testo WT. Contiene testo (solitamente una singola PARENTESI SINISTRA o DESTRA o un carattere di parentesi simile). Secondo JIS X 4051-1995, le parentesi che circondano un warichu possono essere convertite in uno SPAZIO (nominalmente 1/4 EM di larghezza) a discrezione del formatter. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt) | (testo Warichu) Il testo di dimensioni ridotte di un commento warichu formattato in due righe e posizionato tra gli elementi WP circostanti. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
