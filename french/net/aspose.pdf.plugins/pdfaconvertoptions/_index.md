---
title: "Classe PdfAConvertOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.PdfAConvertOptions. Représente les options pour convertir des documents PDF au format PDF/A avec le plugin PdfAConverter"
type: docs
weight: 9140
url: /fr/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions class

Représente les options pour convertir des documents PDF au format PDF/A avec le plugin [`PdfAConverter`](../pdfaconverter/).

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Obtient ou définit une valeur indiquant si des moyens supplémentaires sont nécessaires pour préserver l'alignement du texte pendant le processus de conversion PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Obtient ou définit l'action à entreprendre pour les objets qui ne peuvent pas être convertis. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Obtient ou définit la stratégie de suppression des polices afin de réduire la taille du fichier de sortie pendant le processus de conversion PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Obtient les options pour traiter les polices qui ne peuvent pas être incorporées dans le document. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Obtient ou définit le nom de fichier du profil ICC (International Color Consortium) à utiliser pour la conversion PDF/A à la place de celui par défaut. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Obtient la collection de sources de données |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Obtient ou définit une valeur indiquant si le mode basse mémoire est activé pendant le processus de conversion PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Obtient ou définit la source de données pour la sortie du journal. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Obtient les indicateurs qui contrôlent la conversion PDF/A dans les cas où le document PDF source ne correspond pas à la spécification PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut tenter de réduire la taille du fichier pendant le processus de conversion PDF/A. |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | Obtient la collection des cibles ajoutées (sources de données fichier ou flux) pour les résultats de l'opération d'enregistrement. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Obtient ou définit la version de la norme PDF/A à utiliser pour la validation ou la conversion. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Obtient ou définit la stratégie de traitement des symboles de la zone d'utilisation privée (PUA) dans le document PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Obtient ou définit l'action à entreprendre lors de la conversion des images avec des masques souples. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Obtient ou définit la stratégie d'encodage des polices symboliques lors de la conversion au format PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Obtient ou définit les règles de traitement des tables ToUnicode CMap et non liées aux symboles Unicode pendant le processus de conversion PDF/A. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | Ajoute une nouvelle cible d'enregistrement de résultat. |

### Voir aussi

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


