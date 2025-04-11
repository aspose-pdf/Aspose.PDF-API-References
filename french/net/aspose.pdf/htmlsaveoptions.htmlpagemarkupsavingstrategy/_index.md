---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Le résultat de la conversion peut contenir une ou plusieurs pages HTML qui peuvent également référencer des fichiers externes comme des images ou des polices. Vous pouvez assigner à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de la page HTML obtenue (HTML lui-même) qui a été créée lors de la conversion. Dans ce cas, le traitement (comme l'enregistrement dans un flux ou sur disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour l'enregistrement du balisage des pages HTML doivent être entreprises dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement pour ce cas ou cet autre doit, pour une raison quelconque, être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'htmlSavingInfo' : cela signale au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même de la même manière que s'il n'y avait pas de code d'enregistrement personnalisé externe.
type: docs
weight: 5680
url: /fr/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## Délégué HtmlSaveOptions.HtmlPageMarkupSavingStrategy

Le résultat de la conversion peut contenir une ou plusieurs pages HTML (qui peuvent également référencer des fichiers externes comme des images ou des polices). Vous pouvez assigner à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de la page HTML obtenue (HTML lui-même) qui a été créée lors de la conversion. Dans ce cas, le traitement (comme l'enregistrement dans un flux ou sur disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour l'enregistrement du balisage de la page HTML doivent être entreprises dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement pour ce cas ou cet autre doit, pour une raison quelconque, être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'htmlSavingInfo' : cela signale au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même de la même manière que s'il n'y avait pas de code d'enregistrement personnalisé externe.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | représente des données qui peuvent être utilisées pour l'enregistrement ou le traitement de la page HTML fournie |

### Voir aussi

* classe [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)