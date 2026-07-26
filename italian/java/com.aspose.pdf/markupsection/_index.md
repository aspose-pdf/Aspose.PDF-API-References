---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una sezione di markup - la regione rettangolare di una pagina che contiene testo e può essere visualmente separata da altri blocchi di testo."
type: docs
weight: 2890
url: /it/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Rappresenta una sezione di markup - la regione rettangolare di una pagina che contiene testo e può essere visualmente separata da altri blocchi di testo.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFragments](#getFragments--) | <p> Raccolta di oggetti {@code TextFragment} non vuoti che si trovano all'interno della sezione. </p><hr> L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.). |
| [getParagraphs](#getParagraphs--) | Raccolta di oggetti {@code MarkupParagraph} che si trovano all'interno della sezione. |
| [getRectangle](#getRectangle--) | Rettangolo della sezione |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Raccolta di oggetti {@code TextFragment} non vuoti che si trovano all'interno della sezione. </p><hr> L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.).

**Returns:**
elenco di istanze di TextFragment

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Raccolta di oggetti {@code MarkupParagraph} che si trovano all'interno della sezione.

**Returns:**
elenco di istanze di MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Rettangolo della sezione

**Returns:**
Istanza Rectangle
