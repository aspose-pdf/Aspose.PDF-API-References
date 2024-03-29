---
title: ParagraphAbsorber
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta un oggetto assorbente di oggetti struttura della pagina come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce laccesso a rettangoli e polidoni che lo descrivono nello spazio delle coordinate del testo. Esegue anche la ricerca di segmenti di testo e fornisce laccesso ai risultati della ricerca tramiteTextFragments raccolte raggruppate per elementi della struttura.
type: docs
weight: 6850
url: /it/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Rappresenta un oggetto assorbente di oggetti struttura della pagina come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce l'accesso a rettangoli e polidoni che lo descrivono nello spazio delle coordinate del testo. Esegue anche la ricerca di segmenti di testo e fornisce l'accesso ai risultati della ricerca tramite!:TextFragments raccolte raggruppate per elementi della struttura.

```csharp
public class ParagraphAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber#constructor)() | Inizializza una nuova istanza di[`ParagraphAbsorber`](../paragraphabsorber) che effettua la ricerca di sezioni/paragrafi del documento o della pagina. |
| [ParagraphAbsorber](paragraphabsorber#constructor_1)(int) | Inizializza una nuova istanza di[`ParagraphAbsorber`](../paragraphabsorber) che effettua la ricerca di sezioni/paragrafi del documento o della pagina. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed) { get; set; } | Ottiene o imposta un valore che indica se le righe di testo iniziali di una sezione successiva possono essere considerate come la continuazione dell'ultimo paragrafo di una sezione precedente. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups) { get; } | Ottiene la raccolta di[`PageMarkup`](../pagemarkup) che sono stati assorbiti. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth) { get; set; } | Ottiene o imposta un valore che indica quante volte verranno eseguite le ricerche sequenziali di elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi ecc.) e tre ricerche per sezioni divise verticalmente quelli (colonne). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit#visit)(Document) | Esegue la ricerca di sezioni e paragrafi sull'oggetto specificato[`Document`](../../aspose.pdf/document) . |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit#visit_1)(Page) | Esegue la ricerca sull'oggetto specificato[`Page`](../../aspose.pdf/page) . |

### Osservazioni

Al termine della ricerca il[`PageMarkups`](./pagemarkups) la raccolta conterrà[`PageMarkup`](../pagemarkup) oggetti che rappresentano la struttura della pagina per raccolte di[`MarkupSection`](../markupsection) e[`MarkupParagraph`](../markupparagraph) . Il[`TextFragment`](../textfragment) l'oggetto fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (carattere, dimensione del carattere, colore, ecc.).

### Esempi

L'esempio mostra come trovare il primo segmento di testo di ogni paragrafo nella prima pagina del documento PDF ed evidenziarlo.

```csharp
//ns.adobe.com/xap/1.0/"));
Document doc = new Document("input.pdf");

//metti il timbro solo sulla prima, quarta e sesta pagina.
ParagraphAbsorber absorber = new ParagraphAbsorber();

//La prima pagina verrà utilizzata come timbro.
absorber.Visit(doc.Pages[1]);

//La prima pagina verrà utilizzata come timbro.
PageMarkup markup = absorber.PageMarkups[0];

// Apri documento
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Crea oggetto ParagraphAbsorber
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Accetta l'assorbitore per la prima pagina
doc.Save(GetOutputPath("output.pdf"));
```

### Guarda anche

* spazio dei nomi [Aspose.Pdf.Text](../../aspose.pdf.text)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
