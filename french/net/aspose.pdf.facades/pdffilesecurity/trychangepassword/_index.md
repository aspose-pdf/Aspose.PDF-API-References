---
title: "PdfFileSecurity.TryChangePassword"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileSecurity. Modifie le mot de passe utilisateur et le mot de passe propriétaire; le mot de passe propriétaire conserve les paramètres de sécurité originaux. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lève pas d'exception si le processus échoue."
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Modifie le mot de passe utilisateur et le mot de passe propriétaire à l'aide du mot de passe propriétaire, conserve les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lève pas d'exception si le processus échoue.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe propriétaire original. |
| newUserPassword | String | Nouveau mot de passe utilisateur. |
| newOwnerPassword | String | Nouveau mot de passe propriétaire. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Voir aussi

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Modifie le mot de passe utilisateur et le mot de passe à l'aide du mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lève pas d'exception si le processus échoue.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe propriétaire original. |
| newUserPassword | String | Nouveau mot de passe utilisateur. |
| newOwnerPassword | String | Nouveau mot de passe propriétaire. |
| privilège | DocumentPrivilege | Réinitialiser la sécurité. |
| keySize | KeySize | KeySize.x40 pour le chiffrement 40 bits, KeySize.x128 pour le chiffrement 128 bits et KeySize.x256 pour le chiffrement 256 bits. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Voir aussi

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Modifie le mot de passe utilisateur et le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante sera levée si le kit rencontre cette combinaison. Ne lève pas d'exception si le processus échoue.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe propriétaire original. |
| newUserPassword | String | Nouveau mot de passe utilisateur. |
| newOwnerPassword | String | Nouveau mot de passe propriétaire. |
| privilège | DocumentPrivilege | Réinitialiser la sécurité. |
| keySize | KeySize | KeySize.x40 pour le chiffrement 40 bits, KeySize.x128 pour le chiffrement 128 bits et KeySize.x256 pour le chiffrement 256 bits. |
| cipher | Algorithm | Algorithm.AES pour chiffrer en utilisant l'algorithme AES ou Algorithm.RC4 pour le chiffrement RC4. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Voir aussi

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


