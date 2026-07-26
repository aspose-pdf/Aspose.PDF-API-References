---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un paragrafo."
type: docs
weight: 2880
url: /it/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Rappresenta un paragrafo.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | Elenco dei numeri di pagina su cui il paragrafo continua. Corrisponderà alla pagina in cui il paragrafo è iniziato se continua nella colonna successiva sulla stessa pagina. |
| [getFragments](#getFragments--) | <p> Collezione di oggetti {@code TextFragment} non vuoti del paragrafo. </p><hr> L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Linee del paragrafo. Ogni linea è rappresentata da un elenco di frammenti di testo. </p><hr> L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Punti del poligono che descrive il paragrafo. Il punto iniziale è l'angolo inferiore sinistro del paragrafo. I punti successivi sono in sequenza antioraria. |
| [getSecondaryPoints](#getSecondaryPoints--) | Punti del poligono secondario che descrive la continuazione del paragrafo. Non sarà nullo se il paragrafo continua nella colonna o nella pagina successiva. Il punto iniziale è l'angolo inferiore sinistro del paragrafo. I punti successivi sono in sequenza antioraria. |
| [getText](#getText--) | Restituisce l'oggetto testo {@code string} che l'oggetto {@code MarkupParagraph} rappresenta. |
| [setText](#setText-java.lang.String-) | Ottiene o imposta il testo del paragrafo. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

Elenco dei numeri di pagina su cui il paragrafo continua. Corrisponderà alla pagina in cui il paragrafo è iniziato se continua nella colonna successiva sulla stessa pagina.

**Returns:**
elenco di Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Collezione di oggetti {@code TextFragment} non vuoti del paragrafo. </p><hr> L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.).

**Returns:**
elenco di istanze di TextFragment

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Linee del paragrafo. Ogni linea è rappresentata da un elenco di frammenti di testo. </p><hr> L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore ecc.).

**Returns:**
elenco di istanze di TextFragment

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punti del poligono che descrive il paragrafo. Il punto iniziale è l'angolo inferiore sinistro del paragrafo. I punti successivi sono in sequenza antioraria.

**Returns:**
array di istanze di Point

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Punti del poligono secondario che descrive la continuazione del paragrafo. Non sarà nullo se il paragrafo continua nella colonna o nella pagina successiva. Il punto iniziale è l'angolo inferiore sinistro del paragrafo. I punti successivi sono in sequenza antioraria.

**Returns:**
elenco di Point[]

### getText {#getText--}
```
public String getText()
```

Restituisce l'oggetto testo {@code string} che l'oggetto {@code MarkupParagraph} rappresenta.

**Returns:**
valore String

### setText {#setText-java.lang.String-}
Ottiene o imposta il testo del paragrafo.
