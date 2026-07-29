---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Encapsule le résultat d'une opération visant à extraire le contenu non signé d'un document PDF. Cette classe fournit des informations sur le succès de l'opération, les détails de."
type: docs
weight: 40
url: /fr/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Encapsule le résultat d'une opération visant à extraire le contenu non signé d'un document PDF. Cette classe fournit des informations sur le succès de l'opération, les détails du contenu non signé, un message décrivant le résultat et le statut de couverture des signatures du document.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCoverage](#getCoverage--) | Obtient une valeur indiquant dans quelle mesure le document est couvert par des signatures numériques valides. |
| [getMessage](#getMessage--) | Obtient un message décrivant le résultat de l'opération. |
| [getSuccess](#getSuccess--) | Obtient une valeur indiquant si l'opération de récupération du contenu non signé du document a réussi. |
| [getUnsignedContent](#getUnsignedContent--) | Obtient un contenu non signé. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Obtient une valeur indiquant dans quelle mesure le document est couvert par des signatures numériques valides.

**Returns:**
une valeur indiquant dans quelle mesure le document est couvert par des signatures numériques valides.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Obtient un message décrivant le résultat de l'opération.

**Returns:**
un message décrivant le résultat de l'opération.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Obtient une valeur indiquant si l'opération de récupération du contenu non signé du document a réussi.

**Returns:**
une valeur indiquant si l'opération de récupération du contenu non signé du document a réussi.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Obtient un contenu non signé.

**Returns:**
un contenu non signé.
