---
title: Class MobiXmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.MobiXmlSaveOptions. Options d'enregistrement pour l'exportation au format Xml
type: docs
weight: 6980
url: /fr/net/aspose.pdf/mobixmlsaveoptions/
---
## Classe MobiXmlSaveOptions

Options d'enregistrement pour l'exportation au format Xml

```csharp
public class MobiXmlSaveOptions : UnifiedSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MobiXmlSaveOptions](mobixmlsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion de PDF vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'objet Response sera fermé après que le document a été enregistré dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde se poursuit, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de sauvegarde doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traite les pages dans plusieurs threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDF contiennent des images de fond (de pages ou de cellules de tableau) construites à partir de plusieurs mêmes images de fond en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par exemple, MsWord pour le format DOCS) génèrent parfois des limites visibles entre les parties des images de fond, car leurs techniques de lissage des bords d'image (anti-aliasing) sont différentes de celles d'Acrobat Reader. Si le document exporté semble contenir de telles limites visibles entre les parties des mêmes images de fond, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez utiliser cette option uniquement lorsque cela est vraiment nécessaire. |

### Voir aussi

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)