---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe contient les paramètres qui définissent le comportement de PdfContentEditor lors de l'exécution de l'opération ReplaceText."
type: docs
weight: 650
url: /fr/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

Cette classe contient les paramètres qui définissent le comportement de PdfContentEditor lors de l'exécution de l'opération ReplaceText.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Action effectuée lorsqu'aucune police appropriée n'est trouvée pour le texte modifié (Lancer une exception / Substituer une autre police / Remplacer quand même). |
| [getReplaceScope](#getReplaceScope--) | Portée de l'opération de remplacement (remplacer la première occurrence ou remplacer toutes les occurrences). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Si false, la chaîne à rechercher est un texte simple. Si true, la chaîne à rechercher est une expression régulière. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Action effectuée lorsqu'aucune police appropriée n'est trouvée pour le texte modifié (Lancer une exception / Substituer une autre police / Remplacer quand même). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Si false, la chaîne à rechercher est un texte simple. Si true, la chaîne à rechercher est une expression régulière. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Portée de l'opération de remplacement (remplacer la première occurrence ou remplacer toutes les occurrences). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Action effectuée lorsqu'aucune police appropriée n'est trouvée pour le texte modifié (Lancer une exception / Substituer une autre police / Remplacer quand même).

**Returns:**
Valeur NoCharacterAction. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Portée de l'opération de remplacement (remplacer la première occurrence ou remplacer toutes les occurrences).

**Returns:**
Élément Scope @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Si false, la chaîne à rechercher est un texte simple. Si true, la chaîne à rechercher est une expression régulière.

**Returns:**
valeur booléenne

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Action effectuée lorsqu'aucune police appropriée n'est trouvée pour le texte modifié (Lancer une exception / Substituer une autre police / Remplacer quand même).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Si false, la chaîne à rechercher est un texte simple. Si true, la chaîne à rechercher est une expression régulière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Portée de l'opération de remplacement (remplacer la première occurrence ou remplacer toutes les occurrences).
