---
title: "Autorisations"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Cette énumération représente les autorisations de l'utilisateur pour un PDF."
type: docs
weight: 6560
url: /fr/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

Cette énumération représente les autorisations de l'utilisateur pour un PDF.

## Members
| Nom du membre | Description |
| :- | :- |
| PRINT_DOCUMENT | (Gestionnaires de sécurité de la révision 2) Imprimer le document.<br/>            (Gestionnaires de sécurité de la révision 3 ou supérieure) Imprimer le document <br/>            (possiblement pas au niveau de qualité le plus élevé, <br/>            selon que [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) est également activé). |
| MODIFY_CONTENT | Modifier le contenu du document par des opérations autres <br/>            que celles contrôlées par  [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/), <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/), et 11. |
| EXTRACT_CONTENT | (Gestionnaires de sécurité de la révision 2) Copier ou extraire autrement <br/>            le texte et les graphiques du document, y compris l'extraction <br/>            du texte et des graphiques (pour soutenir l'accessibilité des utilisateurs <br/>            en situation de handicap ou à d'autres fins).<br/>            (Gestionnaires de sécurité de la révision 3 ou supérieure) Copier ou extraire autrement <br/>            le texte et les graphiques du document par des opérations <br/>            autres que celles contrôlées par [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/). |
| MODIFY_TEXT_ANNOTATIONS | Ajouter ou modifier des annotations de texte, remplir les champs de formulaire interactifs, <br/>            et, si [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) est également activé, créer ou modifier des champs de formulaire interactifs <br/>            (y compris les champs de signature). |
| FILL_FORM | (Gestionnaires de sécurité de la révision 3 ou supérieure) Remplir les champs de formulaire interactifs existants <br/>            (y compris les champs de signature), même si <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) est désactivé. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Gestionnaires de sécurité de la révision 3 ou supérieure) Extraire le texte et <br/>            les graphiques (pour soutenir l'accessibilité des utilisateurs en situation de handicap <br/>            ou à d'autres fins). |
| ASSEMBLE_DOCUMENT | (Gestionnaires de sécurité de la révision 3 ou supérieure) Assembler le document <br/>            (insérer, faire pivoter ou supprimer des pages et créer des signets ou des miniatures <br/>            d'images), même si [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) est désactivé. |
| PRINTING_QUALITY | (Gestionnaires de sécurité de la révision 3 ou supérieure) Imprimer le document vers <br/>            une représentation à partir de laquelle une copie numérique fidèle du contenu PDF <br/>            pourrait être générée. Lorsque ce bit est désactivé (et que le bit 3 est activé), <br/>            l'impression est limitée à une représentation de bas niveau de l'apparence, <br/>            éventuellement de qualité dégradée. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

