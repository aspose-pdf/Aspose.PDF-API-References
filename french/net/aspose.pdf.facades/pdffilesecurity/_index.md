---
title: "Classe PdfFileSecurity"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Facades.PdfFileSecurity classe. Représente le chiffrement ou le déchiffrement d'un fichier Pdf avec le mot de passe propriétaire ou utilisateur en modifiant les paramètres de sécurité et le mot de passe."
type: docs
weight: 4670
url: /fr/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Représente le chiffrement ou le déchiffrement d'un fichier Pdf avec le mot de passe propriétaire ou utilisateur, ainsi que la modification des paramètres de sécurité et du mot de passe.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Initialise l'objet PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Initialise un nouvel objet `PdfFileSecurity` basé sur le *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur laquelle travaille. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Renvoie l'exception qui a été levée par la dernière opération. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Initialise la façade. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Modifie le mot de passe utilisateur et le mot de passe propriétaire à l'aide du mot de passe propriétaire, conserve les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Lève une exception si le processus échoue. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Modifie le mot de passe utilisateur et le mot de passe à l'aide du mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Lève une exception si le processus échoue. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Modifie le mot de passe utilisateur et le mot de passe à l'aide du mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et une exception correspondante sera levée si le kit rencontre cette combinaison. Lève une exception si le processus échoue. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Ferme la façade. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Déchiffre un document Pdf chiffré avec le mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est possible d'utiliser le mot de passe utilisateur. Lève une exception si le processus échoue. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libère la façade. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Chiffre un fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges d'accès du document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Lève une exception si le processus échoue. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Chiffre un fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges d'accès du document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et une exception correspondante sera levée si le kit rencontre cette combinaison. Lève une exception si le processus échoue. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Enregistre le document PDF dans le fichier spécifié. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Définit la sécurité du fichier Pdf avec des mots de passe utilisateur/propriétaire vides. Le mot de passe propriétaire sera ajouté sous forme d'une chaîne aléatoire. Lève une exception si le processus échoue. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Définit la sécurité du fichier Pdf avec le mot de passe original. Lève une exception si le processus échoue. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Modifie le mot de passe utilisateur et le mot de passe propriétaire à l'aide du mot de passe propriétaire, conserve les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lève pas d'exception si le processus échoue. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Modifie le mot de passe utilisateur et le mot de passe à l'aide du mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lève pas d'exception si le processus échoue. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Modifie le mot de passe utilisateur et le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante sera levée si le kit rencontre cette combinaison. Ne lève pas d'exception si le processus échoue. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Déchiffre un document Pdf chiffré avec le mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est possible d'utiliser le mot de passe utilisateur. Ne lève pas d'exception si le processus échoue. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Crypte le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Ne lève pas d'exception si le processus échoue. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Définit la sécurité du fichier Pdf avec le mot de passe d'origine. Ne lève pas d'exception si le processus échoue. |

### Voir aussi

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


