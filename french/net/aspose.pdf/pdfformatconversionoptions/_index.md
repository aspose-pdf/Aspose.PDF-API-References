---
title: "Classe PdfFormatConversionOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.PdfFormatConversionOptions. représente un ensemble d'options pour convertir un document PDF"
type: docs
weight: 8520
url: /fr/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

représente un ensemble d'options pour convertir un document PDF

```csharp
public class PdfFormatConversionOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Constructeur |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Obtient l'objet PdfFormatConversionOptions avec les paramètres par défaut |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Ce drapeau contrôle l'alignement du texte dans le document converti. Par défaut, la conversion du document n'affecte pas l'alignement du texte et le laisse tel quel. Mais dans certains cas, la substitution de police entraîne un chevauchement du texte ou des espaces supplémentaires dans le document converti. Lorsque ce drapeau est activé, des opérations d'alignement spéciales seront effectuées. Ce drapeau ne doit être défini que pour les documents qui ont des problèmes de texte chevauché ou d'espaces supplémentaires, car l'utilisation de ce drapeau diminue les performances et peut, dans certains cas, corrompre le contenu du texte. |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | Obtient ou définit les paramètres pour le balisage automatique lors de la conversion au format PDF. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Action pour les images avec masque souple. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Action pour les objets qui ne peuvent pas être convertis |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Stratégie(s) pour exclure les polices superflues et réduire la taille du fichier du document. Ce paramètre n'a de sens que lorsque le drapeau [`OptimizeFileSize`](./optimizefilesize/) est défini sur true. Par défaut, la combinaison des stratégies SubsetFonts et RemoveDuplicatedFonts est utilisée. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Options pour les cas où il n'est pas possible d'incorporer certaines polices dans le document PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Format PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Obtient ou définit le nom de fichier du profil icc. En cas de null, le profil icc par défaut est utilisé. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Obtient/définit l'exécution des flux d'images en mode asynchrone. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Le mode de conversion à faible mémoire est-il activé |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Obtient ou définit s'il faut transférer les données de Info vers Metadata lors de la conversion en PDF 2.0. True par défaut. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Chemin du fichier où les commentaires seront stockés. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Flux où les commentaires seront stockés. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Contient des drapeaux pour contrôler le processus de conversion PDF/A dans les cas où le document source ne correspond pas à la spécification PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Cette propriété est une propriété de sortie. Elle contient toutes les polices (noms de polices) qui n'ont pas été trouvées sur l'ordinateur lors de la dernière conversion PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Obtient ou définit un drapeau qui active/désactive le mode de conversion spécial pour obtenir un document PDF/A avec une taille de fichier réduite. Actuellement, ce drapeau influence l'optimisation des polices utilisées dans le document PDF, et éventuellement, à l'avenir, ce drapeau sera également utilisé pour activer l'optimisation d'autres structures de données, telles que les graphiques. L'ensemble de ce drapeau et du mode pourrait réduire considérablement la taille du fichier, mais en même temps, il pourrait diminuer significativement les performances de la conversion. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Obtient ou définit le [`OutputIntent`](../outputintent/) pour la conversion au format PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Stratégie pour traiter les symboles de la zone d'utilisation privée Unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Stratégie pour copier les données d'encodage des polices symboliques si la police TrueType symbolique possède plus d'une sous-table d'encodage. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Action pour les objets masqués d'image |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Règles pour résoudre les problèmes de mappage Unicode. Peut être nul. |

## Champs

| Nom | Description |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Stratégie pour aligner le texte. Ce paramètre n'a de sens que lorsque le drapeau [`AlignText`](./aligntext/) est défini sur true. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


