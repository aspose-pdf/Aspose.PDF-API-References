---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un'annotazione di testo libero che visualizza il testo direttamente sulla pagina. A differenza di un'annotazione di testo ordinaria, un'annotazione di testo libero non ha uno stato aperto o chiuso; invece."
type: docs
weight: 1790
url: /it/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Rappresenta un'annotazione di testo libero che visualizza il testo direttamente sulla pagina. A differenza di un'annotazione di testo ordinaria, un'annotazione di testo libero non ha uno stato aperto o chiuso; invece di essere visualizzata in una finestra pop-up, il testo è sempre visibile.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Costruttore da utilizzare con Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Crea una nuova annotazione FreeText nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getCallout](#getCallout--) | Array di punti che specificano la linea di richiamo. |
| [getDefaultAppearance](#getDefaultAppearance--) | Ottiene la stringa di aspetto predefinita da utilizzare nella formattazione del testo. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | Oggetto che rappresenta l'aspetto predefinito dell'annotazione FreeText. |
| [getDefaultStyle](#getDefaultStyle--) | Ottiene una stringa di stile predefinita. |
| [getEndingStyle](#getEndingStyle--) | Ottiene lo stile di terminazione della linea per il punto finale della linea. |
| [getIntent](#getIntent--) | Ottiene l'intento dell'annotazione di testo libero. |
| [getJustification](#getJustification--) | Ottiene un codice che specifica la forma di allineamento (giustificazione) da utilizzare nella visualizzazione del testo dell'annotazione. |
| [getRotate](#getRotate--) | Angolo di rotazione dell'annotazione. |
| [getStartingStyle](#getStartingStyle--) | Ottiene o imposta lo stile di terminazione della linea per il punto finale della linea. Questa proprietà è obsoleta, si prega di utilizzare EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | Rettangolo che descrive le differenze numeriche tra due rettangoli: l'elemento Rect dell'annotazione e un rettangolo contenuto all'interno di quel rettangolo. Il rettangolo interno è dove dovrebbe essere visualizzato il testo dell'annotazione. |
| [getTextStyle](#getTextStyle--) | Ottiene o imposta lo stile del testo nell'aspetto. Quando lo stile del testo viene modificato, l'aspetto del testo viene aggiornato. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Array di punti che specificano la linea di richiamo. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Imposta la stringa di aspetto predefinita da utilizzare nella formattazione del testo. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Imposta una stringa di stile predefinita. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Imposta lo stile di terminazione della linea per il punto finale della linea. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Imposta l'intento dell'annotazione di testo libero. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Imposta un codice che specifica la forma di allineamento (giustificazione) da utilizzare nella visualizzazione del testo dell'annotazione. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Angolo di rotazione dell'annotazione. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Ottiene o imposta lo stile di terminazione della linea per il punto finale della linea. Questa proprietà è obsoleta, si prega di utilizzare EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Rettangolo che descrive le differenze numeriche tra due rettangoli: l'elemento Rect dell'annotazione e un rettangolo contenuto all'interno di quel rettangolo. Il rettangolo interno è dove dovrebbe essere visualizzato il testo dell'annotazione. |
| [setTextStyle](#setTextStyle-int-int-int-) | Imposta la formattazione determinata dal parametro textStyle per un frammento di testo dall'indice fromInd all'indice toInd. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | Imposta la formattazione determinata dal parametro textStyle per tutto il testo dell'annotazione. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Imposta lo stile del testo nell'aspetto. Quando lo stile del testo viene modificato, l'aspetto del testo viene aggiornato. |
| [updateAppearance](#updateAppearance--) | Aggiorna l'Aspetto dopo che il testo è stato modificato/spostato. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Costruttore da utilizzare con Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Crea una nuova annotazione FreeText nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
valore int

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Array di punti che specificano la linea di richiamo.

**Returns:**
array di Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Ottiene la stringa di aspetto predefinita da utilizzare nella formattazione del testo.

**Returns:**
valore String

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

Oggetto che rappresenta l'aspetto predefinito dell'annotazione FreeText.

**Returns:**
oggetto DefaultAppearance

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Ottiene una stringa di stile predefinita.

**Returns:**
valore String

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Ottiene lo stile di terminazione della linea per il punto finale della linea.

**Returns:**
valore LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Ottiene l'intento dell'annotazione di testo libero.

**Returns:**
valore int @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Ottiene un codice che specifica la forma di allineamento (giustificazione) da utilizzare nella visualizzazione del testo dell'annotazione.

**Returns:**
valore int @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Angolo di rotazione dell'annotazione.

**Returns:**
elemento Rotation @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Ottiene o imposta lo stile di terminazione della linea per il punto finale della linea. Questa proprietà è obsoleta, si prega di utilizzare EndingStyle.

**Returns:**
elemento LineEnding

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Rettangolo che descrive le differenze numeriche tra due rettangoli: l'elemento Rect dell'annotazione e un rettangolo contenuto all'interno di quel rettangolo. Il rettangolo interno è dove dovrebbe essere visualizzato il testo dell'annotazione.

**Returns:**
Istanza Rectangle

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Ottiene o imposta lo stile del testo nell'aspetto. Quando lo stile del testo viene modificato, l'aspetto del testo viene aggiornato.

**Returns:**
valore TextStyle

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Array di punti che specificano la linea di richiamo.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Imposta la stringa di aspetto predefinita da utilizzare nella formattazione del testo.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Imposta una stringa di stile predefinita.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Imposta lo stile di terminazione della linea per il punto finale della linea.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Imposta l'intento dell'annotazione di testo libero.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Imposta un codice che specifica la forma di allineamento (giustificazione) da utilizzare nella visualizzazione del testo dell'annotazione.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Angolo di rotazione dell'annotazione.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Ottiene o imposta lo stile di terminazione della linea per il punto finale della linea. Questa proprietà è obsoleta, si prega di utilizzare EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Rettangolo che descrive le differenze numeriche tra due rettangoli: l'elemento Rect dell'annotazione e un rettangolo contenuto all'interno di quel rettangolo. Il rettangolo interno è dove dovrebbe essere visualizzato il testo dell'annotazione.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

Imposta la formattazione determinata dal parametro textStyle per un frammento di testo dall'indice fromInd all'indice toInd.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fromInd |  | Indice iniziale del frammento di testo (da 0). |
| toInd |  | Indice finale del frammento di testo (contando da 0, questo non è incluso). |
| textStyles |  | Stile(i) applicato(i) al frammento di testo. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
Imposta la formattazione determinata dal parametro textStyle per tutto il testo dell'annotazione.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Imposta lo stile del testo nell'aspetto. Quando lo stile del testo viene modificato, l'aspetto del testo viene aggiornato.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Aggiorna l'Aspetto dopo che il testo è stato modificato/spostato.
