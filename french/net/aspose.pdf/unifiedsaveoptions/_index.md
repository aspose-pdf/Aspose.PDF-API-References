---
title: Class UnifiedSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.UnifiedSaveOptions. Cette classe représente les options de sauvegarde pour la sauvegarde qui utilise une méthode de conversion unifiée avec un modèle de document interne unifié.
type: docs
weight: 11140
url: /fr/net/aspose.pdf/unifiedsaveoptions/
---
## Classe UnifiedSaveOptions

Cette classe représente les options de sauvegarde pour la sauvegarde qui utilise une méthode de conversion unifiée (avec un modèle de document interne unifié).

```csharp
public class UnifiedSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [UnifiedSaveOptions](unifiedsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion de PDF vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de sauvegarde doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traite les pages dans plusieurs threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDF contiennent des images de fond (de pages ou de cellules de tableau) construites à partir de plusieurs mêmes images de fond en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par exemple, MsWord pour le format DOCS) génèrent parfois des limites visibles entre les parties des images de fond, car leurs techniques de lissage des bords d'image (anti-aliasing) sont différentes de celles d'Acrobat Reader. Si le document exporté contient de telles limites visibles entre les parties des mêmes images de fond, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez utiliser cette option uniquement lorsque cela est vraiment nécessaire. |

### Voir aussi

* classe [SaveOptions](../saveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)