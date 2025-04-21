---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Vous pouvez assigner à cette propriété une stratégie personnalisée qui implémente le traitement et/ou la sauvegarde d'une partie de CSS qui a été créée lors de la conversion de PDF en HTML. Dans ce cas, le traitement doit être effectué dans ce code personnalisé
type: docs
weight: 5590
url: /fr/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## Délégué HtmlSaveOptions.CssSavingStrategy

Vous pouvez assigner à cette propriété une stratégie personnalisée qui implémente le traitement et/ou la sauvegarde d'une partie de CSS qui a été créée lors de la conversion de PDF en HTML. Dans ce cas, le traitement (comme la sauvegarde dans un flux ou sur disque) doit être effectué dans ce code personnalisé

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | représente un ensemble de données qui peut être utilisé pour la sauvegarde de la partie CSS fournie |

### Voir aussi

* classe [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)