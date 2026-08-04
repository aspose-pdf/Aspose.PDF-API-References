---
title: "PdfFormatConversionOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "représente un ensemble d'options pour convertir un document PDF"
type: docs
weight: 1220
url: /fr/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

représente un ensemble d'options pour convertir un document PDF

Le type PdfFormatConversionOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | Initialise une nouvelle instance de la classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | Initialise une nouvelle instance de la classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | Initialise une nouvelle instance de la classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | Initialise une nouvelle instance de la classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | Initialise une nouvelle instance de la classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | Initialise une nouvelle instance de la classe PdfFormatConversionOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| is_async_image_streams_conversion_mode | Obtient/definit l'exécution des flux d'images en mode asynchrone. |
| is_low_memory_mode | Le mode de conversion à faible mémoire est activé |
| format | Format PDF. |
| log_file_name | Chemin du fichier où les commentaires seront stockés. |
| log_stream | Flux où les commentaires seront stockés. |
| error_action | Action pour les objets qui ne peuvent pas être convertis |
| transparency_action | Action pour les objets d'image masqués |
| convert_soft_mask_action | Action pour les images avec masque doux. |
| défaut | Obtient l'objet PdfFormatConversionOptions avec les paramètres par défaut |
| non_specification_cases | Contient des indicateurs pour contrôler le processus de conversion PDF/A pour les cas où le document source<br/>            ne correspond pas à la spécification PDF/A. |
| symbolic_font_encoding_strategy | Stratégie pour copier les données d'encodage des polices symboliques si la police TrueType symbolique<br/>            possède plus d'une table d'encodage. |
| align_text | Ce drapeau contrôle l'alignement du texte dans le document converti. Par défaut, la conversion du document <br/>            n'affecte pas l'alignement du texte et le laisse tel quel. Mais dans certains cas, la substitution de police<br/>            entraîne un chevauchement du texte ou des espaces supplémentaires dans le document converti. Lorsque ce drapeau est activé<br/>            des opérations d'alignement spéciales seront effectuées. Ce drapeau ne doit être activé que pour les documents<br/>            qui ont des problèmes de texte chevauché ou d'espaces supplémentaires, car son utilisation diminue<br/>            les performances et peut, dans certains cas, corrompre le contenu du texte. |
| pua_text_processing_strategy | Stratégie pour traiter les symboles de la zone d’utilisation privée Unicode (PUA). |
| optimize_file_size | Obtient ou définit un indicateur qui active/désactive le mode de conversion spécial pour obtenir un document PDF/A avec une taille de fichier réduite.<br/>            Cet indicateur influence désormais l'optimisation des polices utilisées dans le document PDF, et il est possible qu'à l'avenir, cet indicateur <br/>            soit également utilisé pour activer l'optimisation d'autres structures de données, telles que les graphiques.  <br/>            L'activation de cet indicateur et du mode peut réduire considérablement la taille du fichier, mais en même temps, elle peut<br/>            diminuer significativement les performances de la conversion. |
| exclude_fonts_strategy | Stratégie(s) pour exclure les polices superflues et réduire la taille du fichier du document. <br/>            Ce paramètre n'a de sens que lorsque le drapeau [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) est défini sur true.<br/>            Par défaut, la combinaison des stratégies [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) et<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) est utilisée. |
| font_embedding_options | Options pour les cas où il n'est pas possible d'incorporer certaines polices dans le document PDF. |
| unicode_processing_rules | Règles pour résoudre les problèmes de mappage Unicode. Peut être nul. |
| icc_profile_file_name | Obtient ou définit le nom de fichier du profil icc. En cas de null, le profil icc par défaut est utilisé. |
| not_accessible_fonts | Cette propriété est une propriété de sortie. Elle contient toutes les polices (noms de polices) qui n'ont pas été trouvées sur l'ordinateur <br/>            lors de la dernière conversion PDF/A. |
| is_transfer_info | Obtient ou définit s'il faut transférer les données de Info vers Metadata lors de la conversion en PDF 2.0. True par défaut. |
| align_strategy | Stratégie pour aligner le texte. Ce paramètre n'a de sens que lorsque le drapeau [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) est défini sur true. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

