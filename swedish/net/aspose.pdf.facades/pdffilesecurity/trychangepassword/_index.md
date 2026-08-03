---
title: "PdfFileSecurity.TryChangePassword"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSecurity‑metod. Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet och behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas."
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ursprungligt ägarlösenord. |
| newUserPassword | String | Nytt användarlösenord. |
| newOwnerPassword | String | Nytt ägarlösenord. |

### Returvärde

Sant för lyckat, eller falskt.

## Exempel

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Se även

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf‑dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ursprungligt ägarlösenord. |
| newUserPassword | String | Nytt användarlösenord. |
| newOwnerPassword | String | Nytt ägarlösenord. |
| behörighet | DocumentPrivilege | Återställ säkerhet. |
| keySize | KeySize | KeySize.x40 för 40‑bits kryptering, KeySize.x128 för 128‑bits kryptering och KeySize.x256 för 256‑bits kryptering. |

### Returvärde

Sant för framgång, annars falskt.

## Exempel

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Se även

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf‑dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize‑ och Algorithm‑värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
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

Sant för framgång, annars falskt.

## Exempel

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Se även

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


