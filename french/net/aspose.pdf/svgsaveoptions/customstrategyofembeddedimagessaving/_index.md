---
title: "SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Champ SvgSaveOptions. Ce champ peut contenir une stratégie d’enregistrement qui doit être utilisée, si elle est présente, pendant la conversion pour la gestion personnalisée des fichiers d’images externes référencés créés, comme les BMP ou JPEG incorporés dans le SVG enregistré. Cette stratégie doit traiter les ressources et renvoyer une chaîne qui représente l’URI souhaitée de la ressource enregistrée dans le SVG généré. Si le traitement de ce fichier ou de celui‑ci doit, pour une raison quelconque, être effectué par le code du convertisseur lui‑même et non par du code personnalisé, veuillez définir dans le code personnalisé le drapeau CustomProcessingCancelled du paramètre imageSavingInfo. Il indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être réalisées par le convertisseur comme s’il n’y avait aucun code personnalisé externe."
type: docs
weight: 30
url: /fr/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) pendant la conversion pour la gestion personnalisée des fichiers d'images externes référencés créés (comme les BMP ou JPEG incorporés) incorporés dans le SVG enregistré. Cette stratégie doit traiter les ressources et renvoyer une chaîne représentant l'URI souhaitée de la ressource enregistrée dans le SVG généré. Si le traitement de ce fichier ou de celui‑ci doit, pour une raison quelconque, être effectué par le code du convertisseur lui‑même, et non dans du code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s'il n’y avait aucun code personnalisé externe.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Voir aussi

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


