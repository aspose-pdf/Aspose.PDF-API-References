---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.ParagraphAbsorber. Rappresenta un oggetto assorbitore di oggetti di struttura della pagina come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce accesso a rettangoli e poligoni che lo descrivono nello spazio delle coordinate del testo. Esegue anche la ricerca di segmenti di testo e fornisce accesso ai risultati della ricerca tramite collezioni di TextFragments raggruppate per elementi di struttura.
type: docs
weight: 10670
url: /it/net/aspose.pdf.text/paragraphabsorber/
---
## Classe ParagraphAbsorber

Rappresenta un oggetto assorbitore di oggetti di struttura della pagina come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce accesso a rettangoli e poligoni che lo descrivono nello spazio delle coordinate del testo. Esegue anche la ricerca di segmenti di testo e fornisce accesso ai risultati della ricerca tramite collezioni di !:TextFragments raggruppate per elementi di struttura.

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
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Ottiene o imposta il valore che indica se le righe di testo iniziali di una sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo di una sezione precedente. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Ottiene la collezione di [`PageMarkup`](../pagemarkup/) che sono stati assorbiti. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Ottiene o imposta le opzioni di ParagraphAbsorber. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Ottiene o imposta il valore che istruisce su quante volte verranno eseguite ricerche sequenziali per elementi di struttura più dettagliati. La profondità di ricerca predefinita è 3. Ciò significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi, ecc.) e tre ricerche per quelle divise verticalmente (colonne). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Ottiene o imposta le opzioni di TextReplace. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Esegue la ricerca di sezioni e paragrafi nel [`Document`](../../aspose.pdf/document/) specificato. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Esegue la ricerca nella [`Page`](../../aspose.pdf/page/) specificata. |

## Osservazioni

Quando la ricerca è completata, la collezione [`PageMarkups`](./pagemarkups/) conterrà oggetti [`PageMarkup`](../pagemarkup/) che rappresentano la struttura della pagina tramite collezioni di [`MarkupSection`](../markupsection/) e [`MarkupParagraph`](../markupparagraph/). L'oggetto [`TextFragment`](../textfragment/) fornisce accesso al testo dell'occorrenza della ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore, ecc.).

## Esempi

L'esempio dimostra come trovare il primo segmento di testo di ciascun paragrafo nella prima pagina del documento PDF e metterlo in evidenza.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### Vedi Anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)