---
title: "HiddenDataSanitizer"
linktitle: "HiddenDataSanitizer"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour désinfecter les données cachées."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.security/hiddendatasanitizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizer

```
public final class HiddenDataSanitizer extends Object
```

Représente une classe pour désinfecter les données cachées.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HiddenDataSanitizer](#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-) | Fournit des fonctionnalités pour nettoyer les données cachées d'un document PDF, en veillant à ce que les informations sensibles ou inutiles telles que les métadonnées, les annotations, les JavaScripts ou le contenu privé soient supprimées ou transformées. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [sanitize](#sanitize-com.aspose.pdf.Document-) | Nettoie un document PDF donné en supprimant ou en transformant les données cachées. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-) | Remplace le contenu des pages par des images et supprime les autres données cachées. Vous permet de supprimer le texte caché avec une couleur d'arrière-plan, ainsi que le texte caché sous les images. Aussi, supprime complètement tous les éléments interactifs. Le document est converti en images tel quel, puis nettoyé de toutes les données cachées restantes. Si vous devez d'abord nettoyer puis convertir, utilisez la méthode principale de la classe. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-int-) | Remplace le contenu des pages par des images et supprime les autres données cachées. Vous permet de supprimer le texte caché avec une couleur d'arrière-plan, ainsi que le texte caché sous les images. Supprime également complètement tous les éléments interactifs. Le document est converti en images tel quel, puis nettoyé de toutes les données cachées restantes. Si vous devez d'abord nettoyer puis convertir, utilisez la méthode principale de la classe. |

### HiddenDataSanitizer {#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-}
Fournit des fonctionnalités pour nettoyer les données cachées d'un document PDF, en veillant à ce que les informations sensibles ou inutiles telles que les métadonnées, les annotations, les JavaScripts ou le contenu privé soient supprimées ou transformées.

### sanitize {#sanitize-com.aspose.pdf.Document-}
Nettoie un document PDF donné en supprimant ou en transformant les données cachées.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-}
Remplace le contenu des pages par des images et supprime les autres données cachées. Vous permet de supprimer le texte caché avec une couleur d'arrière-plan, ainsi que le texte caché sous les images. Aussi, supprime complètement tous les éléments interactifs. Le document est converti en images tel quel, puis nettoyé de toutes les données cachées restantes. Si vous devez d'abord nettoyer puis convertir, utilisez la méthode principale de la classe.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-int-}
Remplace le contenu des pages par des images et supprime les autres données cachées. Vous permet de supprimer le texte caché avec une couleur d'arrière-plan, ainsi que le texte caché sous les images. Supprime également complètement tous les éléments interactifs. Le document est converti en images tel quel, puis nettoyé de toutes les données cachées restantes. Si vous devez d'abord nettoyer puis convertir, utilisez la méthode principale de la classe.
