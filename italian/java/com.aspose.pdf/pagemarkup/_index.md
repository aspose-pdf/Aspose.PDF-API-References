---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Markup della pagina rappresentato da collezioni di {@code MarkupSection} e {@code MarkupParagraph}."
type: docs
weight: 3420
url: /it/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

Markup della pagina rappresentato da collezioni di {@code MarkupSection} e {@code MarkupParagraph}.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNumber](#getNumber--) | Restituisce il numero di pagina elaborato. |
| [getParagraphs](#getParagraphs--) | Restituisce la collezione di {@code MarkupParagraph} trovata nella pagina. |
| [getRectangle](#getRectangle--) | Restituisce il rettangolo della pagina elaborata. |
| [getSections](#getSections--) | Restituisce la collezione di {@code MarkupSection} trovata nella pagina. |
| [getTextFragments](#getTextFragments--) | <p> Restituisce la collezione di {@code TextFragment} trovata nella pagina. </p><hr> Il oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo, e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Ottiene o imposta il valore che indica se le linee di testo iniziali di una sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo di una sezione precedente. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Ottiene o imposta il valore che indica se le linee di testo iniziali di una sezione successiva possono essere trattate come continuazione dell'ultimo paragrafo di una sezione precedente. |

### getNumber {#getNumber--}
```
public int getNumber()
```

Restituisce il numero di pagina elaborato.

**Returns:**
valore int

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Restituisce la collezione di {@code MarkupParagraph} trovata nella pagina.

**Returns:**
Elenco di istanze di MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Restituisce il rettangolo della pagina elaborata.

**Returns:**
oggetto Rectangle

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Restituisce la collezione di {@code MarkupSection} trovata nella pagina.

**Returns:**
Elenco di istanze di MarkupSection

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Restituisce la collezione di {@code TextFragment} trovata nella pagina. </p><hr> Il oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo, e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.).

**Returns:**
Elenco di istanze di TextFragment

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
