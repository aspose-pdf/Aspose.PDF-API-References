---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileSecurity. Chiffre le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges d'accès du document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Ne lève pas d'exception si le processus échoue."
type: docs
weight: 110
url: /fr/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

Crypte le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Ne lève pas d'exception si le processus échoue.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe de l'utilisateur. |
| ownerPassword | String | Mot de passe du propriétaire. |
| privilège | DocumentPrivilege | Définir le privilège. |
| keySize | KeySize | KeySize.x40 pour le chiffrement 40 bits, KeySize.x128 pour le chiffrement 128 bits et KeySize.x256 pour le chiffrement 256 bits. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Voir aussi

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


