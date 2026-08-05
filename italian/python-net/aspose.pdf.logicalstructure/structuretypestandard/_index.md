---
title: "StructureTypeStandard"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta i Tipi di Struttura Standard."
type: docs
weight: 560
url: /it/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Rappresenta i Tipi di Struttura Standard.

Il tipo StructureTypeStandard espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| tag | Ottiene il nome del tag di [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/). |
| category | Ottiene la categoria del tipo Standard Structure Type. |
| DOCUMENT | (Document) Un documento completo. Questo è l'elemento radice di qualsiasi albero di struttura contenente più parti o più articoli. |
| PART | (Part) Una divisione su larga scala di un documento. Questo tipo di elemento è appropriato per raggruppare articoli o sezioni. |
| ART | (Article) Un corpo di testo relativamente autonomo che costituisce una singola narrazione o esposizione. Gli articoli dovrebbero essere disgiunti; cioè, non dovrebbero contenere altri articoli come elementi costitutivi. |
| SECT | (Section) Un contenitore per raggruppare elementi di contenuto correlati. |
| DIV | (Division) Un elemento generico a livello di blocco o un gruppo di elementi. |
| BLOCK_QUOTE | (Block quotation) Una porzione di testo composta da uno o più paragrafi attribuiti a qualcuno diverso dall'autore del testo circostante. |
| CAPTION | (Caption) Una breve porzione di testo che descrive una tabella o una figura. |
| TOC | (Table of contents) Un elenco composto da voci di indice (tipo di struttura TOCI) e/o altre voci di indice annidate (TOC). |
| TOCI | (Table of contents item) Un membro individuale di un indice. I figli di questa voce possono essere uno dei seguenti tipi di struttura: |
| INDEX | (Index) Una sequenza di voci contenenti testo identificativo accompagnato da elementi di riferimento che indicano le occorrenze del testo specificato nel corpo principale di un documento. |
| NON_STRUCT | (Nonstructural element) Un elemento di raggruppamento privo di significato strutturale intrinseco; serve esclusivamente a scopi di raggruppamento. Questo tipo di elemento differisce da una divisione (tipo di struttura Div) in quanto non deve essere interpretato o esportato in altri formati di documento; tuttavia, i suoi discendenti devono essere elaborati normalmente. |
| PRIVATE | (Private element) Un elemento di raggruppamento contenente contenuto privato appartenente all'applicazione che lo produce. Il significato strutturale di questo tipo di elemento non è specificato e deve essere determinato interamente dallo scrittore conforme. Né l'elemento Private né alcuno dei suoi discendenti devono essere interpretati o esportati in altri formati di documento. |
| P | (Paragraph) Una divisione di testo a basso livello. |
| H | (Heading) Un'etichetta per una suddivisione del contenuto di un documento. Dovrebbe essere il primo figlio della divisione che titola. |
| H1 | Intestazione di livello 1, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| H2 | Intestazione di livello 2, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| H3 | Intestazione di livello 3, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| H4 | Intestazione di livello 4, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| H5 | Intestazione di livello 5, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| H6 | Intestazione di livello 6, per l'uso in scrittori conformi che non possono annidare gerarchicamente le loro sezioni e quindi non possono determinare il livello di un'intestazione dal suo livello di annidamento. |
| L | (List) Una sequenza di elementi di significato e importanza simili. I suoi figli immediati dovrebbero essere una didascalia opzionale (tipo struttura Caption) seguita da uno o più elementi di elenco (tipo struttura LI). |
| LI | (List item) Un membro individuale di un elenco. I suoi figli possono essere una o più etichette, corpi di elenco o entrambi (tipi struttura Lbl o LBody). |
| LBL | (Label) Un nome o un numero che distingue un dato elemento dagli altri nella stessa lista o in un altro gruppo di elementi simili. |
| L_BODY | (List body) Il contenuto descrittivo di un elemento di elenco. In un elenco dizionario, ad esempio, contiene la definizione del termine. Può contenere direttamente il contenuto o avere altri BLSE, forse includendo elenchi annidati, come figli. |
| TABLE | (Table) Un layout bidimensionale di celle dati rettangolari, possibilmente con una sottostruttura complessa. Contiene uno o più righe di tabella (tipo struttura TR) come figli; oppure un'intestazione di tabella opzionale (tipo struttura THead) seguita da uno o più elementi di corpo tabella (tipo struttura TBody) e un piè di pagina opzionale (tipo struttura TFoot). Inoltre, una tabella può avere una didascalia (tipo struttura Caption) come primo o ultimo figlio. |
| T_HEAD | (Table header row group; PDF 1.5) Un gruppo di righe che costituiscono l'intestazione di una tabella. Se la tabella è divisa su più pagine, queste righe possono essere ridisegnate in cima a ogni frammento di tabella (sebbene ci sia un solo elemento THead). |
| T_BODY | (Gruppo di righe del corpo della tabella; PDF 1.5) Un gruppo di righe che costituisce la parte principale del corpo di una tabella. Se la tabella è suddivisa su più pagine, l'area del corpo può essere interrotta al confine di una riga. Una tabella può avere più elementi TBody per consentire il disegno di un bordo o di uno sfondo per un insieme di righe. |
| T_FOOT | (Gruppo di righe del piè di pagina della tabella; PDF 1.5) Un gruppo di righe che costituisce il piè di pagina di una tabella. Se la tabella è suddivisa su più pagine, queste righe possono essere ridisegnate nella parte inferiore di ogni frammento di tabella (anche se esiste un solo elemento TFoot.) |
| TR | (Riga di tabella) Una riga di intestazioni o dati in una tabella. Può contenere celle di intestazione della tabella e celle di dati della tabella (tipi di struttura TH e TD). |
| TH | (Cella di intestazione della tabella) Una cella della tabella contenente testo di intestazione che descrive una o più righe o colonne della tabella. |
| TD | (Cella di dati della tabella) Una cella della tabella contenente dati che fanno parte del contenuto della tabella. |
| SPAN | (Span) Una porzione di testo inline generica senza particolari caratteristiche intrinseche. Può essere usata, ad esempio, per delimitare un intervallo di testo con un determinato insieme di attributi di stile. |
| QUOTE | (Citazione) Una porzione di testo inline attribuita a qualcuno diverso dall'autore del testo circostante. |
| NOTA | (Nota) Un elemento di testo esplicativo, come una nota a piè di pagina o una nota finale, a cui si fa riferimento dal corpo del documento. Può avere un'etichetta (tipo di struttura Lbl) come figlio. La nota può essere inclusa come figlio dell'elemento di struttura nel testo principale che la richiama, oppure può essere inserita altrove (ad esempio in una sezione di note finali) e accessibile tramite un riferimento (tipo di struttura Reference). |
| REFERENCE | (Riferimento) Una citazione a contenuto presente altrove nel documento. |
| BIB_ENTRY | (Voce di bibliografia) Un riferimento che identifica la fonte esterna di un contenuto citato. Può contenere un'etichetta (tipo di struttura Lbl) come figlio. |
| CODE | (Codice) Un frammento di testo di programma informatico. |
| LINK | (Link) Un'associazione tra una porzione del contenuto dell'ILSE e una o più annotazioni di collegamento corrispondenti. I suoi figli dovrebbero essere uno o più elementi di contenuto o ILSE figli e uno o più riferimenti a oggetti che identificano le annotazioni di collegamento associate. |
| ANNOT | (Annotazione; PDF 1.5) Un'associazione tra una porzione del contenuto dell'ILSE e una corrispondente annotazione PDF. Annot deve essere usato per tutte le annotazioni PDF eccetto le annotazioni di collegamento e le annotazioni widget. |
| RUBY | (Ruby; PDF 1.5) Una nota a margine (annotazione) scritta in una dimensione di testo più piccola e posizionata adiacente al testo di base a cui si riferisce. Un elemento Ruby può contenere anche gli elementi RB, RT e RP. |
| RB | (Ruby base text) Il testo a grandezza piena a cui viene applicata l'annotazione ruby. RB può contenere testo, altri elementi inline o una combinazione di entrambi. Può avere l'attributo RubyAlignattribute. |
| RT | (Ruby annotation text) Il testo a dimensione più piccola che deve essere posizionato adiacente al testo base ruby. Può contenere testo, altri elementi inline o una combinazione di entrambi. Può avere gli attributi RubyAlign e RubyPosition. |
| RP | (Ruby punctuation) Punteggiatura che circonda il testo dell'annotazione ruby. È usata solo quando un'annotazione ruby non può essere formattata correttamente in stile ruby e viene invece formattata come un commento normale, o quando è formattata come un warichu. Contiene testo (di solito una singola parentesi LEFT o RIGHT o un carattere di parentesi simile). |
| WARICHU | (Warichu; PDF 1.5) Un commento o un'annotazione in una dimensione di testo più piccola e formattata su due linee più piccole all'interno dell'altezza della riga di testo contenente e posizionata dopo (inline) il testo base a cui si riferisce. Un elemento Warichu può anche contenere gli elementi WT e WP. |
| WT | (Warichu text) Il testo a dimensione più piccola di un commento warichu che è formattato su due linee e posizionato tra gli elementi WP circostanti. |
| WP | (Warichu punctuation) La punteggiatura che circonda il testo WT. Contiene testo (di solito una singola parentesi LEFT o RIGHT o un carattere di parentesi simile). Secondo JIS X 4051-1995, le parentesi che circondano un warichu possono essere convertite in uno SPAZIO (nominalmente 1/4 EM in larghezza) a discrezione del formattatore. |
| FIGURE | (Figure) Un elemento di contenuto grafico. Il suo posizionamento può essere specificato con l'attributo di layout Placement. |
| FORMULA | (Formula) Una formula matematica. |
| FORM | (Form) Un'annotazione widget che rappresenta un campo modulo interattivo. |

### Vedi anche

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

