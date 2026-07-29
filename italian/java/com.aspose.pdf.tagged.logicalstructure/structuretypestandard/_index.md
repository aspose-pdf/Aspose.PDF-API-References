---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta i tipi di struttura standard."
type: docs
weight: 130
url: /it/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

Rappresenta i tipi di struttura standard.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Annot](#Annot) | (Annotazione; PDF 1.5) Un'associazione tra una parte del contenuto dell'ILSE e una annotazione PDF corrispondente. Annot deve essere usato per tutte le annotazioni PDF tranne le annotazioni di collegamento e le annotazioni widget. |
| [Art](#Art) | (Articolo) Un corpo di testo relativamente autonomo che costituisce una singola narrazione o esposizione. Gli articoli dovrebbero essere disgiunti; cioè, non dovrebbero contenere altri articoli come elementi costitutivi. |
| [BibEntry](#BibEntry) | (Voce di bibliografia) Un riferimento che identifica la fonte esterna di un contenuto citato. Può contenere un'etichetta (tipo di struttura Lbl) come figlio. Sebbene una voce di bibliografia includa probabilmente parti componenti che identificano l'autore, l'opera, l'editore del contenuto citato, ecc., non sono definiti tipi di struttura standard a questo livello di dettaglio. |
| [BlockQuote](#BlockQuote) | (Citazione a blocco) Una porzione di testo composta da uno o più paragrafi attribuiti a qualcuno diverso dall'autore del testo circostante. |
| [Caption](#Caption) | (Didascalia) Una breve porzione di testo che descrive una tabella o una figura. |
| [Code](#Code) | (Codice) Un frammento di testo di programma informatico. |
| [Div](#Div) | (Divisione) Un elemento generico a livello di blocco o un gruppo di elementi. |
| [Document](#Document) | (Documento) Un documento completo. Questo è l'elemento radice di qualsiasi albero di struttura contenente più parti o più articoli. |
| [Figure](#Figure) | (Figura) Un elemento di contenuto grafico. Il suo posizionamento può essere specificato con l'attributo di layout Placement. |
| [Form](#Form) | (Modulo) Un'annotazione widget che rappresenta un campo di modulo interattivo. |
| [Formula](#Formula) | (Formula) Una formula matematica. Questo tipo di struttura è utile solo per identificare un intero elemento di contenuto come formula. Non sono definiti tipi di struttura standard per identificare componenti individuali all'interno della formula. Dal punto di vista della formattazione, la formula deve essere trattata in modo simile a una figura (tipo di struttura Figura). |
| [H](#H) | (Intestazione) Un'etichetta per una suddivisione del contenuto di un documento. Deve essere il primo figlio della divisione che introduce. |
| [H1](#H1) | Intestazione di livello 1, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| [H2](#H2) | Intestazione di livello 2, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| [H3](#H3) | Intestazione di livello 3, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| [H4](#H4) | Intestazione di livello 4, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| [H5](#H5) | Intestazione di livello 5, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| [H6](#H6) | Intestazione di livello 6, da utilizzare in redattori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| [Index](#Index) | (Indice) Una sequenza di voci contenenti testo identificativo accompagnato da elementi di riferimento che indicano le occorrenze del testo specificato nel corpo principale di un documento. |
| [L](#L) | (Elenco) Una sequenza di elementi con lo stesso significato e importanza. I suoi figli immediati dovrebbero essere una didascalia opzionale (tipo struttura Caption) seguita da uno o più elementi di elenco (tipo struttura LI). |
| [Lbl](#Lbl) | (Etichetta) Un nome o un numero che distingue un dato elemento dagli altri nella stessa lista o in un altro gruppo di elementi simili. |
| [LBody](#LBody) | (Corpo dell'elenco) Il contenuto descrittivo di un elemento di elenco. In un elenco dizionario, ad esempio, contiene la definizione del termine. Può contenere direttamente il contenuto o avere altri BLSE, forse includendo elenchi annidati, come figli. |
| [LI](#LI) | (Elemento di elenco) Un membro individuale di un elenco. I suoi figli possono essere una o più etichette, corpi di elenco, o entrambi (tipi struttura Lbl o LBody). |
| [Link](#Link) | (Collegamento) Un'associazione tra una parte del contenuto dell'ILSE e una o più annotazioni di collegamento corrispondenti. I suoi figli dovrebbero essere uno o più elementi di contenuto o ILSE figli e una o più referenze a oggetti che identificano le annotazioni di collegamento associate. |
| [NonStruct](#NonStruct) | (Elemento non strutturale) Un elemento di raggruppamento privo di significato strutturale intrinseco; serve esclusivamente a scopi di raggruppamento. Questo tipo di elemento differisce da una divisione (tipo struttura Div) perché non deve essere interpretato o esportato in altri formati di documento; tuttavia, i suoi discendenti devono essere elaborati normalmente. |
| [Note](#Note) | (Nota) Un elemento di testo esplicativo, come una nota a piè di pagina o una nota finale, a cui si fa riferimento dal corpo del documento. Può avere un'etichetta (tipo struttura Lbl) come figlio. La nota può essere inclusa come figlio dell'elemento strutturale nel testo del corpo che la richiama, oppure può essere inserita altrove (ad esempio in una sezione di note finali) e accessibile tramite una referenza (tipo struttura Reference). Il PDF con tag non prescrive il posizionamento delle note a piè di pagina nell'ordine del contenuto della pagina. Possono essere sia in linea sia alla fine della pagina, a discrezione del redattore conforme. |
| [P](#P) | (Paragrafo) Una divisione di testo di basso livello. |
| [Part](#Part) | (Parte) Una divisione su larga scala di un documento. Questo tipo di elemento è appropriato per raggruppare articoli o sezioni. |
| [Private](#Private) | (Elemento privato) Un elemento di raggruppamento contenente contenuto privato appartenente all'applicazione che lo produce. Il significato strutturale di questo tipo di elemento non è specificato e deve essere determinato interamente dal redattore conforme. Né l'elemento Privato né i suoi discendenti devono essere interpretati o esportati in altri formati di documento. |
| [Quote](#Quote) | (Citazione) Una porzione di testo in linea attribuita a qualcuno diverso dall'autore del testo circostante. Il testo citato dovrebbe essere contenuto in linea all'interno di un unico paragrafo. Questo differisce dall'elemento a livello di blocco BlockQuote, che consiste in uno o più paragrafi completi (o altri elementi presentati come se fossero paragrafi completi). |
| [RB](#RB) | (Testo di base Ruby) Il testo a grandezza piena a cui viene applicata l'annotazione ruby. RB può contenere testo, altri elementi in linea o una combinazione di entrambi. Può avere l'attributo RubyAlign. |
| [Reference](#Reference) | (Riferimento) Una citazione a contenuto altrove nel documento. |
| [RP](#RP) | (Punteggiatura Ruby) Punteggiatura che circonda il testo dell'annotazione ruby. Viene usata solo quando un'annotazione ruby non può essere formattata correttamente in stile ruby e viene invece formattata come un commento normale, o quando è formattata come warichu. Contiene testo (di solito una singola parentesi SINISTRA o DESTRA o un carattere di parentesi simile). |
| [RT](#RT) | (Testo di annotazione Ruby) Il testo di dimensione più piccola che deve essere posizionato accanto al testo di base Ruby. Può contenere testo, altri elementi in linea o una combinazione di entrambi. Può avere gli attributi RubyAlign e RubyPosition. |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) Una nota a margine (annotazione) scritta in una dimensione di testo più piccola e posizionata adiacente al testo base a cui si riferisce. Un elemento Ruby può contenere anche gli elementi RB, RT e RP. (Ruby) Il contenitore dell'intera struttura ruby. Deve contenere un elemento RB seguito da un elemento RT oppure da un gruppo di tre elementi costituito da RP, RT e RP. Gli elementi Ruby e i loro elementi di contenuto non devono interruzioni su più righe. |
| [Sect](#Sect) | (Section) Un contenitore per raggruppare elementi di contenuto correlati. |
| [Span](#Span) | (Span) Una porzione di testo inline generica senza caratteristiche intrinseche particolari. Può essere usata, ad esempio, per delimitare un intervallo di testo con un determinato insieme di attributi di stile. |
| [Table](#Table) | (Table) Un layout bidimensionale di celle dati rettangolari, possibilmente con una sotto‑struttura complessa. Contiene uno o più righe di tabella (tipo struttura TR) come figli; oppure un’intestazione di tabella opzionale (tipo struttura THead) seguita da uno o più elementi corpo della tabella (tipo struttura TBody) e un piè di pagina opzionale (tipo struttura TFoot). Inoltre, una tabella può avere una didascalia (tipo struttura Caption) come primo o ultimo figlio. |
| [TBody](#TBody) | (Table body row group; PDF 1.5) Un gruppo di righe che costituiscono la parte principale del corpo di una tabella. Se la tabella è suddivisa su più pagine, l'area del corpo può essere interrotta al confine di una riga. Una tabella può avere più elementi TBody per consentire il disegno di un bordo o di uno sfondo per un insieme di righe. |
| [TD](#TD) | (Table data cell) Una cella di tabella contenente dati che fanno parte del contenuto della tabella. |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) Un gruppo di righe che costituiscono il piè di pagina di una tabella. Se la tabella è suddivisa su più pagine, queste righe possono essere ridisegnate nella parte inferiore di ogni frammento di tabella (sebbene vi sia un solo elemento TFoot). |
| [TH](#TH) | (Table header cell) Una cella di tabella contenente testo di intestazione che descrive una o più righe o colonne della tabella. |
| [THead](#THead) | (Table header row group; PDF 1.5) Un gruppo di righe che costituiscono l'intestazione di una tabella. Se la tabella è suddivisa su più pagine, queste righe possono essere ridisegnate nella parte superiore di ogni frammento di tabella (sebbene vi sia un solo elemento THead). |
| [TOC](#TOC) | (Table of contents) Un elenco composto da voci di elementi dell'indice (tipo struttura TOCI) e/o da altre voci di indice annidate (TOC). Una voce TOC che include solo voci TOCI rappresenta una gerarchia piatta. Una voce TOC che include altre voci TOC annidate (e possibilmente voci TOCI) rappresenta una gerarchia più complessa. Idealmente, la gerarchia di una voce TOC di livello superiore riflette la struttura del corpo principale del documento. |
| [TOCI](#TOCI) | (Table of contents item) Un membro individuale di un indice. I figli di questa voce possono essere uno dei seguenti tipi di struttura: Lbl - Un'etichetta Reference - Un riferimento al titolo e al numero di pagina NonStruct - Elementi non strutturati per avvolgere un artefatto leader P - Testo descrittivo TOC - Elementi di indice per indici gerarchici, come descritto per la voce TOC |
| [TR](#TR) | (Table row) Una riga di intestazioni o dati in una tabella. Può contenere celle di intestazione di tabella e celle di dati di tabella (tipi di struttura TH e TD). |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) Un commento o annotazione in una dimensione di testo più piccola e formattata su due linee più piccole all'interno dell'altezza della riga di testo contenente, posizionata dopo (inline) il testo base a cui si riferisce. Un elemento Warichu può contenere anche gli elementi WT e WP. (Warichu) Il contenitore dell'intera struttura warichu. Può contenere un gruppo di tre elementi costituito da WP, WT e WP. Gli elementi Warichu (e i loro elementi di contenuto) possono avvolgersi su più linee, secondo le regole di interruzione warichu descritte nello Standard Industriale Giapponese (JIS) X 4051-1995. |
| [WP](#WP) | (Warichu punctuation) La punteggiatura che circonda il testo WT. Contiene testo (di solito una singola parentesi SINISTRA o DESTRA o un carattere di parentesi simile). Secondo JIS X 4051-1995, le parentesi che circondano un warichu possono essere convertite in uno SPAZIO (nominalmente 1/4 EM di larghezza) a discrezione del formattatore. |
| [WT](#WT) | (Testo Warichu) Il testo di dimensioni più piccole di un commento warichu che è formattato in due righe e posizionato tra gli elementi WP circostanti. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | Ottiene la categoria del Tipo di Struttura Standard. |
| [getTag](#getTag--) | Ottiene il nome del tag di {@code StructureElement}. |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | Esegue una conversione esplicita da {@link String} a {@link StructureTypeStandard}. |
| [toString](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotazione; PDF 1.5) Un'associazione tra una parte del contenuto dell'ILSE e una annotazione PDF corrispondente. Annot deve essere usato per tutte le annotazioni PDF tranne le annotazioni di collegamento e le annotazioni widget.

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Articolo) Un corpo di testo relativamente autonomo che costituisce una singola narrazione o esposizione. Gli articoli dovrebbero essere disgiunti; cioè, non dovrebbero contenere altri articoli come elementi costitutivi.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Voce di bibliografia) Un riferimento che identifica la fonte esterna di un contenuto citato. Può contenere un'etichetta (tipo di struttura Lbl) come figlio. Sebbene una voce di bibliografia includa probabilmente parti componenti che identificano l'autore, l'opera, l'editore del contenuto citato, ecc., non sono definiti tipi di struttura standard a questo livello di dettaglio.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Citazione a blocco) Una porzione di testo composta da uno o più paragrafi attribuiti a qualcuno diverso dall'autore del testo circostante.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Didascalia) Una breve porzione di testo che descrive una tabella o una figura.

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Codice) Un frammento di testo di programma informatico.

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Divisione) Un elemento generico a livello di blocco o un gruppo di elementi.

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Documento) Un documento completo. Questo è l'elemento radice di qualsiasi albero di struttura contenente più parti o più articoli.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Figura) Un elemento di contenuto grafico. Il suo posizionamento può essere specificato con l'attributo di layout Placement.

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Modulo) Un'annotazione widget che rappresenta un campo di modulo interattivo.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) Una formula matematica. Questo tipo di struttura è utile solo per identificare un intero elemento di contenuto come formula. Non sono definiti tipi di struttura standard per identificare componenti individuali all'interno della formula. Dal punto di vista della formattazione, la formula deve essere trattata in modo simile a una figura (tipo di struttura Figura).

### H {#H}
```
public static final StructureTypeStandard H
```

(Intestazione) Un'etichetta per una suddivisione del contenuto di un documento. Deve essere il primo figlio della divisione che introduce.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

Intestazione di livello 1, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

Intestazione di livello 2, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Intestazione di livello 3, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Intestazione di livello 4, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Intestazione di livello 5, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Intestazione di livello 6, da utilizzare in redattori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento.

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Indice) Una sequenza di voci contenenti testo identificativo accompagnato da elementi di riferimento che indicano le occorrenze del testo specificato nel corpo principale di un documento.

### L {#L}
```
public static final StructureTypeStandard L
```

(Elenco) Una sequenza di elementi con lo stesso significato e importanza. I suoi figli immediati dovrebbero essere una didascalia opzionale (tipo struttura Caption) seguita da uno o più elementi di elenco (tipo struttura LI).

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Etichetta) Un nome o un numero che distingue un dato elemento dagli altri nella stessa lista o in un altro gruppo di elementi simili.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(Corpo dell'elenco) Il contenuto descrittivo di un elemento di elenco. In un elenco dizionario, ad esempio, contiene la definizione del termine. Può contenere direttamente il contenuto o avere altri BLSE, forse includendo elenchi annidati, come figli.

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(Elemento di elenco) Un membro individuale di un elenco. I suoi figli possono essere una o più etichette, corpi di elenco, o entrambi (tipi struttura Lbl o LBody).

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Collegamento) Un'associazione tra una parte del contenuto dell'ILSE e una o più annotazioni di collegamento corrispondenti. I suoi figli dovrebbero essere uno o più elementi di contenuto o ILSE figli e una o più referenze a oggetti che identificano le annotazioni di collegamento associate.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Elemento non strutturale) Un elemento di raggruppamento privo di significato strutturale intrinseco; serve esclusivamente a scopi di raggruppamento. Questo tipo di elemento differisce da una divisione (tipo struttura Div) perché non deve essere interpretato o esportato in altri formati di documento; tuttavia, i suoi discendenti devono essere elaborati normalmente.

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Nota) Un elemento di testo esplicativo, come una nota a piè di pagina o una nota finale, a cui si fa riferimento dal corpo del documento. Può avere un'etichetta (tipo struttura Lbl) come figlio. La nota può essere inclusa come figlio dell'elemento strutturale nel testo del corpo che la richiama, oppure può essere inserita altrove (ad esempio in una sezione di note finali) e accessibile tramite una referenza (tipo struttura Reference). Il PDF con tag non prescrive il posizionamento delle note a piè di pagina nell'ordine del contenuto della pagina. Possono essere sia in linea sia alla fine della pagina, a discrezione del redattore conforme.

### P {#P}
```
public static final StructureTypeStandard P
```

(Paragrafo) Una divisione di testo di basso livello.

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Parte) Una divisione su larga scala di un documento. Questo tipo di elemento è appropriato per raggruppare articoli o sezioni.

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Elemento privato) Un elemento di raggruppamento contenente contenuto privato appartenente all'applicazione che lo produce. Il significato strutturale di questo tipo di elemento non è specificato e deve essere determinato interamente dal redattore conforme. Né l'elemento Privato né i suoi discendenti devono essere interpretati o esportati in altri formati di documento.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Citazione) Una porzione di testo in linea attribuita a qualcuno diverso dall'autore del testo circostante. Il testo citato dovrebbe essere contenuto in linea all'interno di un unico paragrafo. Questo differisce dall'elemento a livello di blocco BlockQuote, che consiste in uno o più paragrafi completi (o altri elementi presentati come se fossero paragrafi completi).

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Testo di base Ruby) Il testo a grandezza piena a cui viene applicata l'annotazione ruby. RB può contenere testo, altri elementi in linea o una combinazione di entrambi. Può avere l'attributo RubyAlign.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Riferimento) Una citazione a contenuto altrove nel documento.

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Punteggiatura Ruby) Punteggiatura che circonda il testo dell'annotazione ruby. Viene usata solo quando un'annotazione ruby non può essere formattata correttamente in stile ruby e viene invece formattata come un commento normale, o quando è formattata come warichu. Contiene testo (di solito una singola parentesi SINISTRA o DESTRA o un carattere di parentesi simile).

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Testo di annotazione Ruby) Il testo di dimensione più piccola che deve essere posizionato accanto al testo di base Ruby. Può contenere testo, altri elementi in linea o una combinazione di entrambi. Può avere gli attributi RubyAlign e RubyPosition.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) Una nota a margine (annotazione) scritta in una dimensione di testo più piccola e posizionata adiacente al testo base a cui si riferisce. Un elemento Ruby può contenere anche gli elementi RB, RT e RP. (Ruby) Il contenitore dell'intera struttura ruby. Deve contenere un elemento RB seguito da un elemento RT oppure da un gruppo di tre elementi costituito da RP, RT e RP. Gli elementi Ruby e i loro elementi di contenuto non devono interruzioni su più righe.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) Un contenitore per raggruppare elementi di contenuto correlati.

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) Una porzione di testo inline generica senza caratteristiche intrinseche particolari. Può essere usata, ad esempio, per delimitare un intervallo di testo con un determinato insieme di attributi di stile.

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) Un layout bidimensionale di celle dati rettangolari, possibilmente con una sotto‑struttura complessa. Contiene uno o più righe di tabella (tipo struttura TR) come figli; oppure un’intestazione di tabella opzionale (tipo struttura THead) seguita da uno o più elementi corpo della tabella (tipo struttura TBody) e un piè di pagina opzionale (tipo struttura TFoot). Inoltre, una tabella può avere una didascalia (tipo struttura Caption) come primo o ultimo figlio.

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) Un gruppo di righe che costituiscono la parte principale del corpo di una tabella. Se la tabella è suddivisa su più pagine, l'area del corpo può essere interrotta al confine di una riga. Una tabella può avere più elementi TBody per consentire il disegno di un bordo o di uno sfondo per un insieme di righe.

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) Una cella di tabella contenente dati che fanno parte del contenuto della tabella.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) Un gruppo di righe che costituiscono il piè di pagina di una tabella. Se la tabella è suddivisa su più pagine, queste righe possono essere ridisegnate nella parte inferiore di ogni frammento di tabella (sebbene vi sia un solo elemento TFoot).

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) Una cella di tabella contenente testo di intestazione che descrive una o più righe o colonne della tabella.

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) Un gruppo di righe che costituiscono l'intestazione di una tabella. Se la tabella è suddivisa su più pagine, queste righe possono essere ridisegnate nella parte superiore di ogni frammento di tabella (sebbene vi sia un solo elemento THead).

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) Un elenco composto da voci di elementi dell'indice (tipo struttura TOCI) e/o da altre voci di indice annidate (TOC). Una voce TOC che include solo voci TOCI rappresenta una gerarchia piatta. Una voce TOC che include altre voci TOC annidate (e possibilmente voci TOCI) rappresenta una gerarchia più complessa. Idealmente, la gerarchia di una voce TOC di livello superiore riflette la struttura del corpo principale del documento.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) Un membro individuale di un indice. I figli di questa voce possono essere uno dei seguenti tipi di struttura: Lbl - Un'etichetta Reference - Un riferimento al titolo e al numero di pagina NonStruct - Elementi non strutturati per avvolgere un artefatto leader P - Testo descrittivo TOC - Elementi di indice per indici gerarchici, come descritto per la voce TOC

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) Una riga di intestazioni o dati in una tabella. Può contenere celle di intestazione di tabella e celle di dati di tabella (tipi di struttura TH e TD).

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) Un commento o annotazione in una dimensione di testo più piccola e formattata su due linee più piccole all'interno dell'altezza della riga di testo contenente, posizionata dopo (inline) il testo base a cui si riferisce. Un elemento Warichu può contenere anche gli elementi WT e WP. (Warichu) Il contenitore dell'intera struttura warichu. Può contenere un gruppo di tre elementi costituito da WP, WT e WP. Gli elementi Warichu (e i loro elementi di contenuto) possono avvolgersi su più linee, secondo le regole di interruzione warichu descritte nello Standard Industriale Giapponese (JIS) X 4051-1995.

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) La punteggiatura che circonda il testo WT. Contiene testo (di solito una singola parentesi SINISTRA o DESTRA o un carattere di parentesi simile). Secondo JIS X 4051-1995, le parentesi che circondano un warichu possono essere convertite in uno SPAZIO (nominalmente 1/4 EM di larghezza) a discrezione del formattatore.

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Testo Warichu) Il testo di dimensioni più piccole di un commento warichu che è formattato in due righe e posizionato tra gli elementi WP circostanti.

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

Ottiene la categoria del Tipo di Struttura Standard.

**Returns:**
Valore: Categoria del Tipo di Struttura Standard.

### getTag {#getTag--}
```
public final String getTag()
```

Ottiene il nome del tag di {@code StructureElement}.

**Returns:**
Nome del tag di {@code StructureElement}.

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
Esegue una conversione esplicita da {@link String} a {@link StructureTypeStandard}.

### toString {#toString--}
```
public String toString()
```

Restituisce una stringa che rappresenta l'oggetto corrente.

**Returns:**
Stringa che rappresenta l'oggetto corrente.
