---
title: "PdfFileSignature.Sign"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSignature-metoden. Skapar en signatur på pdf-dokumentet"
type: docs
weight: 300
url: /sv/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Skapa en signatur i pdf Document.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Sidnumret där signaturen görs. |
| SigReason | String | Anledningen till signaturen. |
| SigContact | String | Kontakt för signaturen. |
| SigLocation | String | Plats för signaturen. |
| synlig | Boolean | Synligheten för signaturen. |
| annotRect | Rectangle | Rektangeln för signaturen. |

## Exempel

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

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Signera dokumentet med den angivna typens signatur.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Sidnumret där signaturen görs. |
| SigReason | String | Anledningen till signaturen. |
| SigContact | String | Kontakt för signaturen. |
| SigLocation | String | Plats för signaturen. |
| synlig | Boolean | Synligheten för signaturen. |
| annotRect | Rectangle | Rektangeln för signaturen. |
| sig | Signatur | Typen av signaturen, kan vara PKCS1, PKCS7 och PKCS7Detached. |

## Exempel

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

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Signera dokumentet med den angivna typens signatur.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Sidnumret där signaturen görs. |
| synlig | Boolean | Synligheten för signaturen. |
| annotRect | Rectangle | Rektangeln för signaturen. |
| sig | Signatur | Typen av signaturen, kan vara PKCS1, PKCS7 och PKCS7Detached. Sådana data som signaturorsak, kontakt och plats måste redan finnas i detta objekt (se motsvarande egenskaper). |

## Exempel

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

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs. fältet får inte innehålla en signaturdictionary. Således har pdf Document redan ett signaturfält, du ska inte ange platsen för att stämpla signaturen, motsvarande **Page** och **Rectangle** tas från signaturfältet som hittas via signaturnamnet (se SigName‑parameter).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| SigName | String | Namnet på signaturfältet. |
| SigReason | String | Anledningen till signaturen. |
| SigContact | String | Kontakt för signaturen. |
| SigLocation | String | Plats för signaturen. |
| sig | Signatur | Typen av signaturen, kan vara PKCS1, PKCS7 och PKCS7Detached. |

## Exempel

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

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Innan signering bör pdf Document redan ha ett signaturfält, motsvarande **Page** och **Rectangle** tas från signaturfältet som hittas via signaturnamnet (se SigName‑parameter).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Sidnumret där signaturen görs. |
| SigName | String | Namnet på signaturfältet. |
| SigReason | String | Anledningen till signaturen. |
| SigContact | String | Kontakt för signaturen. |
| SigLocation | String | Plats för signaturen. |
| synlig | Boolean | Synligheten för signaturen. |
| annotRect | Rectangle | Rektangeln för signaturen. |
| sig | Signatur | Typen av signaturen, kan vara PKCS1, PKCS7 och PKCS7Detached. |

## Exempel

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

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs. fältet får inte innehålla en signaturdictionary. Således har pdf Document redan ett signaturfält, du ska inte ange platsen för att stämpla signaturen, motsvarande **Page** och **Rectangle** tas från signaturfältet som hittas via signaturnamnet (se SigName‑parameter). Sådana data som signaturens anledning, kontakt och plats måste tillhandahållas av motsvarande egenskaper i Signature‑objektet sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| SigName | String | Namnet på signaturfältet. |
| sig | Signatur | Typen av signaturen, kan vara PKCS1 (Pkcs1Signature-objekt), PKCS7 och PKCS7 detached (Pkcs7Signature-objekt) |

## Exempel

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

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


