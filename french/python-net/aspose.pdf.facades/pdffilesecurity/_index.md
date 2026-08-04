---
title: "PdfFileSecurity"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente le chiffrement ou le déchiffrement d'un fichier Pdf avec le mot de passe propriétaire ou utilisateur, la modification des paramètres de sécurité et du mot de passe."
type: docs
weight: 300
url: /fr/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Représente le chiffrement ou le déchiffrement d'un fichier Pdf avec le mot de passe propriétaire ou utilisateur, la modification des paramètres de sécurité et du mot de passe.

Le type PdfFileSecurity expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | Initialise une nouvelle instance de la classe PdfFileSecurity |
| PdfFileSecurity(input_file, output_file) | Initialise une nouvelle instance de la classe PdfFileSecurity |
| PdfFileSecurity() | Initialise l'objet PdfFileSecurity. |
| PdfFileSecurity(document) | Initialise une nouvelle instance de la classe PdfFileSecurity |
| PdfFileSecurity(document, output_file) | Initialise une nouvelle instance de la classe PdfFileSecurity |
| PdfFileSecurity(document, output_stream) | Initialise une nouvelle instance de la classe PdfFileSecurity |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| allow_exceptions | Si cette valeur est définie sur true, une exception sera levée en cas d'échec de l'opération. Sinon, la méthode renvoie false en cas d'échec et la dernière exception peut être vérifiée avec la propriété LastException. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_file) | Initialise la façade. |
| bind_pdf(src_stream) | Initialise la façade. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save(dest_file) | Enregistre le document PDF dans le fichier spécifié. |
| save(dest_stream) | Enregistre le document PDF dans le flux spécifié. |
| encrypt_file(user_password, owner_password, privilege, key_size) | Crypte le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges d'accès du document.<br/>            Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>            par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide.<br/>            Lève une exception si le processus a échoué. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | Crypte le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges d'accès du document.<br/>            Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>            par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide.<br/>            Il existe 6 combinaisons possibles des valeurs KeySize et Algorithm.<br/>            Cependant, (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante <br/>            sera levée si le kit rencontre cette combinaison.<br/>            Lève une exception si le processus a échoué. |
| set_privilege(privilege) | Définit la sécurité du fichier Pdf avec des mots de passe utilisateur/propriétaire vides.<br/>            Le mot de passe propriétaire sera ajouté sous forme d'une chaîne aléatoire.<br/>            Lève une exception si le processus a échoué. |
| set_privilege(user_password, owner_password, privilege) | Définit la sécurité du fichier Pdf avec le mot de passe original.<br/>            Lève une exception si le processus a échoué. |
| change_password(owner_password, new_user_password, new_owner_password) | Modifie le mot de passe utilisateur et le mot de passe propriétaire à l'aide du mot de passe propriétaire, en conservant les paramètres de sécurité originaux.<br/>             Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>             par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide.<br/>             Lève une exception si le processus a échoué. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Modifie le mot de passe utilisateur et le mot de passe à l'aide du mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf.<br/>            Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>            par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide.<br/>            Lève une exception si le processus a échoué. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Modifie le mot de passe utilisateur et le mot de passe par le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf.<br/>            Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>            par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide.<br/>            Il existe 6 combinaisons possibles des valeurs de KeySize et Algorithm.<br/>            Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante <br/>            sera levée si le kit rencontre cette combinaison.<br/>            Lève une exception si le processus échoue. |
| try_change_password(owner_password, new_user_password, new_owner_password) | Modifie le mot de passe utilisateur et le mot de passe propriétaire par le mot de passe propriétaire, conserve les paramètres de sécurité d'origine.<br/>             Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>             Ne lève pas d'exception si le processus échoue.<br/>             par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Modifie le mot de passe utilisateur et le mot de passe par le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf.<br/>            Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>            par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide.<br/>            Ne lève pas d'exception si le processus échoue. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Modifie le mot de passe utilisateur et le mot de passe par le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf.<br/>            Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>            par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide.<br/>            Il existe 6 combinaisons possibles des valeurs de KeySize et Algorithm.<br/>            Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante <br/>            sera levée si le kit rencontre cette combinaison.<br/>            Ne lève pas d'exception si le processus échoue. |
| close() | Ferme la façade. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | Crypte le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès.<br/>            Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé <br/>            par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide.<br/>            Ne lève pas d'exception si le processus échoue. |
| decrypt_file(owner_password) | Décrypte un document Pdf chiffré avec le mot de passe propriétaire.<br/>            Si le document n'a pas de mot de passe propriétaire, il est possible d'utiliser le mot de passe utilisateur.<br/>            Lève une exception si le processus échoue. |
| try_decrypt_file(owner_password) | Décrypte un document Pdf chiffré avec le mot de passe propriétaire.<br/>            Si le document n'a pas de mot de passe propriétaire, il est possible d'utiliser le mot de passe utilisateur.<br/>            Ne lève pas d'exception si le processus échoue. |
| try_set_privilege(user_password, owner_password, privilege) | Définit la sécurité du fichier Pdf avec le mot de passe d'origine.<br/>            Ne lève pas d'exception si le processus échoue. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

