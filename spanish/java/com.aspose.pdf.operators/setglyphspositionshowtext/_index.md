---
title: "SetGlyphsPositionShowText"
linktitle: "SetGlyphsPositionShowText"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador TJ (muestra texto con posicionamiento de glifos)."
type: docs
weight: 630
url: /es/java/com.aspose.pdf.operators/setglyphspositionshowtext/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextShowOperator, com.aspose.pdf.operators.SetGlyphsPositionShowText

```
public class SetGlyphsPositionShowText extends TextShowOperator
```

Clase que representa el operador TJ (muestra texto con posicionamiento de glifos).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText--) | Inicializa el operador. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-) | Inicializa el operador. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-) | Inicializa el operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getGlyphPositions](#getGlyphPositions--) | Devuelve las posiciones de los glifos. |
| [getText](#getText--) | Obtiene el texto del argumento del operador (se ignora la posición de los glifos). |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText--}
```
public SetGlyphsPositionShowText()
```

Inicializa el operador.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-}
Inicializa el operador.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-}
Inicializa el operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getGlyphPositions {#getGlyphPositions--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerable< GlyphPosition > getGlyphPositions()
```

Devuelve las posiciones de los glifos.

**Returns:**
colección de instancias de GlyphPosition

### getText {#getText--}
```
public String getText()
```

Obtiene el texto del argumento del operador (se ignora la posición de los glifos).

**Returns:**
valor String

### toString {#toString--}
```
public String toString()
```

Devuelve la representación de texto del operador.

**Returns:**
Representación textual del operador.
