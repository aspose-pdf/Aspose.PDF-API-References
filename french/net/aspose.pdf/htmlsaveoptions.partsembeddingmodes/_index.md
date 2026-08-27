---
title: "Enum HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes enum. Cette énumération répertorie les modes possibles d'intégration des fichiers référencés dans le HTML. Elle permet de contrôler si les fichiers référencés (HTML, polices, images, CSS) seront intégrés dans le fichier HTML principal ou générés comme entités binaires séparées."
type: docs
weight: 5840
url: /fr/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

Cette énumération répertorie les modes possibles d'intégration des fichiers référencés dans le HTML. Elle permet de contrôler si les fichiers référencés (HTML, polices, images, CSS) seront intégrés dans le fichier HTML principal ou générés comme entités binaires séparées.

```csharp
public enum PartsEmbeddingModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Force l'intégration de tous les fichiers référencés (CSS, images, polices) dans le balisage HTML généré (c’est‑à‑dire dans le HTML lui‑même). Cette approche génère un seul fichier HTML, mais la taille totale du résultat augmente (car l’encodage Base64 des binaires est utilisé) et tous les navigateurs (en particulier les anciens) ne traitent pas toujours correctement les binaires intégrés dans le HTML. Cependant, elle permet d’obtenir un HTML contenant le résultat complet, sans fichiers supplémentaires. |
| EmbedCssOnly | `1` | Force la séparation de tous les fichiers référencés sauf le CSS (images et polices). Ainsi, le CSS sera intégré dans le HTML résultant, tandis que les autres fichiers référencés (images et polices) seront traités comme des parties externes. Cela génère un HTML compatible avec un large éventail de navigateurs. |
| NoEmbedding | `2` | Force la séparation des fichiers référencés (CSS, images, polices). Cette approche génère un ensemble de fichiers, mais la taille totale du résultat devient plus petite (car aucun encodage Base64 des binaires n’est utilisé). De plus, cette méthode produit un HTML adapté à un large éventail de navigateurs. |

### Voir aussi

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


