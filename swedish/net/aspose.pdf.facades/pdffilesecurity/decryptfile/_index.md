---
title: "PdfFileSecurity.DecryptFile"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSecurity‑metod. Dekrypterar ett krypterat Pdf‑dokument med ägarlösenordet. Om dokumentet saknar ägarlösenord tillåts användning av användarlösenordet. Kastar ett undantag om processen misslyckas."
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

Dekrypterar ett krypterat Pdf‑dokument med ägarlösenord. Om dokumentet saknar ägarlösenord tillåts användning av användarlösenord. Kastar ett undantag om processen misslyckas.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ägarlösenord. |

### Returvärde

Sant för framgång.

## Exempel

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

### Se även

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


