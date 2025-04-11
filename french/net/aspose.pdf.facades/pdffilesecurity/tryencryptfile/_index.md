---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSecurity. Crypte le fichier Pdf avec un mot de passe utilisateur et un mot de passe propriétaire et définit les privilèges d'accès du document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire d'entrée est nul ou vide. Ne lance pas d'exception si le processus échoue.
type: docs
weight: 110
url: /fr/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## Méthode PdfFileSecurity.TryEncryptFile

Crypte le fichier Pdf avec un mot de passe utilisateur et un mot de passe propriétaire et définit les privilèges d'accès du document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire d'entrée est nul ou vide. Ne lance pas d'exception si le processus échoue.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur. |
| ownerPassword | String | Mot de passe propriétaire. |
| privilege | DocumentPrivilege | Définir le privilège. |
| keySize | KeySize | KeySize.x40 pour le cryptage de 40 bits, KeySize.x128 pour le cryptage de 128 bits et KeySize.x256 pour le cryptage de 256 bits. |

### Valeur de retour

Vrai pour le succès, ou faux.

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

* classe [DocumentPrivilege](../../documentprivilege/)
* énum [KeySize](../../keysize/)
* classe [PdfFileSecurity](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)