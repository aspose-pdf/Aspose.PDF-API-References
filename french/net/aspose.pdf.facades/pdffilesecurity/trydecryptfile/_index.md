---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSecurity. Décrypte un document Pdf chiffré par mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est permis d'utiliser le mot de passe utilisateur. Ne lance pas d'exception si le processus échoue.
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## Méthode PdfFileSecurity.TryDecryptFile

Décrypte un document Pdf chiffré par mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est permis d'utiliser le mot de passe utilisateur. Ne lance pas d'exception si le processus échoue.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe propriétaire. |

### Valeur de retour

Vrai pour succès, ou faux.

## Exemples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### Voir aussi

* classe [PdfFileSecurity](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)