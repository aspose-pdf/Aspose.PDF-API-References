---
title: SvgSaveOptions
second_title: Référence de l'API Aspose.PDF pour .NET
description: Enregistrer les options dexportation au format SVG
type: docs
weight: 6450
url: /fr/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

Enregistrer les options d'exportation au format SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Obtient ou définit une valeur booléenne qui indique que l'objet de réponse sera fermé après l'enregistrement du document dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Cet attribut a activé la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Format de sauvegarde des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l'élément d'énumération ReturnAction en spécifiant Continuer ou Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde se poursuit, mais l'utilisateur peut également renvoyer Abort, auquel cas l'opération de sauvegarde doit cesser. |

## Des champs

| Nom | La description |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive) | Spécifie si la sortie sera créée sous la forme d'une archive zip. Veuillez vous référer au commentaire des options 'TreatTargetFileNameAsDirectory' pour voir les règles de dénomination des fichiers svg des pages pour le document source multipage, qui sont également appliquées à l'ensemble compressé des fichiers de sortie. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving) | Ce champ peut contenir une stratégie de sauvegarde qui doit être utilisée (si elle est présente) lors de la conversion pour une gestion personnalisée des images externes référencées créées fichiers (tels que BMP ou JPEG intégrés) intégrés dans le SVG enregistré. Cette stratégie doit traiter les ressources et renvoyer la chaîne qui représente l'URI souhaitable de la ressource enregistrée dans le SVG généré. Si le traitement de tel ou tel fichier pour une raison quelconque doit être effectué par le code du convertisseur lui-même, pas dans le code personnalisé, veuillez définir dans le code personnalisé l'indicateur 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo' Il signale au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme s'il n'y avait aucun code personnalisé externe . |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels) | Spécifie s'il faut redimensionner le document de sortie des points typographiques aux pixels. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory) | Cette option définit si le répertoire cible sera créé (s'il est encore absent) avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie demandé lui-même. Ainsi, ce répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci-dessous) . Si non, les fichiers de sortie des pages autres que la première seront créés exactement dans le répertoire demandé en tant que fichier de sortie principal, mais contiendront dans le suffixe de nom de fichier _[2...n], que est défini par le numéro de page, fe si Vous définissez le fichier de sortie "C:\AsposeTests\output.svg" et la sortie contiendra plusieurs fichiers svg de pages, puis les fichiers de pages seront également créés dans le répertoire "C:\AsposeTests\" et auront des noms "sortie". svg', 'sortie_2.svg', 'sortie_3.svg' etc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Parfois, les fichiers PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière-plan en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus de formats cibles (par exemple MsWord pour le format DOCS) génèrent parfois des limites visibles entre les parties des images d'arrière-plan , car leurs techniques de lissage des bords de l'image (anti-crénelage) sont différentes d'Acrobat Reader. S'il semble que le document exporté contient de telles limites visibles entre parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de de cela effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement essentiellement la conversion, donc, s'il vous plaît, n'utilisez cette option que lorsque c'est vraiment nécessaire. |

### Voir également

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
