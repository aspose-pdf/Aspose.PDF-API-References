---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsPartsEmbeddingModes d'Aspose.Pdf. Cet enum énumère les modes possibles d'incorporation des fichiers référencés dans HTML. Il permet de contrôler si les fichiers référencés (HTML, Fonts, Images, CSS) seront intégrés dans le fichier HTML principal ou seront générés en tant qu'entités binaires séparées.
type: docs
weight: 5710
url: /fr/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## Énumération HtmlSaveOptions.PartsEmbeddingModes

Cet enum énumère les modes possibles d'incorporation des fichiers référencés dans HTML. Il permet de contrôler si les fichiers référencés (HTML, Fonts, Images, CSS) seront intégrés dans le fichier HTML principal ou seront générés en tant qu'entités binaires séparées.

```csharp
public enum PartsEmbeddingModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Force l'incorporation de tous les fichiers référencés (Css, Images, Fonts) dans le balisage HTML généré (c'est-à-dire dans le HTML lui-même). Cette approche génère un fichier HTML, mais la taille totale de la sortie devient plus grande (car l'encodage Base64 des binaires est utilisé) et tous les navigateurs (en particulier les anciens) ne traitent pas avec succès les binaires intégrés dans le HTML. Mais cela permet d'obtenir un HTML qui contient l'ensemble du résultat, sans fichiers supplémentaires. |
| EmbedCssOnly | `1` | Force à mettre à part tous les fichiers référencés sauf le CSS (Images et Fonts). C'est-à-dire que le CSS sera intégré dans le HTML résultant, et tous les autres fichiers référencés (Images et Fonts) seront traités comme des parties externes. Cela génère un HTML qui est adapté à un large éventail de navigateurs. |
| NoEmbedding | `2` | Force à mettre à part les fichiers référencés (Css, Images, Fonts). Cette approche génère un ensemble de fichiers, mais la taille totale de la sortie devient plus petite (car aucun encodage Base64 des binaires n'est utilisé). De plus, cette approche génère un HTML qui est adapté à un large éventail de navigateurs. |

### Voir aussi

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)