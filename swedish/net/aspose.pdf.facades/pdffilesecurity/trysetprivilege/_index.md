---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-metod. Ställer in Pdf-filens säkerhet med originallösenord. Kastar inte ett undantag om processen misslyckas
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege metod

Ställer in Pdf-filens säkerhet med originallösenord. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | Sträng | Originalanvändarlösenord. |
| ownerPassword | Sträng | Originalägarlösenord. |
| privilege | DocumentPrivilege | Ställ in privilegiet. |

### Returvärde

Sant för framgång, eller falskt.

## Exempel

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

### Se Även

* klass [DocumentPrivilege](../../documentprivilege/)
* klass [PdfFileSecurity](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)