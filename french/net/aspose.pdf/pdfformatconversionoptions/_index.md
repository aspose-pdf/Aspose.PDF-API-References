---
title: PdfFormatConversionOptions
second_title: Référence de l'API Aspose.PDF pour .NET
description: représente un ensemble doptions pour convertir le document PDF
type: docs
weight: 6030
url: /fr/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

représente un ensemble d'options pour convertir le document PDF

```csharp
public class PdfFormatConversionOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor)(PdfFormat) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_1)(PdfFormat, ConvertErrorAction) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_3)(string, PdfFormat) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_4)(string, PdfFormat, ConvertErrorAction) | Constructeur |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Constructeur |

## Propriétés

| Nom | La description |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default) { get; } | Obtient l'objet PdfFormatConversionOptions avec les paramètres par défaut |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext) { get; set; } | Cet indicateur contrôle l'alignement du texte dans le document converti. Par défaut, la conversion de document n'affecte pas l'alignement du texte et laisse le texte tel quel. Mais dans certains cas, la substitution de police provoque un chevauchement de texte ou des espaces supplémentaires dans le document converti. Lorsque cet indicateur est défini , des opérations d'alignement spéciales seront effectuées. Cet indicateur doit être défini uniquement pour les documents qui ont des problèmes de chevauchement de texte ou d'espaces de texte supplémentaires qui entraînent l'utilisation de cet indicateur diminuant les performances et, dans certains cas, pourraient corrompre le contenu du texte. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction) { get; set; } | Action pour les images avec masque mou. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction) { get; set; } | Action pour les objets qui ne peuvent pas être convertis |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy) { get; set; } | Stratégie(s) pour exclure les polices superflues et réduire la taille du fichier du document. Ce paramètre n'a de sens que lorsque le drapeau[`OptimizeFileSize`](./optimizefilesize) est défini sur true. Par combinaison de stratégies par défautSubsetFonts et RemoveDuplicatedFonts est utilisé. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions) { get; } | Options pour les cas où il n'est pas possible d'intégrer certaines polices dans un document PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format) { get; set; } | Format PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename) { get; set; } | Obtient ou définit le nom de fichier du nom de profil ICC. En cas de null, le profil ICC par défaut utilisé. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode) { get; set; } | Obtient/définit la série de flux d'images en mode asynchrone. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode) { get; set; } | Le mode de conversion de mémoire faible est-il activé |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo) { get; set; } | Obtient ou définit s'il faut transmettre les données d'Info aux métadonnées lors de la conversion au format PDF 2.0. Vrai par défaut. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename) { get; set; } | Chemin d'accès au fichier où les commentaires seront stockés. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream) { get; set; } | Flux où les commentaires seront stockés. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases) { get; } | Contient des indicateurs pour contrôler le processus de conversion PDF/A dans les cas où le document source ne correspond pas à la spécification PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts) { get; } | Cette propriété est hors propriété. Il contient toutes les polices (noms de police) qui n'ont pas été trouvées sur l'ordinateur lors de la dernière conversion PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize) { get; set; } | Obtient ou définit un indicateur qui active/désactive le mode de conversion spécial pour obtenir un document PDF/A avec une taille de fichier réduite. Maintenant, cet indicateur a un impact sur l'optimisation des polices utilisées dans le document PDF, éventuellement, à l'avenir, cet indicateur sera également utilisé pour activer l'optimisation pour d'autres structures de données, telles que les graphiques. L'ensemble de cet indicateur et de ce mode pourrait réduire considérablement la taille du fichier, mais en même temps, il pourrait réduire considérablement les performances de conversion. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy) { get; set; } | Stratégie pour traiter les symboles de la zone d'utilisation privée (PUA) Unicode. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy) { get; set; } | Stratégie pour copier les données d'encodage pour les polices symboliques si la police symbolique TrueType a plus d'une sous-table d'encodage. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction) { get; set; } | Action pour les objets masqués image |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules) { get; set; } | Règles pour résoudre les problèmes de mappage Unicode. Peut être null. |

## Des champs

| Nom | La description |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy) | Stratégie pour aligner le texte. Ce paramètre n'a de sens que lorsque flag[`AlignText`](./aligntext) est défini sur true. |

### Voir également

* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
