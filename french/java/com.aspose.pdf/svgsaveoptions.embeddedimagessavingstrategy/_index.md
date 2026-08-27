---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "À la propriété de ce type, vous pouvez assigner un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de l'enregistrement externe de l'image qui a été extraite du SVG créé à partir du PDF."
type: docs
weight: 4730
url: /fr/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

À la propriété de ce type, vous pouvez affecter un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de l'enregistrement externe d'une image extraite d'un SVG généré à partir d'un PDF et qui doit être sauvegardée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement (comme un enregistrement fait maison dans un flux ou sur disque) peut être effectué dans ce code personnalisé et ce code doit renvoyer un chemin (ou toute autre chaîne sans guillemets) qui sera ensuite intégré dans le SVG généré à la place du chemin original supposé de la ressource image. Dans ce cas, toutes les actions nécessaires à l'enregistrement de l'image doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement de ce fichier ou de celui‑ci doit, pour une raison quelconque, être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s'il n'existait aucun code personnalisé externe.

## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
