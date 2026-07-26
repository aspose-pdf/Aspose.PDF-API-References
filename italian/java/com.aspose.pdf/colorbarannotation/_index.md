---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'annotazione ColorBarAnnotation. Proprietà Color ignorata, invece viene usato il colore ColorsOfCMYK. Alla creazione, il rapporto tra larghezza e altezza determina l'orientamento."
type: docs
weight: 680
url: /it/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Classe che rappresenta l'annotazione ColorBarAnnotation. La proprietà Color è ignorata, invece viene usato il colore ColorsOfCMYK. Alla creazione, il rapporto tra larghezza e altezza determina l'orientamento dell'annotazione - orizzontale o verticale. Successivamente, verifica che il rettangolo dell'annotazione sia al di fuori del TrimBox e, se non lo è, viene spostato nella posizione più vicina al di fuori del TrimBox, tenendo conto dell'orientamento dell'annotazione. È possibile ridurre la larghezza (altezza) affinché l'annotazione si adatti al di fuori del TrimBox. Se non c'è spazio per il layout, larghezza/altezza può essere impostata a zero (in tal caso, l'annotazione è presente nella pagina, ma non visualizzata).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nuova annotazione ColorBar nella pagina specificata. Predefinito ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Crea una nuova annotazione ColorBar nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aggiorna parametri e aspetto, in base alla trasformazione della matrice e allo spostamento al di fuori del TrimBox se necessario. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getColorOfCMYK](#getColorOfCMYK--) | Ottiene o imposta il colore (uno tra ciano, magenta, giallo, nero) con cui l'annotazione viene disegnata. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Ottiene o imposta il colore (uno tra ciano, magenta, giallo, nero) con cui l'annotazione viene disegnata. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nuova annotazione ColorBar nella pagina specificata. Predefinito ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Crea una nuova annotazione ColorBar nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aggiorna parametri e aspetto, in base alla trasformazione della matrice e allo spostamento al di fuori del TrimBox se necessario.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
valore int

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Ottiene o imposta il colore (uno tra ciano, magenta, giallo, nero) con cui l'annotazione viene disegnata.

**Returns:**
Elemento ColorsOfCMYK

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Ottiene o imposta il colore (uno tra ciano, magenta, giallo, nero) con cui l'annotazione viene disegnata.
