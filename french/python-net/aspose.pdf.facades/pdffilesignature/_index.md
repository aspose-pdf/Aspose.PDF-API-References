---
title: "PdfFileSignature"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe permettant de signer un fichier pdf avec un certificat."
type: docs
weight: 310
url: /fr/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Représente une classe permettant de signer un fichier pdf avec un certificat.

Le type PdfFileSignature expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfFileSignature() | Le constructeur de la classe PdfFileSignature. |
| PdfFileSignature(input_file) | Initialise une nouvelle instance de la classe PdfFileSignature |
| PdfFileSignature(input_file, output_file) | Initialise une nouvelle instance de la classe PdfFileSignature |
| PdfFileSignature(document) | Initialise une nouvelle instance de la classe PdfFileSignature |
| PdfFileSignature(document, output_file) | Initialise une nouvelle instance de la classe PdfFileSignature |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| signature_appearance | Définit ou obtient l'apparence graphique de la signature. La valeur de la propriété représente le nom du fichier image. |
| is_ltv_enabled | Obtient le drapeau LTV activé. |
| is_certified | Obtient le drapeau déterminant si un document est certifié ou non. |
| signature_appearance_stream | Définit ou obtient l'apparence graphique de la signature. La valeur de la propriété représente le flux d'image. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(input_file) | Lie un fichier Pdf pour l'édition. |
| bind_pdf(input_stream) | Lie un flux Pdf pour l'édition. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save(output_file) | Enregistre le PDF résultant dans un fichier. |
| save(output_stream) | Enregistre le PDF résultant dans un flux. |
| save() | Enregistre le PDF résultant dans un fichier. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Créer une signature sur le document pdf. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Signer le document avec la signature de type donnée. |
| sign(page, visible, annot_rect, sig) | Signer le document avec la signature de type donnée. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Signer le document avec la signature de type donnée. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Signer le document avec la signature de type donnée. |
| sign(sig_name, sig) | Signer le document avec la signature de type donnée. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Certifier le document avec la signature MDP.<br/>            Des données telles que le motif de la signature, le contact et le lieu doivent être fournies par les propriétés correspondantes de l'objet Signature sig. |
| certify(sig_name, doc_mdp_signature) | Certifier le document avec la signature MDP.<br/>            Des données telles que le motif de la signature, le contact et le lieu doivent être fournies par les propriétés correspondantes de l'objet Signature sig. |
| remove_signature(sign_name) | Supprimer la signature selon le nom de la signature. |
| remove_signature(sign_name, remove_field) | Supprime la signature selon le nom de la signature. |
| close() | Ferme la façade. |
| get_access_permissions() | Renvoie la valeur des autorisations d'accès du document certifié par le type de signature MDP. |
| get_sign_names(only_active) | Obtient les noms de toutes les signatures non vides. |
| get_blank_sign_names() | Obtient les noms de tous les champs de signature vides. |
| is_contain_signature() | Vérifie si le pdf possède une signature numérique ou non. |
| contains_signature() | Vérifie si le pdf possède une signature numérique ou non. |
| contains_usage_rights() | Vérifie si le pdf possède des droits d'utilisation ou non. |
| is_covers_whole_document(sign_name) | Vérifie si la signature couvre l'ensemble du document. |
| covers_whole_document(sign_name) | Vérifie si la signature couvre l'ensemble du document. |
| get_revision(sign_name) | Obtient la révision d'une signature. |
| get_total_revision() | Obtient la révision totale. |
| remove_usage_rights() | Supprime l'entrée des droits d'utilisation. |
| verify_signed(sign_name) | Vérifie la validité d'une signature. |
| get_signer_name(sign_name) | Obtient le nom de la personne ou de l'organisation qui signe le document pdf. |
| get_date_time(sign_name) | Obtient la date et l'heure de la signature. |
| get_reason(sign_name) | Obtient la raison d'une signature. |
| get_location(sign_name) | Obtient le lieu d'une signature. |
| get_contact_info(sign_name) | Obtient les informations de contact d'une signature. |
| verify_signature(sign_name) | Vérifie la validité d'une signature. |
| extract_image(sign_name) | Extrait l'image de la signature. |
| extract_certificate(sign_name) | Extrait le certificat X.509 unique de la signature sous forme de flux. |
| set_certificate(pfx, pass) | Définit le fichier de certificat et le mot de passe pour la routine de signature. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

