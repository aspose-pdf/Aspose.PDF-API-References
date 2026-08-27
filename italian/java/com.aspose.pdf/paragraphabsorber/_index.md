---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta un oggetto assorbitore di oggetti della struttura della pagina come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce l'accesso per.</p>"
type: docs
weight: 3470
url: /it/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Rappresenta un oggetto assorbitore della struttura della pagina, come sezioni e paragrafi. Esegue la ricerca di sezioni e paragrafi di testo e fornisce l'accesso a rettangoli e poligoni che la descrivono nello spazio delle coordinate del testo. Esegue inoltre la ricerca di segmenti di testo e fornisce l'accesso ai risultati della ricerca tramite collezioni {@code TextFragments} raggruppate per elementi di struttura. </p> L'esempio dimostra come trovare il primo segmento di testo di ogni paragrafo nella prima pagina del documento PDF e evidenziarlo. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Quando la ricerca è completata, la collezione {@code ParagraphAbsorber.PageMarkups} conterrà oggetti {@code PageMarkup} che rappresentano la struttura della pagina mediante collezioni di {@code MarkupSection} e {@code MarkupParagraph}. L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore, ecc.).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Inizializza una nuova istanza di {@code ParagraphAbsorber} che esegue la ricerca di sezioni/paragrafi del documento o della pagina. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Inizializza una nuova istanza di {@code ParagraphAbsorber} che esegue la ricerca di sezioni/paragrafi del documento o della pagina. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Inizializza una nuova istanza di {@code ParagraphAbsorber} che esegue la ricerca di sezioni/paragrafi del documento o della pagina. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Inizializza una nuova istanza di {@code ParagraphAbsorber} che esegue la ricerca di sezioni/paragrafi del documento o della pagina. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Ottiene la collezione di {@code PageMarkup} che è stata assorbita. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | Ottiene le ParagraphAbsorberOptions. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Ottiene o imposta il valore che indica quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi ecc.) e tre ricerche per quelle divise verticalmente (colonne). </p><hr> L'aumento di questo valore può portare a una leggera diminuzione delle prestazioni senza cambiamenti visibili nei risultati della ricerca. La diminuzione di questo valore può portare a una determinazione errata dei paragrafi nelle sezioni. Non consigliamo di impostare un valore inferiore al predefinito se non si desidera ottenere solo elementi 'grezzi' della struttura della pagina. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Ottiene o imposta le TextReplaceOptions. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Ottiene o imposta il valore che indica se le linee di testo iniziali di una sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo di una sezione precedente. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Ottiene o imposta il valore che indica se le linee di testo iniziali di una sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo di una sezione precedente. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | Imposta le ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Ottiene o imposta il valore che indica quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi ecc.) e tre ricerche per quelle divise verticalmente (colonne). </p><hr> L'aumento di questo valore può portare a una leggera diminuzione delle prestazioni senza cambiamenti visibili nei risultati della ricerca. La diminuzione di questo valore può portare a una determinazione errata dei paragrafi nelle sezioni. Non consigliamo di impostare un valore inferiore al predefinito se non si desidera ottenere solo elementi 'grezzi' della struttura della pagina. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Ottiene o imposta le TextReplaceOptions. |
| [visit](#visit-com.aspose.pdf.Document-) | Esegue la ricerca di sezioni e paragrafi sul {@link Document} specificato. |
| [visit](#visit-com.aspose.pdf.Page-) | Esegue la ricerca sulla {@code Page} specificata. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Inizializza una nuova istanza di {@code ParagraphAbsorber} che esegue la ricerca di sezioni/paragrafi del documento o della pagina.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Inizializza una nuova istanza di {@code ParagraphAbsorber} che esegue la ricerca di sezioni/paragrafi del documento o della pagina. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sectionsSearchDepth |  | Numero di ricerche sequenziali per elementi più fini della struttura che verranno eseguite. <hr> Vedi la proprietà {@code ParagraphAbsorber.SectionsSearchDepth} per ulteriori indicazioni sul parametro. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Inizializza una nuova istanza di {@code ParagraphAbsorber} che esegue la ricerca di sezioni/paragrafi del documento o della pagina.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Inizializza una nuova istanza di {@code ParagraphAbsorber} che esegue la ricerca di sezioni/paragrafi del documento o della pagina.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Ottiene la collezione di {@code PageMarkup} che è stata assorbita.

**Returns:**
Elenco di istanze PageMarkup

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

Ottiene le ParagraphAbsorberOptions.

**Returns:**
Istanza ParagraphAbsorberOptions

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Ottiene o imposta il valore che indica quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi ecc.) e tre ricerche per quelle divise verticalmente (colonne). </p><hr> L'aumento di questo valore può portare a una leggera diminuzione delle prestazioni senza cambiamenti visibili nei risultati della ricerca. La diminuzione di questo valore può portare a una determinazione errata dei paragrafi nelle sezioni. Non consigliamo di impostare un valore inferiore al predefinito se non si desidera ottenere solo elementi 'grezzi' della struttura della pagina.

**Returns:**
valore int

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

Ottiene o imposta le TextReplaceOptions.

**Returns:**
Istanza di TextReplaceOptions

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Ottiene o imposta il valore che indica se le linee di testo iniziali di una sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo di una sezione precedente.

**Returns:**
valore booleano

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Ottiene o imposta il valore che indica se le linee di testo iniziali di una sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo di una sezione precedente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
Imposta le ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Ottiene o imposta il valore che indica quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi ecc.) e tre ricerche per quelle divise verticalmente (colonne). </p><hr> L'aumento di questo valore può portare a una leggera diminuzione delle prestazioni senza cambiamenti visibili nei risultati della ricerca. La diminuzione di questo valore può portare a una determinazione errata dei paragrafi nelle sezioni. Non consigliamo di impostare un valore inferiore al predefinito se non si desidera ottenere solo elementi 'grezzi' della struttura della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Ottiene o imposta le TextReplaceOptions.

### visit {#visit-com.aspose.pdf.Document-}
Esegue la ricerca di sezioni e paragrafi sul {@link Document} specificato.

### visit {#visit-com.aspose.pdf.Page-}
Esegue la ricerca sulla {@code Page} specificata.
