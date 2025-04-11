---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Pour cette propriété, vous pouvez assigner un délégué créé à partir d'une méthode personnalisée qui implémente le traitement de la ressource externe, police ou image, qui a été extraite du PDF et doit être enregistrée en tant que ressource externe lors de la conversion du PDF en HTML. Dans ce cas, le traitement tel que l'enregistrement dans un flux ou sur un disque peut être effectué dans ce code personnalisé et ce code personnalisé doit retourner un chemin ou toute autre chaîne sans guillemets qui sera ensuite incorporée dans le HTML généré au lieu du chemin supposé d'origine vers cette ressource image. Dans ce cas, toutes les actions nécessaires pour l'enregistrement de l'image doivent être entreprises dans le code de la méthode fournie car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement pour ce fichier ou cet autre fichier doit, pour une raison quelconque, être effectué par le code du convertisseur lui-même et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau CustomProcessingCancelled de la variable paramètres resourceSavingInfo. Cela signale au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme s'il n'y avait pas de code personnalisé externe.
type: docs
weight: 5730
url: /fr/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
| --- | --- |
| resourceSavingInfo | ResourceSavingInfo | représente un ensemble de données pour l'enregistrement de la ressource |

### Valeur de retour

doit retourner l'URL de la ressource enregistrée qui sera utilisée lors de la génération du HTML

### Voir aussi

* classe [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)