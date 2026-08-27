---
title: "PdfFileSecurity.SetPrivilege"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSecurity‑metod. Ställer in PDF‑filens säkerhet med tomma användar‑/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas"
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Ställer in Pdf‑filens säkerhet med tomma användar‑/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| behörighet | DocumentPrivilege | Ange behörighet. |

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

### Se även

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Ställer in Pdf‑filens säkerhet med originallösenordet. Kastar ett undantag om processen misslyckas.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Ursprungligt användarlösenord. |
| ownerPassword | String | Ursprungligt ägarlösenord. |
| behörighet | DocumentPrivilege | Ange behörighet. |

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

### Se även

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


