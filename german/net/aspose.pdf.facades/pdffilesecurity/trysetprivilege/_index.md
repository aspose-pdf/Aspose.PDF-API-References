---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-Methode. Setzt die Pdf-Dateisicherheit mit dem ursprünglichen Passwort. Wirft keine Ausnahme, wenn der Prozess fehlschlägt
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege-Methode

Setzt die Pdf-Dateisicherheit mit dem ursprünglichen Passwort. Wirft keine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Ursprüngliches Benutzerpasswort. |
| ownerPassword | String | Ursprüngliches Besitzerpasswort. |
| privilege | DocumentPrivilege | Setze Berechtigung. |

### Rückgabewert

True bei Erfolg, oder false.

## Beispiele

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

### Siehe auch

* Klasse [DocumentPrivilege](../../documentprivilege/)
* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)