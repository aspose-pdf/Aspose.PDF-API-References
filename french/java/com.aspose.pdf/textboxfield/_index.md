---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant le champ de zone de texte."
type: docs
weight: 4930
url: /fr/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

Classe représentant le champ de zone de texte.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextBoxField](#TextBoxField--) | Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc) |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | Ajoute le code-barres 128 dans le champ. La valeur du champ sera remplacée par le code et le champ deviendra en lecture seule. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Ajoute une image dans les ressources du champ et la dessine. |
| [getForceCombs](#getForceCombs--) | Obtient le drapeau indiquant si le champ est divisé en positions espacées. |
| [getMaxLen](#getMaxLen--) | Obtient la longueur maximale du texte dans le champ. |
| [getMultiline](#getMultiline--) | Obtient le drapeau multiligne du champ. Si Multiline est vrai, le champ peut contenir plusieurs lignes de texte. |
| [getScrollable](#getScrollable--) | Obtient le drapeau défilable du champ. Si vrai, le champ peut être défilé. |
| [getSpellCheck](#getSpellCheck--) | Obtient le drapeau de vérification orthographique pour le champ. Si vrai, le champ sera vérifié orthographiquement. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | Obtient ou définit l'alignement vertical du texte pour l'annotation. |
| [getValue](#getValue--) | Obtient la valeur du champ. |
| [setForceCombs](#setForceCombs-boolean-) | Définit le drapeau qui indique si le champ est divisé en positions espacées. |
| [setJustification](#setJustification-boolean-) | Définit la justification |
| [setMaxLen](#setMaxLen-int-) | Définit la longueur maximale du texte dans le champ. |
| [setMultiline](#setMultiline-boolean-) | Définit le drapeau multiligne du champ. Si Multiline est vrai, le champ peut contenir plusieurs lignes de texte. |
| [setScrollable](#setScrollable-boolean-) | Définit le drapeau défilable du champ. Si vrai, le champ peut être défilé. |
| [setSpellCheck](#setSpellCheck-boolean-) | Définit le drapeau de vérification orthographique pour le champ. Si vrai, le champ sera vérifié orthographiquement. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtient ou définit l'alignement vertical du texte pour l'annotation. |
| [setValue](#setValue-java.lang.String-) | Définit la valeur du champ. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
Créer une instance de TextBoxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
Ajoute le code-barres 128 dans le champ. La valeur du champ sera remplacée par le code et le champ deviendra en lecture seule.

### addImage {#addImage-java.awt.image.BufferedImage-}
Ajoute une image dans les ressources du champ et la dessine.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

Obtient le drapeau indiquant si le champ est divisé en positions espacées.

**Returns:**
valeur booléenne

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

Obtient la longueur maximale du texte dans le champ.

**Returns:**
valeur int

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

Obtient le drapeau multiligne du champ. Si Multiline est vrai, le champ peut contenir plusieurs lignes de texte.

**Returns:**
valeur booléenne

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

Obtient le drapeau défilable du champ. Si vrai, le champ peut être défilé.

**Returns:**
valeur booléenne

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

Obtient le drapeau de vérification orthographique pour le champ. Si vrai, le champ sera vérifié orthographiquement.

**Returns:**
valeur booléenne

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

Obtient ou définit l'alignement vertical du texte pour l'annotation.

**Returns:**
Élément VerticalAlignment

### getValue {#getValue--}
```
public String getValue()
```

Obtient la valeur du champ.

**Returns:**
valeur String

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

Définit le drapeau qui indique si le champ est divisé en positions espacées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

Définit la justification

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

Définit la longueur maximale du texte dans le champ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

Définit le drapeau multiligne du champ. Si Multiline est vrai, le champ peut contenir plusieurs lignes de texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

Définit le drapeau défilable du champ. Si vrai, le champ peut être défilé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

Définit le drapeau de vérification orthographique pour le champ. Si vrai, le champ sera vérifié orthographiquement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtient ou définit l'alignement vertical du texte pour l'annotation.

### setValue {#setValue-java.lang.String-}
Définit la valeur du champ.
