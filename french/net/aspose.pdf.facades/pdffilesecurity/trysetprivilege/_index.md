---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSecurity. Définit la sécurité du fichier Pdf avec le mot de passe d'origine. Ne lance pas d'exception si le processus échoue
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## Méthode PdfFileSecurity.TrySetPrivilege

Définit la sécurité du fichier Pdf avec le mot de passe d'origine. Ne lance pas d'exception si le processus échoue.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur d'origine. |
| ownerPassword | String | Mot de passe propriétaire d'origine. |
| privilege | DocumentPrivilege | Définir le privilège. |

### Valeur de retour

Vrai pour le succès, ou faux.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Voir aussi

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)