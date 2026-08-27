---
title: "Déléguer HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Le résultat de la conversion peut contenir une ou plusieurs pages HTML qui peuvent également référencer des fichiers externes tels que des images ou des polices. Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de la page HTML obtenue elle‑même, créée pendant la conversion. Dans ce cas, le traitement comme l'enregistrement dans un flux ou sur disque peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour enregistrer le balisage des pages HTML doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement de ce cas ou de celui‑ci doit être effectué par le code du convertisseur lui‑même et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau CustomProcessingCancelled du paramètre htmlSavingInfo ; il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur de la même façon que s'il n’y avait aucun code d’enregistrement externe personnalisé."
type: docs
weight: 5810
url: /fr/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

Le résultat de la conversion peut contenir une ou plusieurs pages HTML (qui peuvent également référencer des fichiers externes comme des images ou des polices). Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de la page HTML obtenue (HTML elle‑même) créée pendant la conversion. Dans ce cas, le traitement (comme l'enregistrement dans un flux ou sur disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour enregistrer le balisage de la page HTML doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement de ce cas ou de celui‑ci doit être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' du paramètre 'htmlSavingInfo' : il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur de la même façon que s'il n’y avait aucun code d’enregistrement externe personnalisé.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | représente des données pouvant être utilisées pour l'enregistrement ou le traitement de la page HTML fournie |

### Voir aussi

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


