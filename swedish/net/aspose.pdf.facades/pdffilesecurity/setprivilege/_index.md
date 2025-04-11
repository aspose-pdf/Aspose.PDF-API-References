---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-metod. Ställer in Pdf-filens säkerhet med tomma användar-/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Ställer in Pdf-filens säkerhet med tomma användar-/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| privilege | DocumentPrivilege | Ställ in privilegiet. |

### Returvärde

Sant för framgång.

## Exempel

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Se Även

* klass [DocumentPrivilege](../../documentprivilege/)
* klass [PdfFileSecurity](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Ställer in Pdf-filens säkerhet med originallösenord. Kastar ett undantag om processen misslyckas.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | Sträng | Originalanvändarlösenord. |
| ownerPassword | Sträng | Originalägarlösenord. |
| privilege | DocumentPrivilege | Ställ in privilegiet. |

### Returvärde

Sant för framgång.

## Exempel

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Se Även

* klass [DocumentPrivilege](../../documentprivilege/)
* klass [PdfFileSecurity](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)