---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Pour une propriété de ce type, vous pouvez assigner un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de l'enregistrement externe de l'image extraite du SVG créé à partir du PDF et qui doit être enregistrée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement (comme l'enregistrement fait maison dans un flux ou sur disque) peut être effectué dans ce code personnalisé et ce code personnalisé doit retourner un chemin (ou toute autre chaîne sans guillemets) qui sera ensuite incorporé dans le SVG généré au lieu du chemin supposé original vers cette ressource image. Dans ce cas, toutes les actions nécessaires pour l'enregistrement de l'image doivent être entreprises dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement pour ce fichier ou cet autre fichier doit, pour une raison quelconque, être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela signale au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme s'il n'y avait pas de code personnalisé externe. représente des informations sur l'image enregistrée qui peuvent être utilisées dans le code personnalisé doit retourner une chaîne qui représente l'URL de l'image qui sera mise dans le SVG
type: docs
weight: 10240
url: /fr/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## Délégué SvgSaveOptions.EmbeddedImagesSavingStrategy

Pour une propriété de ce type, vous pouvez assigner un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de l'enregistrement externe de l'image extraite du SVG créé à partir du PDF et qui doit être enregistrée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement (comme l'enregistrement fait maison dans un flux ou sur disque) peut être effectué dans ce code personnalisé et ce code personnalisé doit retourner un chemin (ou toute autre chaîne sans guillemets) qui sera ensuite incorporé dans le SVG généré au lieu du chemin supposé original vers cette ressource image. Dans ce cas, toutes les actions nécessaires pour l'enregistrement de l'image doivent être entreprises dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement pour ce fichier ou cet autre fichier doit, pour une raison quelconque, être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela signale au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme s'il n'y avait pas de code personnalisé externe. représente des informations sur l'image enregistrée qui peuvent être utilisées dans le code personnalisé doit retourner une chaîne qui représente l'URL de l'image qui sera mise dans le SVG

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Voir aussi

* classe [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* classe [SvgSaveOptions](../svgsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)