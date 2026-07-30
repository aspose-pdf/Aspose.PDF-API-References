---
title: "HtmlSaveOptions.SplitCssIntoPages"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "HtmlSaveOptions property. Lorsque le mode multi‑pages est sélectionné, c’est‑à‑dire que SplitIntoPages est vrai, cet attribut définit s’il faut créer un fichier CSS séparé pour chaque page HTML résultante. Par défaut, cet attribut est faux, donc un seul CSS commun volumineux est créé pour toutes les pages générées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement bien supérieure à celle d’un seul gros fichier CSS, car dans le premier cas les classes CSS sont dupliquées dans plusieurs fichiers CSS pour chaque page. Ainsi, ce paramètre ne doit être utilisé que lorsque vous avez besoin de traiter chaque page HTML indépendamment et que la taille du CSS de chaque page séparée est un critère critique."
type: docs
weight: 190
url: /fr/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages property

Lorsque le mode multipage est sélectionné (c’est‑à‑dire que 'SplitIntoPages' est true), cet attribut définit s’il faut créer un fichier CSS séparé pour chaque page HTML résultante. Par défaut, cet attribut est false, donc un seul grand CSS commun est créé pour toutes les pages générées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement bien supérieure à celle d’un seul grand fichier CSS, car dans le premier cas les classes CSS sont dupliquées dans plusieurs fichiers CSS pour chaque page. Ainsi, ce réglage ne doit être utilisé que si vous avez besoin de traiter chaque page HTML indépendamment, et que la taille du CSS de chaque page séparée est le critère le plus critique.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Voir aussi

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


