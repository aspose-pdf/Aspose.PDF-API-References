---
title: "PdfFileSecurity.TryDecryptFile"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSecurity‑metod. Dekrypterar ett krypterat Pdf‑dokument med ägarlösenordet. Om dokumentet saknar ägarlösenord tillåts användning av användarlösenordet. Kastar inte ett undantag om processen misslyckas."
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile method

Dekrypterar ett krypterat Pdf‑dokument med ägarlösenord. Om dokumentet inte har ägarlösenord tillåts användning av användarlösenord. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ägarlösenord. |

### Returvärde

Sant för lyckat, eller falskt.

## Exempel

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

### Se även

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


