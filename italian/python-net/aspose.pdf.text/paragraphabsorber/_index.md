---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta un oggetto assorbitore di oggetti della struttura della pagina come sezioni e paragrafi.<br/>            Esegue la ricerca di sezioni e paragrafi di testo e fornisce l'accesso a rettangoli e poligoni che li descrivono nello spazio delle coordinate del testo. <br/>            Esegue anche la ricerca di segmenti di testo e fornisce l'accesso ai risultati della ricerca tramite collezioni TextFragments raggruppate per elementi di struttura."
type: docs
weight: 240
url: /it/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Rappresenta un oggetto assorbitore di oggetti della struttura della pagina come sezioni e paragrafi.<br/>            Esegue la ricerca di sezioni e paragrafi di testo e fornisce l'accesso a rettangoli e poligoni che li descrivono nello spazio delle coordinate del testo. <br/>            Esegue anche la ricerca di segmenti di testo e fornisce l'accesso ai risultati della ricerca tramite collezioni TextFragments raggruppate per elementi di struttura.

Il tipo ParagraphAbsorber espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| ParagraphAbsorber() | Inizializza una nuova istanza del [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) che esegue la ricerca di sezioni/paragrafi del documento o della pagina. |
| ParagraphAbsorber(sections_search_depth) | Inizializza una nuova istanza della classe ParagraphAbsorber |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| page_markups | Ottiene la collezione di [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) che sono stati assorbiti. |
| sections_search_depth | Ottiene o imposta il valore che indica quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura.<br/>            La profondità di ricerca predefinita è 3.<br/>            Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi ecc.) e tre ricerche per quelle divise verticalmente (colonne). |
| is_multicolumn_paragraphs_allowed | Ottiene o imposta il valore che indica se le righe di testo iniziali di una sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo di una sezione precedente. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| visit(doc) | Esegue la ricerca di sezioni e paragrafi sul [Document](/pdf/python-net/aspose.pdf/document/) specificato. |
| visit(page) | Esegue la ricerca sulla [Page](/pdf/python-net/aspose.pdf/page/) specificata. |

### Vedi anche

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

