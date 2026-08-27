---
title: "PdfFileSecurity.TryDecryptFile"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileSecurity. Déchiffre un document Pdf chiffré avec le mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est possible d'utiliser le mot de passe utilisateur. Ne lève pas d'exception si le processus échoue."
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile method

Déchiffre un document Pdf chiffré avec le mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est possible d'utiliser le mot de passe utilisateur. Ne lève pas d'exception si le processus échoue.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ownerPassword | String | Mot de passe du propriétaire. |

### Valeur de retour

Vrai en cas de succès, ou faux.

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

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


