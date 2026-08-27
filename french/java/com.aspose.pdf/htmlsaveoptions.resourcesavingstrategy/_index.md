---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "À cette propriété, vous pouvez assigner un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une ressource externe (police ou image) extraite du PDF et devant être enregistrée."
type: docs
weight: 2150
url: /fr/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

À cette propriété, vous pouvez affecter un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une ressource externe (police ou image) extraite du PDF et qui doit être enregistrée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement (comme l'enregistrement dans un flux ou sur le disque) peut être effectué dans ce code personnalisé et ce code personnalisé doit renvoyer un chemin (ou toute autre chaîne sans guillemets) qui sera ensuite incorporé dans le HTML généré à la place du chemin original supposé vers cette ressource d'image. Dans ce cas, toutes les actions nécessaires à l'enregistrement de l'image doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement de ce fichier ou de celui‑ci, pour une raison quelconque, doit être effectué par le code du convertisseur lui‑même, et non par le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'resourceSavingInfo'. Il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur lui‑même comme s'il n'existait aucun code personnalisé externe.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Méthode invoquée |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Méthode invoquée
