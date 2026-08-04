---
title: "HeaderArtifact"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "La classe décrit l'artéfact Heaader. Cet artifacgt peut être utilisé pour définir l'en-tête de la page."
type: docs
weight: 440
url: /fr/python-net/aspose.pdf/headerartifact/
---

## HeaderArtifact class

La classe décrit l'artéfact Heaader. Cet artifacgt peut être utilisé pour définir l'en-tête de la page.

Le type HeaderArtifact expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| HeaderArtifact() | Crée une instance de Header Artifact. |
## Propriétés
| Nom | Description |
| :- | :- |
| custom_type | Obtient le nom du type d'artefact. Peut être utilisé si le type d'artefact n'est pas standard. |
| custom_subtype | Obtient le nom du sous-type d'artefact. Peut être utilisé si le sous-type d'artefact n'est pas un sous-type standard. |
| type | Obtient le type d'artefact. |
| subtype | Obtient le sous-type d'artefact. Si l'artefact possède un sous-type non standard, le nom du sous-type peut être lu via CustomSubtype. |
| contenu | Obtient la collection des opérateurs internes de l'artefact. |
| form | Obtient le XForm de l'artefact (si le XForm est utilisé). |
| rectangle | Obtient le rectangle de l'artefact. |
| position | Obtient ou définit la position de l'artefact.<br/>            Si cette propriété est spécifiée, alors les marges et les alignements sont ignorés. |
| right_margin | Marge droite de l'artefact. <br/>            Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| left_margin | Marge gauche de l'artefact. <br/>            Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| top_margin | Marge supérieure de l'artefact. <br/>            Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| bottom_margin | Marge inférieure de l'artefact. <br/>            Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| artifact_horizontal_alignment | Alignement horizontal de l'artefact. <br/>            Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| artifact_vertical_alignment | Alignement vertical de l'artefact. <br/>            Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| rotation | Obtient ou définit l'angle de rotation de l'artefact. |
| text | Obtient le texte de l'artefact. |
| image | Obtient l'image de l'artefact (si présent). |
| opacité | Obtient ou définit l'opacité de l'artefact. Les valeurs possibles sont dans la plage 0..1. |
| lines | Lignes de l'artefact texte multiligne. |
| text_state | État du texte pour le texte de l'artefact. |
| is_background | Si vrai, l'artefact est placé derrière le contenu de la page. |
## Méthodes
| Nom | Description |
| :- | :- |
| set_image(image_stream) | Définit l'image de l'artefact. |
| set_image(image_name) | Définit l'image de l'artefact. |
| set_text(formatted_text) | Définit le texte de l'artefact. |
| set_text_and_state(text, text_state) | Définit le texte et les propriétés du texte de l'artefact. |
| set_lines_and_state(text, text_state) | Définit le texte et les propriétés du texte de l'artefact. Permet de spécifier plusieurs lignes. |
| set_pdf_page(page) | Définit la page PDF qui est placée sur la page du document en tant qu'artefact. |
| get_value(name) | Obtient la valeur personnalisée de l'artefact. |
| set_value(name, value) | Définit la valeur personnalisée de l'artefact. |
| remove_value(name) | Supprime la valeur personnalisée de l'artefact. |
| begin_updates() | Démarrer les mises à jour différées. Utilisez cette fonctionnalité si vous devez effectuer plusieurs modifications du même artefact afin d'améliorer les performances. <br/>            Habituellement, les opérateurs d'artefact sont modifiés chaque fois qu'une propriété d'artefact a été changée. Cela entraîne la modification du contenu des pages<br/>            chaque fois que l'artefact a été modifié. Pour éviter cet effet, placez toutes les mises à jour d'artefact entre les appels StartUpdates/SaveUpdates.<br/>            Cela permet de modifier le contenu des pages une seule fois. |
| save_updates() | Enregistre toutes les mises à jour de l'artefact qui ont été effectuées après l'appel de BeginUpdates(). |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

