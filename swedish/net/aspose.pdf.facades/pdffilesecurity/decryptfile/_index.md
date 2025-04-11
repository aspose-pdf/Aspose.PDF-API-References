---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-metod. Avkrypterar ett krypterat Pdf-dokument med ägarens lösenord. Om dokumentet inte har ägarens lösenord är det tillåtet att använda användarens lösenord. Kastar ett undantag om processen misslyckas
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile metod

Avkrypterar ett krypterat Pdf-dokument med ägarens lösenord. Om dokumentet inte har ägarens lösenord, är det tillåtet att använda användarens lösenord. Kastar ett undantag om processen misslyckas.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | Sträng | Ägarens lösenord. |

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

### Se Även

* klass [PdfFileSecurity](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)