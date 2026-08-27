---
title: "Class ParagraphAbsorber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Text.ParagraphAbsorber class. Rappresenta un oggetto assorbitore di oggetti della struttura della pagina come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce l'accesso a rettangoli e polydons che li descrivono nello spazio delle coordinate del testo. Esegue anche la ricerca di segmenti di testo e fornisce l'accesso ai risultati della ricerca tramite collezioni di TextFragments raggruppate per elementi di struttura."
type: docs
weight: 10850
url: /it/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Rappresenta un oggetto assorbitore di oggetti della struttura della pagina come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce l'accesso a rettangoli e poligoni che li descrivono nello spazio delle coordinate del testo. Esegue anche la ricerca di segmenti di testo e fornisce l'accesso ai risultati della ricerca tramite le collezioni !:TextFragments raggruppate per elementi di struttura.

```csharp
public class ParagraphAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Inizializza una nuova istanza di `ParagraphAbsorber` che esegue la ricerca di sezioni/paragrafi del documento o della pagina. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Inizializza una nuova istanza di `ParagraphAbsorber` che esegue la ricerca di sezioni/paragrafi del documento o della pagina. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Inizializza una nuova istanza di `ParagraphAbsorber` che esegue la ricerca di sezioni/paragrafi del documento o della pagina con i parametri specificati. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Inizializza una nuova istanza di `ParagraphAbsorber` che esegue la ricerca di sezioni/paragrafi del documento o della pagina con i parametri specificati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Ottiene o imposta il valore che indica se le linee di testo iniziali della sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo della sezione precedente. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Ottiene la collezione di [`PageMarkup`](../pagemarkup/) che sono stati assorbiti. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Ottiene o imposta le ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Ottiene o imposta il valore che indica quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi ecc.) e tre ricerche per quelle divise verticalmente (colonne). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Ottiene o imposta le TextReplaceOptions. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Esegue la ricerca di sezioni e paragrafi sul [`Document`](../../aspose.pdf/document/) specificato. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Esegue la ricerca sulla [`Page`](../../aspose.pdf/page/) specificata. |

## Osservazioni

Quando la ricerca è completata, la collezione [`PageMarkups`](./pagemarkups/) conterrà oggetti [`PageMarkup`](../pagemarkup/) che rappresentano la struttura della pagina tramite collezioni di [`MarkupSection`](../markupsection/) e [`MarkupParagraph`](../markupparagraph/). L'oggetto [`TextFragment`](../textfragment/) fornisce l'accesso al testo dell'occorrenza trovata, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.).

## Esempi

L'esempio dimostra come trovare il primo segmento di testo di ogni paragrafo nella prima pagina del documento PDF e evidenziarlo.

```csharp
// Apri documento
Document doc = new Document("input.pdf");

// Crea oggetto ParagraphAbsorber
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accetta l'assorbitore per la prima pagina
absorber.Visit(doc.Pages[1]);

// Ottieni l'oggetto markup della prima pagina
PageMarkup markup = absorber.PageMarkups[0];

// Scorri gli elementi strutturali del testo della pagina per trovare il primo frammento di testo di ogni paragrafo
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Aggiorna le proprietà del testo
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Salva documento
doc.Save(GetOutputPath("output.pdf"));
```

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


