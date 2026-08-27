---
title: "FontRepository"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Effectue une recherche de polices. Recherche parmi les polices installées sur le système et les polices Pdf standard.<br/>             Fournit également la fonctionnalité d'ouvrir des polices personnalisées."
type: docs
weight: 130
url: /fr/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Effectue une recherche de polices. Recherche parmi les polices installées sur le système et les polices Pdf standard.<br/>             Fournit également la fonctionnalité d'ouvrir des polices personnalisées.

Le type FontRepository expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| FontRepository() | Initialise une nouvelle instance de la classe FontRepository |
## Propriétés
| Nom | Description |
| :- | :- |
| substitutions | Obtient la collection des stratégies de substitution de police. |
| sources | Obtient la collection des sources de police. |
## Méthodes
| Nom | Description |
| :- | :- |
| find_font(font_name) | Recherche et renvoie la police avec le nom de police spécifié. |
| find_font(font_name, ignore_case) | Recherche et renvoie la police avec le nom de police spécifié en ignorant ou en respectant la sensibilité à la casse. |
| find_font(font_family_name, stl) | Recherche et renvoie la police avec le nom de police et le style de police spécifiés. |
| find_font(font_family_name, stl, ignore_case) | Recherche et renvoie la police avec le nom de police et le style de police spécifiés <br/>             en ignorant ou en respectant la sensibilité à la casse. |
| open_font(font_stream, font_type) | Ouvre la police avec le flux de police spécifié. |
| open_font(font_file_path) | Ouvre la police avec le chemin de fichier de police spécifié. |
| open_font(font_file_path, metrics_file_path) | Ouvre la police avec le chemin de fichier de police spécifié. |
| load_fonts() | Charge les polices installées sur le système et les polices Pdf standard. Cette méthode a été conçue pour accélérer le processus de chargement des polices.<br/>            Par défaut, les polices sont chargées lors de la première requête pour n'importe quelle police. L'utilisation de cette méthode charge les polices du système et les polices Pdf standard<br/>            immédiatement avant l'ouverture de tout document Pdf. |
| reload_fonts() | Recharge toutes les polices spécifiées par la propriété [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

