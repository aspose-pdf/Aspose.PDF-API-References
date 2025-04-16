---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: Propriété HtmlSaveOptions. Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent avoir des numéros basés sur 1. C'est-à-dire que les numéros de pages valides doivent être pris dans la plage 1...NumberOfPagesInConvertedDocument. L'ordre d'apparition des pages dans cette liste n'affecte pas leur ordre dans les pages HTML résultantes - dans les pages résultantes, elles apparaîtront toujours dans l'ordre dans lequel elles sont présentes dans le PDF source. Si cette liste est nulle, toutes les pages seront converties. Si un numéro de page de cette liste sort de la plage des pages présentes, une exception sera levée.
type: docs
weight: 70
url: /fr/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## Propriété HtmlSaveOptions.ExplicitListOfSavedPages

Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent avoir des numéros basés sur 1. C'est-à-dire que les numéros de pages valides doivent être pris dans la plage (1...[NumberOfPagesInConvertedDocument]). L'ordre d'apparition des pages dans cette liste n'affecte pas leur ordre dans la ou les pages HTML résultantes - dans les pages résultantes, elles apparaîtront toujours dans l'ordre dans lequel elles sont présentes dans le PDF source. Si cette liste est nulle (comme c'est le cas par défaut), toutes les pages seront converties. Si un numéro de page de cette liste sort de la plage des pages présentes (1-[amountOfPagesInDocument]), une exception sera levée.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Voir aussi

* classe [HtmlSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)