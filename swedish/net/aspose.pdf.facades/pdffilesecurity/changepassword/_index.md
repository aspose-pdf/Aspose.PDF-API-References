---
title: "PdfFileSecurity.ChangePassword"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSecurity-metoden. Ändrar användarlösenordet och ägarlösenordet, där ägarlösenordet behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas."
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ursprungligt ägarlösenord. |
| newUserPassword | String | Nytt användarlösenord. |
| newOwnerPassword | String | Nytt ägarlösenord. |

### Returvärde

Sant för framgång.

## Exempel

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### Se även

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf‑dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ursprungligt ägarlösenord. |
| newUserPassword | String | Nytt användarlösenord. |
| newOwnerPassword | String | Nytt ägarlösenord. |
| behörighet | DocumentPrivilege | Återställ säkerhet. |
| keySize | KeySize | KeySize.x40 för 40‑bits kryptering, KeySize.x128 för 128‑bits kryptering och KeySize.x256 för 256‑bits kryptering. |

### Returvärde

Sant för framgång.

## Exempel

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Se även

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf‑dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize‑ och Algorithm‑värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar ett undantag om processen misslyckas.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ursprungligt ägarlösenord. |
| newUserPassword | String | Nytt användarlösenord. |
| newOwnerPassword | String | Nytt ägarlösenord. |
| behörighet | DocumentPrivilege | Återställ säkerhet. |
| keySize | KeySize | KeySize.x40 för 40‑bits kryptering, KeySize.x128 för 128‑bits kryptering och KeySize.x256 för 256‑bits kryptering. |
| chiffer | Algoritm | Algorithm.AES för att kryptera med AES‑algoritmen eller Algorithm.RC4 för RC4‑kryptering. |

### Returvärde

Sant för framgång.

## Exempel

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Se även

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


