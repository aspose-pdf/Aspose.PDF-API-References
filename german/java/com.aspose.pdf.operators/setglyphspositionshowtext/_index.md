---
title: "SetGlyphsPositionShowText"
linktitle: "SetGlyphsPositionShowText"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den TJ-Operator darstellt (Text mit Glyphenpositionierung anzeigen)."
type: docs
weight: 630
url: /de/java/com.aspose.pdf.operators/setglyphspositionshowtext/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextShowOperator, com.aspose.pdf.operators.SetGlyphsPositionShowText

```
public class SetGlyphsPositionShowText extends TextShowOperator
```

Klasse, die den TJ-Operator darstellt (Text mit Glyphenpositionierung anzeigen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText--) | Initialisiert den Operator. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-) | Initialisiert den Operator. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-) | Initialisiert den Operator. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getGlyphPositions](#getGlyphPositions--) | Gibt die Positionen der Glyphen zurück. |
| [getText](#getText--) | Gibt den Text aus dem Operator-Argument zurück (Glyph-Positionierung wird ignoriert). |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText--}
```
public SetGlyphsPositionShowText()
```

Initialisiert den Operator.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-}
Initialisiert den Operator.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-}
Initialisiert den Operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getGlyphPositions {#getGlyphPositions--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerable< GlyphPosition > getGlyphPositions()
```

Gibt die Positionen der Glyphen zurück.

**Returns:**
Sammlung von GlyphPosition-Instanzen

### getText {#getText--}
```
public String getText()
```

Gibt den Text aus dem Operator-Argument zurück (Glyph-Positionierung wird ignoriert).

**Returns:**
String Wert

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.
