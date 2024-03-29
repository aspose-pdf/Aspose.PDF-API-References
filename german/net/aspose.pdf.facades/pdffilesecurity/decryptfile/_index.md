---
title: DecryptFile
second_title: Aspose.PDF für .NET-API-Referenz
description: Entschlüsselt ein verschlüsseltes PDF-Dokument nach Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat darf es das Benutzerpasswort verwenden. Löst eine Ausnahme aus wenn der Prozess fehlgeschlagen ist.
type: docs
weight: 60
url: /de/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

Entschlüsselt ein verschlüsseltes PDF-Dokument nach Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, darf es das Benutzerpasswort verwenden. Löst eine Ausnahme aus, wenn der Prozess fehlgeschlagen ist.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Besitzer-Passwort. |

### Rückgabewert

Wahr für den Erfolg.

### Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden.
string outFile = "D:\\output.pdf"; //Der TestPath kann neu zugewiesen werden.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### Siehe auch

* class [PdfFileSecurity](../../pdffilesecurity)
* namensraum [Aspose.Pdf.Facades](../../pdffilesecurity)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
