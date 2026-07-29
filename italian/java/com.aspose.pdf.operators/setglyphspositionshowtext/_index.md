---
title: "SetGlyphsPositionShowText"
linktitle: "SetGlyphsPositionShowText"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore TJ (mostra il testo con posizionamento dei glifi)."
type: docs
weight: 630
url: /it/java/com.aspose.pdf.operators/setglyphspositionshowtext/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextShowOperator, com.aspose.pdf.operators.SetGlyphsPositionShowText

```
public class SetGlyphsPositionShowText extends TextShowOperator
```

Classe che rappresenta l'operatore TJ (mostra il testo con posizionamento dei glifi).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText--) | Inizializza l'operatore. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-) | Inizializza l'operatore. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-) | Inizializza l'operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getGlyphPositions](#getGlyphPositions--) | Restituisce le posizioni dei glifi. |
| [getText](#getText--) | Ottiene il testo dall'argomento dell'operatore (la posizione dei glifi è ignorata). |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText--}
```
public SetGlyphsPositionShowText()
```

Inizializza l'operatore.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-}
Inizializza l'operatore.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-}
Inizializza l'operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getGlyphPositions {#getGlyphPositions--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerable< GlyphPosition > getGlyphPositions()
```

Restituisce le posizioni dei glifi.

**Returns:**
collezione di istanze di GlyphPosition

### getText {#getText--}
```
public String getText()
```

Ottiene il testo dall'argomento dell'operatore (la posizione dei glifi è ignorata).

**Returns:**
valore String

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.
