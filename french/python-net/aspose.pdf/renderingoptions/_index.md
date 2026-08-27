---
title: "RenderingOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente les options de rendu."
type: docs
weight: 1330
url: /fr/python-net/aspose.pdf/renderingoptions/
---

## RenderingOptions class

Représente les options de rendu.

Le type RenderingOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| RenderingOptions() | Initialise une nouvelle instance de la classe RenderingOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| barcode_optimization | Obtient ou définit le mode d'optimisation du code-barres. |
| optimize_dimensions | Obtient ou définit le mode d'optimisation des dimensions. |
| system_fonts_native_rendering | Obtient ou définit un mode où les polices système sont rendues nativement. |
| use_new_imaging_engine | Obtient ou définit un indicateur qui détermine si le nouveau moteur d'imagerie est utilisé ou non. |
| width_extra_units | Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle. |
| height_extra_units | Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle. |
| convert_fonts_to_unicode_ttf | Indique que toutes les polices seront converties en versions TTF Unicode. Cela est utile pour des raisons de compatibilité <br/>             et pour optimiser l'utilisation des polices, car chaque nouvelle police TTF ne contiendra pas tous les symboles <br/>             de la police source, mais uniquement les symboles utilisés dans le texte. |
| use_font_hinting | L'utilisation de cet indicateur active le mécanisme de hinting des polices. Le hinting des polices consiste à utiliser des instructions mathématiques pour ajuster l'affichage <br/>            d'une police vectorielle. Dans certains cas, activer cet indicateur peut résoudre les problèmes de lisibilité du texte. <br/>            Pour le moment, l'utilisation de cet indicateur ne peut avoir d'effet que sur les polices TTF, si ces polices sont utilisées dans le document source. |
| scale_images_to_fit_page_width | Obtient ou définit une valeur utilisée pour mettre à l'échelle toutes les images de la page afin d'ajuster la largeur de la page. |
| interpolation_high_quality | Obtient ou définit le mode de haute qualité pour l'interpolation. |
| max_fonts_cache_size | Nombre maximal de polices dans le cache de polices. La valeur par défaut est 10. |
| max_symbols_cache_size | Nombre maximal de symboles dans le cache de symboles. La valeur par défaut est 100. |
| default_font_name | Obtient/définit le nom par défaut de la police utilisée pour remplacer les polices manquantes. |
| ignore_resource_font_errors | Obtient ou définit l'indication selon laquelle les erreurs liées à l'absence de police seront ignorées.<br/>            true - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte qui font référence à des ressources incorrectes seront ignorés pendant le traitement.<br/>            false par défaut |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

