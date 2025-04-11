---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.PdfFormatConversionOptions. Représente un ensemble d'options pour convertir un document PDF
type: docs
weight: 8380
url: /fr/net/aspose.pdf/pdfformatconversionoptions/
---
## Classe PdfFormatConversionOptions

Représente un ensemble d'options pour convertir un document PDF

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
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Ce drapeau contrôle l'alignement du texte dans le document converti. Par défaut, la conversion du document n'affecte pas l'alignement du texte et laisse le texte tel quel. Cependant, dans certains cas, la substitution de police peut provoquer des chevauchements ou des espaces supplémentaires dans le document converti. Lorsque ce drapeau est activé, des opérations d'alignement spéciales seront effectuées. Ce drapeau ne doit être activé que pour les documents présentant des problèmes de texte chevauché ou des espaces superflus, car son utilisation peut réduire les performances et, dans certains cas, corrompre le contenu textuel. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Action pour les images avec masque doux. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Action pour les objets qui ne peuvent pas être convertis |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Stratégie(s) pour exclure les polices superflues et réduire la taille du fichier du document. Ce paramètre n'a de sens que lorsque le drapeau [`OptimizeFileSize`](./optimizefilesize/) est activé. Par défaut, la combinaison des stratégies SubsetFonts et RemoveDuplicatedFonts est utilisée. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Options pour les cas où il n'est pas possible d'intégrer certaines polices dans le document PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Format PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Obtient ou définit le nom du fichier du profil ICC. En cas de valeur nulle, le profil ICC par défaut est utilisé. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Obtient ou définit l'exécution des flux d'images en mode asynchrone. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Indique si le mode de conversion à faible consommation de mémoire est activé |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Obtient ou définit si les données de Info doivent être transférées vers Metadata lors de la conversion en PDF 2.0. Vrai par défaut. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Chemin vers le fichier où les commentaires seront enregistrés. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Flux dans lequel les commentaires seront enregistrés. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Contient des indicateurs pour contrôler le processus de conversion PDF/A dans les cas où le document source ne correspond pas à la spécification PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Cette propriété est externe. Elle contient toutes les polices (noms des polices) qui n'ont pas été trouvées sur l'ordinateur lors de la dernière conversion PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Obtient ou définit un indicateur qui active ou désactive un mode de conversion spécial pour obtenir un document PDF/A de taille réduite. Actuellement, ce drapeau influence l'optimisation des polices utilisées dans le document PDF et, à l'avenir, il pourra également être utilisé pour activer l'optimisation d'autres structures de données, telles que les graphismes. L'activation de ce drapeau et de ce mode peut réduire considérablement la taille du fichier, mais peut également diminuer significativement les performances de conversion. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Obtient ou définit l'[`OutputIntent`](../outputintent/) pour la conversion au format PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Stratégie pour traiter les symboles de la zone d'utilisation privée Unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Stratégie pour copier les données d'encodage pour les polices symboliques si une police TrueType symbolique possède plus d'une sous-table d'encodage. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Action pour les objets masqués par image |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Règles pour résoudre les problèmes de correspondance Unicode. Peut être nul. |

## Champs

| Nom | Description |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Stratégie pour aligner le texte. Ce paramètre n'a de sens que lorsque le drapeau [`AlignText`](./aligntext/) est activé. |

### Voir Aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)