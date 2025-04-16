---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Champ HtmlSaveOptions. Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez assigner à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une page HTML qui a été créée lors de la conversion. Dans ce cas, le traitement peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour la sauvegarde de la page HTML doivent être entreprises dans le code de la méthode fournie, car la sauvegarde du résultat dans le code du convertisseur ne sera pas utilisée. Si le traitement pour ce cas ou cet autre doit pour une raison quelconque être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable de paramètre 'htmlSavingInfo' : cela signalera au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même de la même manière que s'il n'y avait pas de code personnalisé externe pour le traitement.
type: docs
weight: 270
url: /fr/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## Champ HtmlSaveOptions.CustomHtmlSavingStrategy

Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez assigner à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une page HTML (pour être précisément - markup-HTML, sans fichiers liés externes le cas échéant) qui a été créée lors de la conversion. Dans ce cas, le traitement (comme la sauvegarde de la page HTML dans un flux ou sur disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour la sauvegarde de la page HTML doivent être entreprises dans le code de la méthode fournie, car la sauvegarde du résultat dans le code du convertisseur ne sera pas utilisée. Si le traitement pour ce cas ou cet autre doit pour une raison quelconque être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable de paramètre 'htmlSavingInfo' : cela signalera au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même de la même manière que s'il n'y avait pas de code personnalisé externe pour le traitement.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Voir aussi

* délégué [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* classe [HtmlSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)