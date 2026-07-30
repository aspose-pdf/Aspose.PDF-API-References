---
title: "PdfFileSecurity.SetPrivilege"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileSecurity. Définit la sécurité du fichier Pdf avec des mots de passe utilisateur/propriétaire vides. Le mot de passe propriétaire sera ajouté par une chaîne aléatoire. Lève une exception si le processus échoue"
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Définit la sécurité du fichier Pdf avec des mots de passe utilisateur/propriétaire vides. Le mot de passe propriétaire sera ajouté sous forme d'une chaîne aléatoire. Lève une exception si le processus échoue.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| privilège | DocumentPrivilege | Définir le privilège. |

### Valeur de retour

Vrai pour le succès.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Voir aussi

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Définit la sécurité du fichier Pdf avec le mot de passe original. Lève une exception si le processus échoue.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur original. |
| ownerPassword | String | Mot de passe propriétaire original. |
| privilège | DocumentPrivilege | Définir le privilège. |

### Valeur de retour

Vrai pour le succès.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Voir aussi

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


