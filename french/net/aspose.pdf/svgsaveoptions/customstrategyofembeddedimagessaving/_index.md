---
title: CustomStrategyOfEmbeddedImagesSaving
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ce champ peut contenir une stratégie de sauvegarde qui doit être utilisée si elle est présente lors de la conversion pour une gestion personnalisée des images externes référencées créées fichiers tels que BMP ou JPEG intégrés intégrés dans le SVG enregistré. Cette stratégie doit traiter les ressources et renvoyer la chaîne qui représente lURI souhaitable de la ressource enregistrée dans le SVG généré. Si le traitement de tel ou tel fichier pour une raison quelconque doit être effectué par le code du convertisseur lui-même pas dans le code personnalisé veuillez définir dans le code personnalisé lindicateur CustomProcessingCancelled de la variable du paramètre imageSavingInfo Il signale au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme sil ny avait aucun code personnalisé externe .
type: docs
weight: 30
url: /fr/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

Ce champ peut contenir une stratégie de sauvegarde qui doit être utilisée (si elle est présente) lors de la conversion pour une gestion personnalisée des images externes référencées créées fichiers (tels que BMP ou JPEG intégrés) intégrés dans le SVG enregistré. Cette stratégie doit traiter les ressources et renvoyer la chaîne qui représente l'URI souhaitable de la ressource enregistrée dans le SVG généré. Si le traitement de tel ou tel fichier pour une raison quelconque doit être effectué par le code du convertisseur lui-même, pas dans le code personnalisé, veuillez définir dans le code personnalisé l'indicateur 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo' Il signale au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme s'il n'y avait aucun code personnalisé externe .

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Voir également

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy)
* class [SvgSaveOptions](../../svgsaveoptions)
* espace de noms [Aspose.Pdf](../../svgsaveoptions)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->