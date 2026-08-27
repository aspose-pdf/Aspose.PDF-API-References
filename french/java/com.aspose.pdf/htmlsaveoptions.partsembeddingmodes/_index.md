---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette énumération répertorie les modes possibles d'intégration des fichiers référencés dans le HTML. Elle permet de contrôler si les fichiers référencés (HTML, polices, images, CSS) seront intégrés dans le principal."
type: docs
weight: 2130
url: /fr/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Cette énumération énumère les modes possibles d'intégration des fichiers référencés dans le HTML. Elle permet de contrôler si les fichiers référencés (HTML, polices, images, CSS) seront incorporés dans le fichier HTML principal ou générés comme des entités binaires séparées.

## Champs

| Champ | Description |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Force l'intégration de tous les fichiers référencés (CSS, images, polices) dans le balisage HTML généré (c'est‑à‑dire dans le HTML lui‑même). Cette approche génère un seul fichier HTML, mais la taille totale de la sortie devient plus grande (car l'encodage Base64 des binaires est utilisé) et tous les navigateurs (en particulier les anciens) ne traitent pas toujours correctement les binaires intégrés dans le HTML. Mais elle permet d'obtenir un HTML contenant le résultat complet, sans aucun fichier supplémentaire. |
| [EmbedCssOnly](#EmbedCssOnly) | Force la séparation de tous les fichiers référencés sauf le CSS (images et polices). Ainsi, le CSS sera intégré dans le HTML résultant, tandis que tous les autres fichiers référencés (images et polices) seront traités comme des parties externes. Cela génère un HTML adapté à un large éventail de navigateurs. |
| [NoEmbedding](#NoEmbedding) | Force la séparation des fichiers référencés (CSS, images, polices). Cette approche génère un ensemble de fichiers, mais la taille totale de la sortie devient plus petite (car aucun encodage Base64 des binaires n'est utilisé). De plus, cette approche génère un HTML adapté à un large éventail de navigateurs. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Force l'intégration de tous les fichiers référencés (CSS, images, polices) dans le balisage HTML généré (c'est‑à‑dire dans le HTML lui‑même). Cette approche génère un seul fichier HTML, mais la taille totale de la sortie devient plus grande (car l'encodage Base64 des binaires est utilisé) et tous les navigateurs (en particulier les anciens) ne traitent pas toujours correctement les binaires intégrés dans le HTML. Mais elle permet d'obtenir un HTML contenant le résultat complet, sans aucun fichier supplémentaire.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

Force la séparation de tous les fichiers référencés sauf le CSS (images et polices). Ainsi, le CSS sera intégré dans le HTML résultant, tandis que tous les autres fichiers référencés (images et polices) seront traités comme des parties externes. Cela génère un HTML adapté à un large éventail de navigateurs.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Force la séparation des fichiers référencés (CSS, images, polices). Cette approche génère un ensemble de fichiers, mais la taille totale de la sortie devient plus petite (car aucun encodage Base64 des binaires n'est utilisé). De plus, cette approche génère un HTML adapté à un large éventail de navigateurs.
