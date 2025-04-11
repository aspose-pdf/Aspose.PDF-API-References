---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSecurity. Définit la sécurité du fichier Pdf avec des mots de passe utilisateur/propriétaire vides. Le mot de passe propriétaire sera ajouté par une chaîne aléatoire. Lance une exception si le processus échoue.
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Définit la sécurité du fichier Pdf avec des mots de passe utilisateur/propriétaire vides. Le mot de passe propriétaire sera ajouté par une chaîne aléatoire. Lance une exception si le processus échoue.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| privilege | DocumentPrivilege | Définir le privilège. |

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

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Définit la sécurité du fichier Pdf avec le mot de passe d'origine. Lance une exception si le processus échoue.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur d'origine. |
| ownerPassword | String | Mot de passe propriétaire d'origine. |
| privilege | DocumentPrivilege | Définir le privilège. |

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

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)