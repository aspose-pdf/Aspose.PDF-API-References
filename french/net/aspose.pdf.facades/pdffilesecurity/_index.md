---
title: PdfFileSecurity
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente le cryptage ou le décryptage dun fichier PDF avec le mot de passe du propriétaire ou de lutilisateur en modifiant le paramètre de sécurité et le mot de passe.
type: docs
weight: 2560
url: /fr/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Représente le cryptage ou le décryptage d'un fichier PDF avec le mot de passe du propriétaire ou de l'utilisateur, en modifiant le paramètre de sécurité et le mot de passe.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | Initialiser l'objet de PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | Initialise nouveau[`PdfFileSecurity`](../pdffilesecurity) objet sur la base de la*document* . |

## Propriétés

| Nom | La description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | Renvoie l'exception qui a été levée par la dernière opération. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | Initialise la façade. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | Modifie le mot de passe utilisateur et le mot de passe propriétaire par mot de passe propriétaire, conserve les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide. Lance une exception si le processus a échoué. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Change le mot de passe utilisateur et le mot de passe par mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide. Lance une exception si le processus a échoué. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Change le mot de passe utilisateur et le mot de passe par mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) ne sont pas valides et l'exception correspondante sera déclenchée si le kit rencontre cette combinaison. Lève une exception si le processus a échoué. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | Ferme la façade. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | Décrypte un document PDF crypté par mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est autorisé à utiliser le mot de passe utilisateur. Lance une exception si le processus a échoué. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | Crypte le fichier PDF avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges d'accès au document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le mot de passe du propriétaire saisi est nul ou vide. Lève une exception si le processus a échoué. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Crypte le fichier PDF avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges d'accès au document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le mot de passe du propriétaire saisi est nul ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) ne sont pas valides et l'exception correspondante sera déclenchée si le kit rencontre cette combinaison. Lève une exception si le processus a échoué. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Enregistre le document PDF dans le fichier spécifié. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | Définit la sécurité des fichiers PDF avec des mots de passe utilisateur/propriétaire vides. Le mot de passe du propriétaire sera ajouté par une chaîne aléatoire. Lève une exception si le processus a échoué. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | Définit la sécurité du fichier PDF avec le mot de passe d'origine. Lève une exception si le processus a échoué. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | Modifie le mot de passe utilisateur et le mot de passe propriétaire par mot de passe propriétaire, conserve les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé Ne génère pas d'exception si le processus a échoué. par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Change le mot de passe utilisateur et le mot de passe par mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide. Ne lève pas d'exception si le processus a échoué. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Change le mot de passe utilisateur et le mot de passe par mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) ne sont pas valides et l'exception correspondante sera déclenchée si le kit rencontre cette combinaison. Ne lève pas d'exception si le processus a échoué. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | Décrypte un document PDF crypté par mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est autorisé à utiliser le mot de passe utilisateur. Ne lève pas d'exception si le processus a échoué. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | Crypte le fichier PDF avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges d'accès au document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le mot de passe du propriétaire saisi est nul ou vide. Ne lève pas d'exception si le processus a échoué. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | Définit la sécurité du fichier PDF avec le mot de passe d'origine. Ne génère pas d'exception si le processus a échoué. |

### Voir également

* class [SaveableFacade](../saveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
