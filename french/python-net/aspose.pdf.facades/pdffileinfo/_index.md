---
title: "PdfFileInfo"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe permettant d'accéder aux métadonnées d'un document PDF."
type: docs
weight: 270
url: /fr/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Représente une classe permettant d'accéder aux métadonnées d'un document PDF.

Le type PdfFileInfo expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfFileInfo() | Initialise une nouvelle instance de la classe Aspose.Pdf.Facades.PdfFileInfo avec les valeurs par défaut. |
| PdfFileInfo(input_stream) | Initialise une nouvelle instance de la classe PdfFileInfo |
| PdfFileInfo(input_stream, password) | Initialise une nouvelle instance de la classe PdfFileInfo |
| PdfFileInfo(input_file) | Initialise une nouvelle instance de la classe PdfFileInfo |
| PdfFileInfo(input_file, password) | Initialise une nouvelle instance de la classe PdfFileInfo |
| PdfFileInfo(document) | Initialise une nouvelle instance de la classe PdfFileInfo |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| author | Obtient ou définit les informations Author du document PDF. |
| is_encrypted | Vérifie si le document PDF est chiffré. |
| is_pdf_file | Vérifie si l'entrée source est un fichier PDF valide. |
| use_strict_validation | Utilise des règles de validation strictes via la propriété [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | Obtient ou définit les informations CreationDate du document PDF. |
| creator | Obtient ou définit les informations Creator du document PDF. |
| has_collection | Renvoie vrai si le fichier d'entrée actuel est un fichier 'Portfolio' contenant une collection de fichiers PDF. |
| input_file | Obtient ou définit le fichier d'entrée. |
| input_stream | Obtient ou définit le flux d'entrée. |
| keywords | Obtient ou définit les informations des Keywords du document PDF. |
| mod_date | Obtient ou définit les informations de date ModDate du document PDF. |
| number_of_pages | Obtient le nombre de pages du document. |
| producer | Obtient les informations du Producer du document PDF. |
| subject | Obtient ou définit les informations du Subject du document PDF. |
| title | Obtient ou définit les informations du Title du document PDF. |
| password_type | Renvoie le type de mot de passe qui a été passé lors de la création de l'instance PdfFileInfo. Voir les valeurs possibles dans [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Faites attention que le document pdf peut être ouvert avec à la fois le mot de passe utilisateur (ou d'ouverture) et le mot de passe propriétaire (ou permissions, édition). |
| has_open_password | Renvoie vrai si un mot de passe est nécessaire pour ouvrir le document pdf protégé par mot de passe. |
| has_edit_password | Renvoie vrai si un mot de passe est nécessaire pour modifier les permissions ou la propriété de sécurité du document.<br/>            Faites attention que cette propriété ne peut être lue que si un mot de passe valide a été fourni dans le constructeur [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Dans le cas où PasswordType est Inaccessible (signifie qu'un mot de passe invalide a été fourni), la lecture de cette propriété échouera avec [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/). |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_doc) | Initialise la façade. |
| bind_pdf(src_file) | Initialise la façade. |
| bind_pdf(src_stream) | Initialise la façade. |
| save(dest_stream) | Enregistre le document PDF mis à jour dans le flux spécifié. |
| save(dest_file) | Enregistre le document PDF mis à jour dans le fichier spécifié. |
| save_new_info(output_stream) | Enregistre le document PDF mis à jour dans le flux spécifié. |
| save_new_info(output_file) | Enregistre le document PDF mis à jour dans le fichier spécifié. |
| close() | Désinitialise l'instance. |
| clear_info() | Efface toutes les informations méta du document PDF. |
| get_document_privilege() | Obtient les paramètres de privilèges du document PDF. |
| get_meta_info(name) | Obtient les informations personnalisées du document PDF avec le nom de propriété. S'il n'existe aucune propriété correspondant au nom, il renverra une chaîne vide. |
| get_page_height(page_num) | Obtient la hauteur de la page spécifiée. |
| get_page_rotation(page_num) | Obtient la rotation de la page spécifiée. |
| get_page_width(page_num) | Obtient la largeur de la page spécifiée. |
| get_page_x_offset(page_num) | Obtient le décalage horizontal de la zone d'affichage de la page spécifiée. |
| get_page_y_offset(page_num) | Obtient le décalage vertical de la zone d'affichage de la page spécifiée. |
| get_pdf_version() | Obtient les informations de version du document PDF. |
| set_meta_info(name, value) | Définit les informations personnalisées du document PDF. |
| save_new_info_with_xmp(output_file_name) | Modifie les propriétés spécifiées explicitement en définissant les informations du fichier, les autres propriétés restent inchangées. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

