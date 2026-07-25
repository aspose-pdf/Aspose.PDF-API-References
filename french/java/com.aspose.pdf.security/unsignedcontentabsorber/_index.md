---
title: "UnsignedContentAbsorber"
linktitle: "UnsignedContentAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant d'extraire le contenu non signé d'un fichier PDF géré par des signatures numériques."
type: docs
weight: 30
url: /fr/java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

Représente une classe permettant d'extraire le contenu non signé d'un fichier PDF géré par des signatures numériques.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | Représente une classe utilisée pour le traitement du contenu non signé. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [tryGetContent](#tryGetContent--) | Tentative de récupération du contenu non signé du document associé. |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
Représente une classe utilisée pour le traitement du contenu non signé.

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

Tentative de récupération du contenu non signé du document associé.

**Returns:**
Un objet {@link UnsignedContentAbsorber.Result} contenant des détails sur le contenu non signé, la couverture des signatures numériques, le statut de réussite de l'opération et un message d'information.
