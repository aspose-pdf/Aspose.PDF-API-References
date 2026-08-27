---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un oggetto assorbitore di paragrafi di testo. Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextParagraphAbsorber.TextParagraphs}."
type: docs
weight: 5220
url: /it/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

Rappresenta un oggetto assorbitore di paragrafi di testo. Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextParagraphAbsorber.TextParagraphs}.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> Inizializza una nuova istanza di {@code TextParagraphAbsorber} con la collezione di rettangoli. </p> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRectangles](#getRectangles--) | Restituisce i rettangoli che {@code TextParagraphAbsorber} utilizza per cercare i paragrafi di testo nel documento PDF o nella pagina. |
| [getTextParagraphs](#getTextParagraphs--) | Restituisce la collezione di occorrenze di ricerca presentate con oggetti {@code TextParagraph}. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | Imposta i rettangoli che {@code TextParagraphAbsorber} utilizza per cercare i paragrafi di testo nel documento PDF o nella pagina. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Imposta la collezione di occorrenze di ricerca presentate con oggetti {@code TextParagraph}. |
| [visit](#visit-com.aspose.pdf.Page-) | Esegue la ricerca nella pagina specificata. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> Inizializza una nuova istanza di {@code TextParagraphAbsorber} con la collezione di rettangoli. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

Restituisce i rettangoli che {@code TextParagraphAbsorber} utilizza per cercare i paragrafi di testo nel documento PDF o nella pagina.

**Returns:**
array di rettangoli

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

Restituisce la collezione di occorrenze di ricerca presentate con oggetti {@code TextParagraph}.

**Returns:**
Valore di TextParagraphCollection

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
Imposta i rettangoli che {@code TextParagraphAbsorber} utilizza per cercare i paragrafi di testo nel documento PDF o nella pagina.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
Imposta la collezione di occorrenze di ricerca presentate con oggetti {@code TextParagraph}.

### visit {#visit-com.aspose.pdf.Page-}
Esegue la ricerca nella pagina specificata.
