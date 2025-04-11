---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-metod. Dekrypterar ett krypterat Pdf-dokument med ägarens lösenord. Om dokumentet inte har ägarens lösenord är det tillåtet att använda användarens lösenord. Kastar inte ett undantag om processen misslyckas
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile metod

Dekrypterar ett krypterat Pdf-dokument med ägarens lösenord. Om dokumentet inte har ägarens lösenord, är det tillåtet att använda användarens lösenord. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | Sträng | Ägarens lösenord. |

### Returvärde

Sant för framgång, eller falskt.

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

### Se Även

* klass [PdfFileSecurity](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)