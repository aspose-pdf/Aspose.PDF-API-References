---
title: "Délégué HtmlSaveOptions.CssSavingStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Vous pouvez affecter à cette propriété une stratégie personnalisée qui implémente le traitement et/ou l'enregistrement d'une partie CSS créée lors de la conversion de PDF en HTML. Dans ce cas, le traitement tel que l'enregistrement vers un flux ou le disque doit être effectué dans ce code personnalisé."
type: docs
weight: 5720
url: /fr/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

Vous pouvez affecter à cette propriété une stratégie personnalisée qui implémente le traitement et/ou l'enregistrement d'une partie CSS créée lors de la conversion de PDF en HTML. Dans ce cas, le traitement (comme l'enregistrement vers un flux ou le disque) doit être effectué dans ce code personnalisé.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | représente un ensemble de données pouvant être utilisées pour l'enregistrement de la partie CSS fournie |

### Voir aussi

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


