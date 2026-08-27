---
title: "Délégué HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "À cette propriété vous pouvez affecter un délégué créé à partir d’une méthode personnalisée qui implémente le traitement d’une ressource externe (police ou image) extraite du PDF et devant être enregistrée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement tel que l’enregistrement dans un flux ou sur le disque peut être effectué dans ce code personnalisé et ce code doit renvoyer un chemin ou toute autre chaîne sans guillemets qui sera ensuite incorporée dans le HTML généré à la place du chemin d’origine supposé de cette ressource d’image. Dans ce cas, toutes les actions nécessaires à l’enregistrement de l’image doivent être réalisées dans le code de la méthode fournie, car l’enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement de ce fichier ou de celui‑ci, pour une raison quelconque, doit être effectué par le code du convertisseur lui‑même et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau CustomProcessingCancelled du paramètre resourceSavingInfo. Il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s’il n’y avait aucun code personnalisé externe."
type: docs
weight: 5860
url: /fr/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

À cette propriété vous pouvez affecter un délégué créé à partir d’une méthode personnalisée qui implémente le traitement d’une ressource externe (police ou image) extraite du PDF et devant être enregistrée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement (comme l’enregistrement dans un flux ou sur le disque) peut être effectué dans ce code personnalisé et ce code doit renvoyer un chemin (ou toute autre chaîne sans guillemets) qui sera ensuite incorporé dans le HTML généré à la place du chemin d’origine supposé de cette ressource d’image. Dans ce cas, toutes les actions nécessaires à l’enregistrement de l’image doivent être réalisées dans le code de la méthode fournie, car l’enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement de ce fichier ou de celui‑ci, pour une raison quelconque, doit être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' du paramètre 'resourceSavingInfo'. Il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s’il n’y avait aucun code personnalisé externe.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | représente un ensemble de données pour l’enregistrement de la ressource |

### Valeur de retour

doit renvoyer l’URL de la ressource enregistrée qui sera utilisée lors de la génération du HTML

### Voir aussi

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


