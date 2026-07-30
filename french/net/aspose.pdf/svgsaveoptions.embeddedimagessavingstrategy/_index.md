---
title: "Délégué SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Pour une propriété de ce type, vous pouvez affecter un délégué créé à partir d’une méthode personnalisée qui implémente le traitement de l’enregistrement externe d’une image extraite du SVG généré à partir du PDF et qui doit être enregistrée comme ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement tel qu’un enregistrement autonome dans un flux ou sur le disque peut être effectué dans ce code personnalisé et ce code doit renvoyer un chemin ou toute autre chaîne sans guillemets qui sera ensuite incorporée dans le SVG généré à la place du chemin initial supposé vers cette ressource d’image. Dans ce cas, toutes les actions nécessaires à l’enregistrement de l’image doivent être réalisées dans le code de la méthode fournie, car l’enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement de ce fichier ou de celui‑ci doit, pour une raison quelconque, être effectué par le code du convertisseur lui‑même et non par le code personnalisé, veuillez définir dans le code personnalisé le drapeau CustomProcessingCancelled du paramètre imageSavingInfo. Il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s’il n’y avait aucun code personnalisé externe. représente les informations sur l’image enregistrée qui peuvent être utilisées dans le code personnalisé ; il doit renvoyer une chaîne qui représente l’URL de l’image qui sera insérée dans le SVG"
type: docs
weight: 10420
url: /fr/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

Pour une propriété de ce type, vous pouvez affecter un délégué créé à partir d’une méthode personnalisée qui implémente le traitement de l’enregistrement externe d’une image extraite du SVG généré à partir du PDF et qui doit être enregistrée comme ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement (comme un enregistrement autonome dans un flux ou sur le disque) peut être effectué dans ce code personnalisé et ce code doit renvoyer un chemin (ou toute autre chaîne sans guillemets) qui sera ensuite incorporé dans le SVG généré à la place du chemin initial supposé vers cette ressource d’image. Dans ce cas, toutes les actions nécessaires à l’enregistrement de l’image doivent être réalisées dans le code de la méthode fournie, car l’enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement de ce fichier ou de celui‑ci doit, pour une raison quelconque, être effectué par le code du convertisseur lui‑même, et non par le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' du paramètre 'imageSavingInfo'. Il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s’il n’y avait aucun code personnalisé externe. représente les informations sur l’image enregistrée qui peuvent être utilisées dans le code personnalisé ; il doit renvoyer une chaîne qui représente l’URL de l’image qui sera insérée dans le SVG

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Voir aussi

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


