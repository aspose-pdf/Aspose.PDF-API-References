---
title: "HtmlSaveOptions.CustomHtmlSavingStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Champ HtmlSaveOptions. Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez affecter à cette propriété un délégué créé à partir d’une méthode personnalisée qui implémente le traitement d’une page HTML à marquer précisément en HTML sans fichiers liés externes, le cas échéant, créés pendant la conversion. Dans ce cas, des opérations telles que l’enregistrement des pages HTML dans un flux ou sur le disque peuvent être effectuées dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires à l’enregistrement de la page HTML doivent être réalisées dans le code de la méthode fournie, car l’enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement doit être effectué par le code du convertisseur lui‑même et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau CustomProcessingCancelled du paramètre htmlSavingInfo ; cela signalera au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur, comme si aucun code personnalisé externe n’existait pour le traitement."
type: docs
weight: 270
url: /fr/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez affecter à cette propriété un délégué créé à partir d’une méthode personnalisée qui implémente le traitement d’une page HTML (précisément : le balisage HTML, sans fichiers liés externes le cas échéant) générée pendant la conversion. Dans ce cas, le traitement (comme l’enregistrement du HTML de la page dans un flux ou sur le disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires à l’enregistrement de la page HTML doivent être réalisées dans le code de la méthode fournie, car l’enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement doit être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'htmlSavingInfo' : il signalera au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur lui‑même, de la même façon que s’il n’y avait aucun code personnalisé externe pour le traitement.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Voir aussi

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


