---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSecurity. Décrypte un document Pdf chiffré par mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est permis d'utiliser le mot de passe utilisateur. Lance une exception si le processus échoue.
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## Méthode PdfFileSecurity.DecryptFile

Décrypte un document Pdf chiffré par mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est permis d'utiliser le mot de passe utilisateur. Lance une exception si le processus échoue.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe propriétaire. |

### Valeur de retour

Vrai pour succès.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### Voir aussi

* classe [PdfFileSecurity](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)