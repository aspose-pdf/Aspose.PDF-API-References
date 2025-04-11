---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-Methode. Entschlüsselt ein verschlüsseltes Pdf-Dokument mit dem Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, ist es erlaubt, das Benutzerpasswort zu verwenden. Wirft eine Ausnahme, wenn der Prozess fehlschlägt.
type: docs
weight: 60
url: /de/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile-Methode

Entschlüsselt ein verschlüsseltes Pdf-Dokument mit dem Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, ist es erlaubt, das Benutzerpasswort zu verwenden. Wirft eine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Besitzerpasswort. |

### Rückgabewert

True bei Erfolg.

## Beispiele

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

### Siehe auch

* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)