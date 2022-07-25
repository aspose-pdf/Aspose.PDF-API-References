---
title: TryChangePassword
second_title: Référence de l'API Aspose.PDF pour .NET
description: Modifie le mot de passe utilisateur et le mot de passe propriétaire par mot de passe propriétaire conserve les paramètres de sécurité dorigine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé Ne génère pas dexception si le processus a échoué. par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide.
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Modifie le mot de passe utilisateur et le mot de passe propriétaire par mot de passe propriétaire, conserve les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé Ne génère pas d'exception si le processus a échoué. par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe du propriétaire d'origine. |
| newUserPassword | String | Nouveau mot de passe utilisateur. |
| newOwnerPassword | String | Nouveau mot de passe propriétaire. |

### Return_Value

Vrai pour le succès, ou faux.

### Exemples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; // Le TestPath peut être réaffecté.
 string outFile = "D:\\output.pdf";	// Le TestPath peut être réaffecté.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Voir également

* class [PdfFileSecurity](../../pdffilesecurity)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesecurity)
* Assemblée [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Change le mot de passe utilisateur et le mot de passe par mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide. Ne lève pas d'exception si le processus a échoué.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe du propriétaire d'origine. |
| newUserPassword | String | Nouveau mot de passe utilisateur. |
| newOwnerPassword | String | Nouveau mot de passe propriétaire. |
| privilege | DocumentPrivilege | Réinitialisez la sécurité. |
| keySize | KeySize | KeySize.x40 pour un cryptage 40 bits, KeySize.x128 pour un cryptage 128 bits et KeySize.x256 pour un cryptage 256 bits. |

### Return_Value

Vrai pour le succès, ou faux.

### Exemples

```csharp
[C#]
string inFile = ".D:\\input.pdf"; // Le TestPath peut être réaffecté.
string outFile = "D:\\output.pdf";	// Le TestPath peut être réaffecté.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Voir également

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesecurity)
* Assemblée [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Change le mot de passe utilisateur et le mot de passe par mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être nuls ou vides. Le mot de passe du propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe du propriétaire est nul ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) ne sont pas valides et l'exception correspondante sera déclenchée si le kit rencontre cette combinaison. Ne lève pas d'exception si le processus a échoué.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe du propriétaire d'origine. |
| newUserPassword | String | Nouveau mot de passe utilisateur. |
| newOwnerPassword | String | Nouveau mot de passe propriétaire. |
| privilege | DocumentPrivilege | Réinitialisez la sécurité. |
| keySize | KeySize | KeySize.x40 pour un cryptage 40 bits, KeySize.x128 pour un cryptage 128 bits et KeySize.x256 pour un cryptage 256 bits. |
| cipher | Algorithm | Algorithm.AES pour chiffrer à l'aide de l'algorithme AES ou Algorithm.RC4 pour le chiffrement RC4. |

### Return_Value

Vrai pour le succès, ou faux.

### Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; // Le TestPath peut être réaffecté.
string outFile = "D:\\output.pdf";	// Le TestPath peut être réaffecté.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Voir également

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesecurity)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
