---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe base astratta per le annotazioni di markup del testo."
type: docs
weight: 5180
url: /it/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Classe base astratta per le annotazioni di markup del testo.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aggiorna i QuadPoints, secondo la trasformazione della matrice. |
| [getMarkedText](#getMarkedText--) | Ottiene il testo sotto l'annotazione markup come stringa. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | Ottiene il testo sotto l'annotazione markup come {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | Restituisce un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero comprende una parola o un gruppo di parole contigue nel testo sottostante l'annotazione. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Imposta un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero comprende una parola o un gruppo di parole contigue nel testo sottostante l'annotazione. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aggiorna i QuadPoints, secondo la trasformazione della matrice.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

Ottiene il testo sotto l'annotazione markup come stringa.

**Returns:**
Stringa contenente il testo che è sotto l'annotazione markup.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

Ottiene il testo sotto l'annotazione markup come {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} contenente {@code TextFragment}s che è sotto l'annotazione markup.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

Restituisce un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero comprende una parola o un gruppo di parole contigue nel testo sottostante l'annotazione.

**Returns:**
array di valore Point

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Imposta un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero comprende una parola o un gruppo di parole contigue nel testo sottostante l'annotazione.
