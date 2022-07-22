---
title: Sign
second_title: Aspose.PDF för .NET API Referens
description: Gör en signatur på pdf-dokumentet.
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Gör en signatur på pdf-dokumentet.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Sidnumret som signaturen görs på. |
| SigReason | String | Anledningen till underskrift. |
| SigContact | String | Underskriftskontakten. |
| SigLocation | String | Platsen för signaturen. |
| visible | Boolean | Signaturens synlighet. |
| annotRect | Rectangle | Signaturen. |

### Exempel

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PdfFileSignature pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile);
System.Drawing.Rectangle rect = new System.Drawing.Rectangle(100, 100, 200, 200);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.SetCertificate("certificate.pfx", "password");
pdfSign.Sign(2, "Allen", "success", "ChangSha", true, rect);
pdfSign.Save(outFile);

[Visual Basic]
Dim pdfSign = new PdfFileSignature()
pdfSign.BindPdf(inFile)
Dim rect as System.Drawing.Rectangle = new System.Drawing.Rectangle(100, 100, 200, 200)
pdfSign.SetCertificate("certificate.pfx", "password")
pdfSign.Sign(2, "Allen", "success", "ChangSha", true, rect)
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg"
pdfSign.Save(outFile)
```

### Se även

* class [PdfFileSignature](../../pdffilesignature)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesignature)
* hopsättning [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Signera dokumentet med den angivna typen signatur.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Sidnumret som signaturen görs på. |
| SigReason | String | Anledningen till underskrift. |
| SigContact | String | Underskriftskontakten. |
| SigLocation | String | Platsen för signaturen. |
| visible | Boolean | Signaturens synlighet. |
| annotRect | Rectangle | Signaturen. |
| sig | Signature | Typen av signatur kan vara PKCS1, PKCS7 och PKCS7Detached. |

### Exempel

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
System.Drawing.Rectangle rect = new System.Drawing.Rectangle(100, 100, 200, 100);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.Sign(2, "Allen", "success", "ChangSha", true, rect, new PKCS1("certificate.pfx", "password"));
pdfSign.Save();

[Visual Basic]
Dim inFile As String = TestPath & "example1.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS1 = new PKCS1("certificate.pfx", "password")
Dim pdfSign = new PdfFileSignature(inFile, outFile)
Dim rect as System.Drawing.Rectangle = new System.Drawing.Rectangle(100, 100, 200, 100)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign(2, "Allen", "success", "ChangSha", true, rect, sig)
pdfSign.Save()
```

### Se även

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesignature)
* hopsättning [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Signera dokumentet med den angivna typen signatur.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Sidnumret som signaturen görs på. |
| visible | Boolean | Signaturens synlighet. |
| annotRect | Rectangle | Signaturen. |
| sig | Signature | Typen av signatur kan vara PKCS1, PKCS7 och PKCS7Detached. Sådana data som signaturorsak, kontakt och plats måste redan finnas i detta objekt (se motsvarande egenskaper). |

### Exempel

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PKCS1 sig = new PKCS1("certificate.pfx", "password");
sig.Reason = "Some reason";
sig.Contact = "Smith";
sig.Location = "New York";
PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
System.Drawing.Rectangle rect = new System.Drawing.Rectangle(100, 100, 200, 100);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.Sign(2, true, rect, sig);
pdfSign.Save();

[Visual Basic]
Dim inFile As String = TestPath & "example1.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS1 = new PKCS1("certificate.pfx", "password")
sig.Reason = "Some reason"
sig.Contact = "Smith"
sig.Location = "New York"
Dim pdfSign = new PdfFileSignature(inFile, outFile)
Dim rect as System.Drawing.Rectangle = new System.Drawing.Rectangle(100, 100, 200, 100)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign(2, true, rect, sig)
pdfSign.Save()
```

### Se även

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesignature)
* hopsättning [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Signera dokumentet med den givna typen signatur som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs fältet får inte innehålla signaturlexikon. Således pdf-dokument har redan signaturfält, du ska inte ange platsen för att stämpla signaturen tas motsvarande sida och rektangel från signaturfältet som hittas av signaturnamnet (se SigName parameter).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| SigName | String | Namnet på signaturfältet. |
| SigReason | String | Anledningen till underskrift. |
| SigContact | String | Underskriftskontakten. |
| SigLocation | String | Platsen för signaturen. |
| sig | Signature | Typen av signatur kan vara PKCS1, PKCS7 och PKCS7Detached. |

### Exempel

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PKCS1 sig = new PKCS1("certificate.pfx", "password");
PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.Sign("Signature1", "Allen", "success", "ChangSha", sig);
pdfSign.Save();

[Visual Basic]
Dim inFile As String = TestPath & "example1.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS1 = new PKCS1("certificate.pfx", "password")
Dim pdfSign = new PdfFileSignature(inFile, outFile)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign("Signature1", "Allen", "success", "ChangSha", sig)
pdfSign.Save()
```

### Se även

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesignature)
* hopsättning [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Signera dokumentet med den givna typen signatur som placeras i redan presenterat signaturfält. Innan man signerar pdf-dokument bör man redan ha signaturfält, motsvarande sida och rektangel är hämtade från signaturfält som hittas av signaturnamn (se SigName parameter) .

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Sidnumret som signaturen görs på. |
| SigName | String | Namnet på signaturfältet. |
| SigReason | String | Anledningen till underskrift. |
| SigContact | String | Underskriftskontakten. |
| SigLocation | String | Platsen för signaturen. |
| visible | Boolean | Signaturens synlighet. |
| annotRect | Rectangle | Signaturen. |
| sig | Signature | Typen av signatur kan vara PKCS1, PKCS7 och PKCS7Detached. |

### Exempel

```csharp
[C#]
string inFile = TestPath + "blankWithSignature.pdf";
string outFile = TestPath + "signature.pdf";
PKCS7 sig = new PKCS7("certificate.pfx", "password");
PdfFileSignature pdfSign = new PdfFileSignature(inFile);
System.Drawing.Rectangle rect = new System.Drawing.Rectangle(100, 100, 100, 100);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg"
pdfSign.Sign(1, "Signature1", "ReasonToTest", "ContactMe", "SomeLocation", true, rect, sig);                
pdfSign.Save(outFile);                

[Visual Basic]
Dim inFile As String = TestPath & "blankWithSignature.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS7 = new PKCS7("certificate.pfx", "password")
Dim pdfSign = new PdfFileSignature(inFile, outFile)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign("Signature1",  "ReasonToTest", "ContactMe", "SomeLocation", true, rect, sig)
pdfSign.Save(outFile)
```

### Se även

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesignature)
* hopsättning [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Signera dokumentet med den givna typen signatur som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs fältet får inte innehålla signaturlexikon. Således pdf-dokument har redan signaturfält, du ska inte ange platsen för att stämpla signaturen tas motsvarande sida och rektangel från signaturfält som hittas av signaturnamn (se SigName parameter). Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper för Signaturobjektet sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| SigName | String | Namnet på signaturfältet. |
| sig | Signature | Typen av signatur kan vara PKCS1 (Pkcs1Signature-objekt), PKCS7 och PKCS7 fristående (Pkcs7Signature-objekt) |

### Exempel

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
string outFile = TestPath + "signature.pdf";
PKCS1 sig = new PKCS1("certificate.pfx", "password");
sig.Reason = "Some reason";
sig.Contact = "Smith";
sig.Location = "New York";
PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
pdfSign.SignatureAppearance = TestPath + "butterfly.jpg";
pdfSign.Sign("Signature1", sig);
pdfSign.Save();

[Visual Basic]
Dim inFile As String = TestPath & "example1.pdf"
Dim outFile As String = TestPath & "signature.pdf"
Dim sig As PKCS1 = new PKCS1("certificate.pfx", "password")
sig.Reason = "Some reason"
sig.Contact = "Smith"
sig.Location = "New York"
Dim pdfSign = new PdfFileSignature(inFile, outFile)
pdfSign.SignatureAppearance = TestPath & "butterfly.jpg"
pdfSign.Sign("Signature1", sig)
pdfSign.Save()
```

### Se även

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilesignature)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
