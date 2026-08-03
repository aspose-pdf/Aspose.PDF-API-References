---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSecurity-metoden. Krypterar Pdf-filen med användarlösenord och ägarlösenord och sätter dokumentets åtkomsträttigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas."
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

Krypterar Pdf‑fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Användarlösenord. |
| ownerPassword | String | Ägarlösenord. |
| behörighet | DocumentPrivilege | Ange behörighet. |
| keySize | KeySize | KeySize.x40 för 40‑bits kryptering, KeySize.x128 för 128‑bits kryptering och KeySize.x256 för 256‑bits kryptering. |

### Returvärde

Sant för framgång, annars falskt.

## Exempel

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Se även

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


