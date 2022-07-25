---
title: TryChangePassword
second_title: Aspose.PDF för .NET API Referens
description: Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas Ger inget undantag om processen misslyckades. med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt.
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas Ger inget undantag om processen misslyckades. med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Original ägarlösenord. |
| newUserPassword | String | Nytt användarlösenord. |
| newOwnerPassword | String | Nytt ägarlösenord. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //TestPath kan tilldelas om.
 string outFile = "D:\\output.pdf";	//TestPath kan tilldelas om.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Se även

* class [PdfFileSecurity](../../pdffilesecurity)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesecurity)
* hopsättning [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Ändrar användarlösenordet och lösenordet med ägarlösenordet, gör det möjligt att återställa Pdf-dokumentsäkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Ger inget undantag om processen misslyckades.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ursprungligt ägarlösenord. |
| newUserPassword | String | Nytt användarlösenord. |
| newOwnerPassword | String | Nytt ägarlösenord. |
| privilege | DocumentPrivilege | Återställ säkerheten. |
| keySize | KeySize | KeySize.x40 för 40 bitars kryptering, KeySize.x128 för 128 bitars kryptering och KeySize.x256 för 256 bitars kryptering. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //TestPath kan tilldelas om.
string outFile = "D:\\output.pdf";	//TestPath kan tilldelas om.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Se även

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesecurity)
* hopsättning [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Ändrar användarlösenordet och lösenordet med ägarlösenordet, gör det möjligt att återställa Pdf-dokumentsäkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize och Algoritmvärden. Emellertid (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) är ogiltiga och motsvarande undantag kommer att höjas om kitet stöter på denna kombination. Ger inget undantag om processen misslyckades._x0000

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | String | Ursprungligt ägarlösenord. |
| newUserPassword | String | Nytt användarlösenord. |
| newOwnerPassword | String | Nytt ägarlösenord. |
| privilege | DocumentPrivilege | Återställ säkerheten. |
| keySize | KeySize | KeySize.x40 för 40 bitars kryptering, KeySize.x128 för 128 bitars kryptering och KeySize.x256 för 256 bitars kryptering. |
| cipher | Algorithm | Algorithm.AES för att kryptera med AES-algoritm eller Algorithm.RC4 för RC4-kryptering. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
[C#]
string inFile = "D:\\input.pdf"; //TestPath kan tilldelas om.
string outFile = "D:\\output.pdf";	//TestPath kan tilldelas om.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Se även

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesecurity)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
