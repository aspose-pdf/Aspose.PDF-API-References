---
title: "Stamp"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant un tampon."
type: docs
weight: 410
url: /fr/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Classe représentant un tampon.

Le type Stamp expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| Stamp() | Initialise une nouvelle instance de la classe Stamp |
## Propriétés
| Nom | Description |
| :- | :- |
| stamp_id | Obtient ou définit l'identifiant du tampon. |
| qualité | Obtient ou définit la qualité du tampon d'image en pourcentage. Valeurs valides 0..100%. |
| opacité | Obtient ou définit l'opacité du tampon. |
| page_number | Obtient ou définit le numéro de page. |
| pages | Obtient ou définit un tableau avec les numéros de pages qui seront affectées par le tampon. <br/>            Si Pages = null toutes les pages du document sont affectées. |
| rotation | Obtient ou définit la rotation du tampon en degrés. |
| is_background | Obtient ou définit l'état d'arrière-plan. Si vrai, le tampon sera placé en arrière-plan de la page tamponnée.<br/>            Par défaut, il est réglé sur false. |
| blending_space | Obtient ou définit une valeur BlendingColorSpace qui définit un espace colorimétrique <br/>            utilisé pour effectuer des opérations de transparence et de fusion sur la page. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(pdf_file, page_number) | Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon. |
| bind_pdf(pdf_stream, page_number) | Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon. |
| bind_image(image_file) | Définit l'image comme tampon. |
| bind_image(image) | Définit l'image qui sera utilisée comme tampon. |
| bind_logo(formatted_text) | Définit le texte comme tampon. |
| bind_text_state(text_state) | Définit l'état du texte du tampon. |
| set_origin(origin_x, origin_y) | Définit la position sur la page où le tampon sera placé. |
| set_image_size(width, height) | Définit la taille du tampon d'image. L'image sera redimensionnée selon les valeurs spécifiées. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

