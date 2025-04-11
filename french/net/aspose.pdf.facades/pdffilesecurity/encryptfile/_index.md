---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSecurity. Crypte le fichier Pdf avec un mot de passe utilisateur et un mot de passe propriétaire et définit les privilèges d'accès aux documents. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire d'entrée est nul ou vide. Lève une exception si le processus échoue.
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Crypte le fichier Pdf avec un mot de passe utilisateur et un mot de passe propriétaire et définit les privilèges d'accès du document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire d'entrée est nul ou vide. Lève une exception si le processus échoue.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur. |
| ownerPassword | String | Mot de passe propriétaire. |
| privilege | DocumentPrivilege | Définir le privilège. |
| keySize | KeySize | KeySize.x40 pour le cryptage 40 bits, KeySize.x128 pour le cryptage 128 bits et KeySize.x256 pour le cryptage 256 bits. |

### Valeur de retour

Vrai pour le succès.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Voir aussi

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Crypte le fichier Pdf avec un mot de passe utilisateur et un mot de passe propriétaire et définit les privilèges d'accès du document. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire d'entrée est nul ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant, (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et une exception correspondante sera levée si le kit rencontre cette combinaison. Lève une exception si le processus échoue.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur. |
| ownerPassword | String | Mot de passe propriétaire. |
| privilege | DocumentPrivilege | Définir le privilège. |
| keySize | KeySize | KeySize.x40 pour le cryptage 40 bits, KeySize.x128 pour le cryptage 128 bits et KeySize.x256 pour le cryptage 256 bits. |
| cipher | Algorithm | Algorithm.AES pour crypter en utilisant l'algorithme AES ou Algorithm.RC4 pour le cryptage RC4. |

### Valeur de retour

Vrai pour le succès.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Voir aussi

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)