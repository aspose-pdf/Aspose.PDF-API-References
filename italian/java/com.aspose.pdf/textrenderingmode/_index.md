---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La modalità di rendering del testo, Tmode, determina se la visualizzazione del testo deve far sì che i contorni dei glifi siano tracciati, riempiti, usati come limite di ritaglio, o una combinazione dei tre."
type: docs
weight: 5240
url: /it/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

La modalità di rendering del testo, Tmode, determina se la visualizzazione del testo deve far sì che i contorni dei glifi siano tracciati, riempiti, usati come limite di ritaglio, o una combinazione dei tre.

## Campi

| Campo | Descrizione |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Aggiungi testo al percorso per il ritaglio. |
| [FillText](#FillText) | Riempi il testo. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Riempi il testo e aggiungi al percorso per il ritaglio (vedi 9.3.6, "Text Rendering Mode,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Riempi, poi traccia il testo. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Riempi, poi traccia il testo e aggiungi al percorso per il ritaglio. |
| [Invisible](#Invisible) | Né riempire né tracciare il testo (invisibile). |
| [StrokeText](#StrokeText) | Traccia il testo. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Traccia il testo e aggiungi al percorso per il ritaglio. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Aggiungi testo al percorso per il ritaglio.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Riempi il testo.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Riempi il testo e aggiungi al percorso per il ritaglio (vedi 9.3.6, "Text Rendering Mode,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Riempi, poi traccia il testo.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Riempi, poi traccia il testo e aggiungi al percorso per il ritaglio.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Né riempire né tracciare il testo (invisibile).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Traccia il testo.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Traccia il testo e aggiungi al percorso per il ritaglio.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
