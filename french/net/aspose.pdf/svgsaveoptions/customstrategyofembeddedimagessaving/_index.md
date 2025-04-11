---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: Champ SvgSaveOptions. Ce champ peut contenir la stratégie de sauvegarde qui doit être utilisée si elle est présente lors de la conversion pour un traitement personnalisé des fichiers d'images externes référencés créés, comme les BMP intégrés ou les JPEG intégrés dans le SVG enregistré. Cette stratégie doit traiter les ressources et retourner une chaîne qui représente l'URI souhaitée de la ressource sauvegardée dans le SVG généré. Si le traitement de ce fichier ou d'un autre doit, pour une raison quelconque, être effectué par le code du convertisseur lui-même et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable des paramètres 'imageSavingInfo'. Cela signale au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme s'il n'y avait pas de code personnalisé externe.
type: docs
weight: 30
url: /fr/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## Champ SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving

Ce champ peut contenir la stratégie de sauvegarde qui doit être utilisée (si présente) lors de la conversion pour un traitement personnalisé des fichiers d'images externes référencés créés (comme les BMP intégrés ou les JPEG) intégrés dans le SVG enregistré. Cette stratégie doit traiter les ressources et retourner une chaîne qui représente l'URI souhaitée de la ressource sauvegardée dans le SVG généré. Si le traitement de ce fichier ou d'un autre doit, pour une raison quelconque, être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable des paramètres 'imageSavingInfo'. Cela signale au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme s'il n'y avait pas de code personnalisé externe.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Voir aussi

* délégué [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* classe [SvgSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)