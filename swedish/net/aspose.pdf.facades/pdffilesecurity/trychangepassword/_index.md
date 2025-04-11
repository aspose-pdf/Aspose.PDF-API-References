---
title: PdfFileSecurity.TryChangePassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-metod. Ändrar användarlösenordet och ägarens lösenord genom att ägarens lösenord behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas. Kastar inte ett undantag om processen misslyckas. med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Ändrar användarlösenordet och ägarens lösenord genom att ägarens lösenord behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas. Kastar inte ett undantag om processen misslyckas. med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | Sträng | Ursprungligt ägarens lösenord. |
| newUserPassword | Sträng | Nytt användarlösenord. |
| newOwnerPassword | Sträng | Nytt ägarens lösenord. |

### Returvärde

Sant för framgång, eller falskt.

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

### Se Även

* klass [PdfFileSecurity](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Ändrar användarlösenordet och lösenordet genom att ägarens lösenord, tillåter att återställa Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | Sträng | Ursprungligt ägarens lösenord. |
| newUserPassword | Sträng | Nytt användarlösenord. |
| newOwnerPassword | Sträng | Nytt ägarens lösenord. |
| privilege | DocumentPrivilege | Återställ säkerhet. |
| keySize | KeySize | KeySize.x40 för 40 bits kryptering, KeySize.x128 för 128 bits kryptering och KeySize.x256 för 256 bits kryptering. |

### Returvärde

Sant för framgång, eller falskt.

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

### Se Även

* klass [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* klass [PdfFileSecurity](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Ändrar användarlösenordet och lösenordet genom att ägarens lösenord, tillåter att återställa Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt. Det finns 6 möjliga kombinationer av KeySize och Algorithm-värden. Men (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) är ogiltiga och motsvarande undantag kommer att uppstå om kit stöter på denna kombination. Kastar inte ett undantag om processen misslyckas.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ownerPassword | Sträng | Ursprungligt ägarens lösenord. |
| newUserPassword | Sträng | Nytt användarlösenord. |
| newOwnerPassword | Sträng | Nytt ägarens lösenord. |
| privilege | DocumentPrivilege | Återställ säkerhet. |
| keySize | KeySize | KeySize.x40 för 40 bits kryptering, KeySize.x128 för 128 bits kryptering och KeySize.x256 för 256 bits kryptering. |
| cipher | Algorithm | Algorithm.AES för att kryptera med AES-algoritmen eller Algorithm.RC4 för RC4-kryptering. |

### Returvärde

Sant för framgång, eller falskt.

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

### Se Även

* klass [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* klass [PdfFileSecurity](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)