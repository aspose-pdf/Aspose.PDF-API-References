---
title: "HtmlSaveOptions.ExplicitListOfSavedPages"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "HtmlSaveOptions property. Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent être numérotées à partir de 1. C’est‑à‑dire que les numéros valides doivent provenir de la plage 1…NumberOfPagesInConvertedDocument. L’ordre d’apparition des pages dans cette liste n’affecte pas leur ordre dans les pages HTML résultantes ; les pages résultantes seront toujours dans l’ordre où elles apparaissent dans le PDF source. Si cette liste est nulle, comme c’est le cas par défaut, toutes les pages seront converties. Si un numéro de page de cette liste dépasse la plage des pages présentes (amountOfPagesInDocument), une exception sera levée."
type: docs
weight: 70
url: /fr/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent être numérotées à partir de 1. C’est‑à‑dire que les numéros valides de pages doivent être pris dans la plage (1...[NumberOfPagesInConvertedDocument]). L’ordre d’apparition des pages dans cette liste n’affecte pas leur ordre dans les pages HTML résultantes — dans les pages résultantes, elles seront toujours présentées dans l’ordre où elles figurent dans le PDF source. Si cette liste est null (comme c’est le cas par défaut), toutes les pages seront converties. Si un numéro de page de cette liste dépasse la plage des pages présentes (1-[amountOfPagesInDocument]), une exception sera levée.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Voir aussi

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


