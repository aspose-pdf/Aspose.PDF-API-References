---
title: "SetGlyphsPositionShowText"
linktitle: "SetGlyphsPositionShowText"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur TJ (affiche le texte avec le positionnement des glyphes)."
type: docs
weight: 630
url: /fr/java/com.aspose.pdf.operators/setglyphspositionshowtext/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextShowOperator, com.aspose.pdf.operators.SetGlyphsPositionShowText

```
public class SetGlyphsPositionShowText extends TextShowOperator
```

Classe représentant l'opérateur TJ (affiche le texte avec le positionnement des glyphes).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText--) | Initialise l'opérateur. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-) | Initialise l'opérateur. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-) | Initialise l'opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getGlyphPositions](#getGlyphPositions--) | Renvoie les positions des glyphes. |
| [getText](#getText--) | Obtient le texte de l'argument de l'opérateur (le positionnement des glyphes est ignoré). |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText--}
```
public SetGlyphsPositionShowText()
```

Initialise l'opérateur.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-}
Initialise l'opérateur.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-}
Initialise l'opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getGlyphPositions {#getGlyphPositions--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerable< GlyphPosition > getGlyphPositions()
```

Renvoie les positions des glyphes.

**Returns:**
collection d'instances GlyphPosition

### getText {#getText--}
```
public String getText()
```

Obtient le texte de l'argument de l'opérateur (le positionnement des glyphes est ignoré).

**Returns:**
valeur String

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
