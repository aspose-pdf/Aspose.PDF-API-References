---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe décrit les règles qui peuvent être utilisées pour résoudre l'erreur Adobe Preflight « Le texte ne peut pas être mappé vers Unicode »."
type: docs
weight: 5380
url: /fr/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

Cette classe décrit les règles qui peuvent être utilisées pour résoudre l'erreur Adobe Preflight "Le texte ne peut pas être mappé à Unicode".

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Initialise une nouvelle instance de la classe {@link ToUnicodeProcessingRules}. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | Initialise une nouvelle instance de la classe {@link ToUnicodeProcessingRules} avec l'option spécifiée pour supprimer les espaces des noms CMap. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Initialise une nouvelle instance de la classe {@link ToUnicodeProcessingRules} avec les options spécifiées. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Certaines polices ne fournissent pas d'informations sur les unicodes pour certains symboles de texte. Cette absence d'information déclenche une erreur « Le texte ne peut pas être mappé vers Unicode ». Utilisez ce drapeau pour mapper les symboles non liés sur le caractère Unicode « espace » (code 32). |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Certaines polices ont des cartes de codes de caractères ToUnicode avec des espaces dans les noms. Ces espaces peuvent provoquer des erreurs de mappage de texte Unicode. Ce drapeau indique de supprimer les espaces des noms des cartes de codes de caractères ToUnicode. Par défaut, false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Certaines polices ne fournissent pas d'informations sur les unicodes pour certains symboles de texte. Cette absence d'information déclenche une erreur « Le texte ne peut pas être mappé vers Unicode ». Utilisez ce drapeau pour mapper les symboles non liés sur le caractère Unicode « espace » (code 32). |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Certaines polices ont des cartes de codes de caractères ToUnicode avec des espaces dans les noms. Ces espaces peuvent provoquer des erreurs de mappage de texte Unicode. Ce drapeau indique de supprimer les espaces des noms des cartes de codes de caractères ToUnicode. Par défaut, false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Initialise une nouvelle instance de la classe {@link ToUnicodeProcessingRules}.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

Initialise une nouvelle instance de la classe {@link ToUnicodeProcessingRules} avec l'option spécifiée pour supprimer les espaces des noms CMap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| removeSpaces |  | Valeur booléenne indiquant s'il faut supprimer les espaces des noms CMap. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Initialise une nouvelle instance de la classe {@link ToUnicodeProcessingRules} avec les options spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| removeSpaces |  | Indique si les espaces doivent être supprimés des noms CMap. |
| mapNonLinkedUnicodesOnSpace |  | Indique si les symboles Unicode non liés doivent être mappés sur des espaces. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Certaines polices ne fournissent pas d'informations sur les unicodes pour certains symboles de texte. Cette absence d'information déclenche une erreur « Le texte ne peut pas être mappé vers Unicode ». Utilisez ce drapeau pour mapper les symboles non liés sur le caractère Unicode « espace » (code 32).

**Returns:**
valeur booléenne

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Certaines polices ont des cartes de codes de caractères ToUnicode avec des espaces dans les noms. Ces espaces peuvent provoquer des erreurs de mappage de texte Unicode. Ce drapeau indique de supprimer les espaces des noms des cartes de codes de caractères ToUnicode. Par défaut, false.

**Returns:**
valeur booléenne

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Certaines polices ne fournissent pas d'informations sur les unicodes pour certains symboles de texte. Cette absence d'information déclenche une erreur « Le texte ne peut pas être mappé vers Unicode ». Utilisez ce drapeau pour mapper les symboles non liés sur le caractère Unicode « espace » (code 32).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Certaines polices ont des cartes de codes de caractères ToUnicode avec des espaces dans les noms. Ces espaces peuvent provoquer des erreurs de mappage de texte Unicode. Ce drapeau indique de supprimer les espaces des noms des cartes de codes de caractères ToUnicode. Par défaut, false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
