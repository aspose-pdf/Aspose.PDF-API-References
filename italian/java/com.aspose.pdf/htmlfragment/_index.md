---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un frammento html."
type: docs
weight: 1950
url: /it/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

Rappresenta un frammento html.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | Inizializza una nuova istanza della classe HtmlFragment. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona frammento html. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Ottiene HtmlLoadOptions che verranno utilizzati per il caricamento (e il rendering) di HTML in questa istanza della classe. Si prega di usarlo quando è necessario utilizzare impostazioni specifiche per l'importazione di HTML per questa o quella istanza (ad es. quando questa o quella istanza deve utilizzare un BasePath specifico per l'HTML importato o deve utilizzare un loader specifico di risorse esterne). Se il parametro è predefinito (null), verranno utilizzate le opzioni standard di caricamento HTML. |
| [getRectangle](#getRectangle--) | Ottiene il rettangolo dell'HtmlFragment |
| [getTextState](#getTextState--) | Ottiene o imposta il font |
| [isBreakWords](#isBreakWords--) | Ottiene o imposta l'interruzione delle parole |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Ottiene o imposta se il paragrafo ha il margine predefinito, altrimenti il margine è 0 |
| [setBreakWords](#setBreakWords-boolean-) | Ottiene o imposta l'interruzione delle parole |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Imposta HtmlLoadOptions che verranno utilizzati per il caricamento (e il rendering) di HTML in questa istanza della classe. Si prega di usarlo quando è necessario utilizzare impostazioni specifiche per l'importazione di HTML per questa o quella istanza (ad es. quando questa o quella istanza deve utilizzare un BasePath specifico per l'HTML importato o deve utilizzare un loader specifico di risorse esterne). Se il parametro è predefinito (null), verranno utilizzate le opzioni standard di caricamento HTML. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Ottiene o imposta se il paragrafo ha il margine predefinito, altrimenti il margine è 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Ottiene o imposta il font |

### HtmlFragment {#HtmlFragment-java.lang.String-}
Inizializza una nuova istanza della classe HtmlFragment.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona frammento html.

**Returns:**
Oggetto frammento html clonato.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Ottiene HtmlLoadOptions che verranno utilizzati per il caricamento (e il rendering) di HTML in questa istanza della classe. Si prega di usarlo quando è necessario utilizzare impostazioni specifiche per l'importazione di HTML per questa o quella istanza (ad es. quando questa o quella istanza deve utilizzare un BasePath specifico per l'HTML importato o deve utilizzare un loader specifico di risorse esterne). Se il parametro è predefinito (null), verranno utilizzate le opzioni standard di caricamento HTML.

**Returns:**
Valore HtmlLoadOptions

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Ottiene il rettangolo dell'HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float instance

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Ottiene o imposta il font

**Returns:**
Oggetto TextState

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Ottiene o imposta l'interruzione delle parole

**Returns:**
valore booleano

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Ottiene o imposta se il paragrafo ha il margine predefinito, altrimenti il margine è 0

**Returns:**
valore booleano

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Ottiene o imposta l'interruzione delle parole

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Imposta HtmlLoadOptions che verranno utilizzati per il caricamento (e il rendering) di HTML in questa istanza della classe. Si prega di usarlo quando è necessario utilizzare impostazioni specifiche per l'importazione di HTML per questa o quella istanza (ad es. quando questa o quella istanza deve utilizzare un BasePath specifico per l'HTML importato o deve utilizzare un loader specifico di risorse esterne). Se il parametro è predefinito (null), verranno utilizzate le opzioni standard di caricamento HTML.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Ottiene o imposta se il paragrafo ha il margine predefinito, altrimenti il margine è 0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Ottiene o imposta il font
