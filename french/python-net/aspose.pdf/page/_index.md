---
title: "Page"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant une page du document PDF."
type: docs
weight: 1080
url: /fr/python-net/aspose.pdf/page/
---

## Page class

Classe représentant une page du document PDF.

Le type Page expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| is_add_paragraphs_after_last | Obtient ou définit l'ajout de paragraphes après le dernier paragraphe de la page |
| background_image | Obtient ou définit l'image d'arrière‑plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document). |
| toc_info | Obtient ou définit les informations de la table des matières. |
| header | Obtient ou définit l'en-tête de la page. |
| couches | Obtient ou définit la collection de couches. |
| pied de page | Obtient ou définit le pied de page de la page. |
| paragraphs | Obtient les paragraphes. |
| page_info | Obtient ou définit les informations de la page (uniquement pour le générateur, non rempli lors de la lecture du document). |
| rect | Obtient ou définit le rectangle de la page.<br/>            Pour la lecture : la boîte de recadrage de la page est renvoyée si spécifiée, sinon la boîte média de la page est renvoyée.<br/>            Pour l'écriture : la boîte média de la page est toujours définie.<br/>            Veuillez noter que cette propriété ne prend pas en compte la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, veuillez utiliser ActualRect. |
| type_couleur | Définit le type de couleur des pages en fonction des informations obtenues des opérateurs SetColor,<br/>            images et formulaires. |
| style_ligne_note | Obtient ou définit le style de ligne pour les notes (uniquement pour le générateur, non rempli lors de la lecture du document). |
| tab_order | Obtient ou définit l'ordre des onglets de la page. <br/>            Valeurs possibles : Row, Column. Par défaut, Manual. |
| durée | Obtient ou définit la durée d'affichage de la page. Il s'agit du temps en secondes pendant lequel la page doit être affichée lors de la présentation.<br/>            Retourne -1 si la durée n'est pas définie. |
| contents | Obtient la collection d'opérateurs dans le flux de contenu de la page.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| groupe | Obtient ou définit une classe d'attributs de groupe spécifiant les attributs du groupe de pages pour une utilisation dans le modèle d'imagerie transparente. |
| annotations | Obtient la collection d'annotations de page.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| tourner | Obtient ou définit la rotation de la page. |
| trim_box | Obtient ou définit la boîte de rognage de la page. |
| art_box | Obtient ou définit la boîte d'art de la page. |
| bleed_box | Obtient ou définit le bleed box de la page. |
| crop_box | Obtient ou définit le crop box de la page. |
| media_box | Obtient ou définit le media box de la page. |
| nombre | Obtient le numéro de la page. |
| rotation_matrix | Obtient la matrice de transformation pour la page. |
| background | Obtient ou définit la couleur d'arrière-plan de la page. |
| watermark | Obtient ou définit le filigrane de la page. |
| artifacts | Obtient la collection d'artefacts sur la page. |
| actions | Obtient la collection des propriétés de la page. |
| fields_in_tab_order | Obtient la liste d'objets Field dans l'ordre d'onglet sur cette page. |
| user_unit | Obtient ou définit la valeur UserUnit. Un nombre positif indiquant la taille des unités d'espace utilisateur par défaut, en multiples de 1 ⁄ 72 pouce.<br/>            La valeur par défaut est 1. Veuillez définir zéro ou une valeur négative afin de supprimer cette entrée de la page. |
## Méthodes
| Nom | Description |
| :- | :- |
| send_to(device, output) | Envoie la page au processus avec le dispositif de page fourni. |
| send_to(device, output_file_name) | Envoie la page au processus avec le dispositif de page fourni. |
| accept(visitor) | Accepte l'objet visiteur [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) qui fournit des fonctionnalités pour travailler avec les annotations. |
| accept(visitor) | Accepte l'objet visiteur [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) qui fournit des fonctionnalités pour travailler avec les objets texte. |
| accept(visitor) | Accepte l'objet visiteur [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de placement d'image. |
| accept(visitor) | Accepte l'objet visiteur [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) qui fournit des fonctionnalités pour travailler avec les objets texte. |
| add_image(image_stream, image_rect) | Ajoute une image à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| add_image(hocr, image_stream, image_rect) | Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | Ajoute une image sur la page et la place en fonction de la position du rectangle de l'image. |
| add_image(image_path, rectangle) | Ajoute une image recherchable à la page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| is_blank(fill_threshold_factor) | Obtient le drapeau indiquant si la page est vide ou non. |
| get_page_rect(consider_rotation) | Renvoie le rectangle de la page selon son CropBox (ou MediaBox si le CropBox est nul). |
| calculate_content_b_box() | Calcule la valeur du bbox - rectangle contenant le contenu sans marges visibles. |
| rotation_to_int(rotation) | Traduit le membre d'énumération de rotation en valeur entière. |
| int_to_rotation(rotation) | Traduit la valeur entière en le membre d'énumération de rotation correspondant. |
| add_stamp(stamp) | Place un tampon sur la page. Le tampon peut être le numéro de page, une image ou du texte simple, par ex. un logo. |
| flatten() | Supprime tous les champs situés sur la page et place leurs valeurs à la place. |
| set_page_size(width, height) | Définit la taille de la page. |
| make_grayscale() | Convertit la page en niveaux de gris. |
| free_memory() | Efface les données en cache |
| get_notifications() | Renvoie les notifications concernant les opérations internes sur le contenu de la page. (Seules les notifications concernant les événements de paragraphe dans les scénarios d'ajout de texte sont prises en charge pour le moment.) |
| as_byte_array(resolution) | Convertit la page actuelle en bitmap puis renvoie un tableau d'octets. |
| as_xml() | Convertit la page actuelle en XML avec encodage UTF-8. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

