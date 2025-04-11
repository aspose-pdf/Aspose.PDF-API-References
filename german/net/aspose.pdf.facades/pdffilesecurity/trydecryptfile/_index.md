---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-Methode. Entschlüsselt ein verschlüsseltes Pdf-Dokument mit dem Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, ist es erlaubt, das Benutzerpasswort zu verwenden. Wirft keine Ausnahme, wenn der Prozess fehlschlägt.
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile-Methode

Entschlüsselt ein verschlüsseltes Pdf-Dokument mit dem Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, ist es erlaubt, das Benutzerpasswort zu verwenden. Wirft keine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Besitzerpasswort. |

### Rückgabewert

True bei Erfolg, oder false.

## Beispiele

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

### Siehe auch

* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)