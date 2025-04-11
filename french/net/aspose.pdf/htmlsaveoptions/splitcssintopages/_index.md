---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: Propriété HtmlSaveOptions. Lorsque le mode multipage est sélectionné, c'est-à-dire que SplitIntoPages est vrai, cet attribut définit s'il faut créer un fichier CSS séparé pour chaque page HTML résultante. Par défaut, cet attribut est faux, donc un grand CSS commun sera créé pour toutes les pages créées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement beaucoup plus grande que la taille d'un grand fichier CSS, car dans le premier cas, les classes CSS sont des doublons dans plusieurs fichiers CSS pour chaque page. Donc, ce paramètre est à utiliser uniquement lorsque vous êtes intéressé par le traitement futur de chaque page HTML indépendamment, et par conséquent, la taille du CSS de chaque page prise séparément est le problème le plus critique.
type: docs
weight: 190
url: /fr/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## Propriété HtmlSaveOptions.SplitCssIntoPages

Lorsque le mode multipage est sélectionné (c'est-à-dire que 'SplitIntoPages' est 'true'), cet attribut définit s'il faut créer un fichier CSS séparé pour chaque page HTML résultante. Par défaut, cet attribut est faux, donc un grand CSS commun sera créé pour toutes les pages créées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement beaucoup plus grande que la taille d'un grand fichier CSS, car dans le premier cas, les classes CSS sont des doublons dans plusieurs fichiers CSS pour chaque page. Donc, ce paramètre est à utiliser uniquement lorsque vous êtes intéressé par le traitement futur de chaque page HTML indépendamment, et par conséquent, la taille du CSS de chaque page prise séparément est le problème le plus critique.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Voir aussi

* classe [HtmlSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)