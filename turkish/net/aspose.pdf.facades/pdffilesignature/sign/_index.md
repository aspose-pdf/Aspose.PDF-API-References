---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature metodu. PDF belgesine imza atın
type: docs
weight: 300
url: /tr/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

PDF belgesine imza atın.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Int32 | İmzanın atıldığı sayfa numarası. |
| SigReason | String | İmza nedeni. |
| SigContact | String | İmza iletişimi. |
| SigLocation | String | İmza yeri. |
| visible | Boolean | İmzanın görünürlüğü. |
| annotRect | Rectangle | İmzanın dikdörtgeni. |

## Örnekler

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

### Ayrıca Bakınız

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Belirtilen türde imza ile belgeyi imzalayın.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Int32 | İmzanın atıldığı sayfa numarası. |
| SigReason | String | İmza nedeni. |
| SigContact | String | İmza iletişimi. |
| SigLocation | String | İmza yeri. |
| visible | Boolean | İmzanın görünürlüğü. |
| annotRect | Rectangle | İmzanın dikdörtgeni. |
| sig | Signature | İmzanın türü, PKCS1, PKCS7 ve PKCS7Detached olabilir. |

## Örnekler

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

### Ayrıca Bakınız

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Belirtilen türde imza ile belgeyi imzalayın.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Int32 | İmzanın atıldığı sayfa numarası. |
| visible | Boolean | İmzanın görünürlüğü. |
| annotRect | Rectangle | İmzanın dikdörtgeni. |
| sig | Signature | İmzanın türü, PKCS1, PKCS7 ve PKCS7Detached olabilir. İmza nedeni, iletişim ve yer gibi veriler bu nesnede zaten mevcut olmalıdır (ilgili özelliklere bakın). |

## Örnekler

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

### Ayrıca Bakınız

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Belirtilen türde imza ile belgeyi imzalayın, bu imza zaten mevcut olan imza alanına yerleştirilmiştir. İmza atmadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Böylece PDF belgesi zaten imza alanına sahiptir, imzayı damgalamak için yeri sağlamanız gerekmez, ilgili sayfa ve dikdörtgen imza adı ile bulunan imza alanından alınır (bkz. SigName parametresi).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| SigName | String | İmza alanının adı. |
| SigReason | String | İmza nedeni. |
| SigContact | String | İmza iletişimi. |
| SigLocation | String | İmza yeri. |
| sig | Signature | İmzanın türü, PKCS1, PKCS7 ve PKCS7Detached olabilir. |

## Örnekler

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

### Ayrıca Bakınız

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Belirtilen türde imza ile belgeyi imzalayın, bu imza zaten mevcut olan imza alanına yerleştirilmiştir. İmza atmadan önce PDF belgesinin zaten imza alanına sahip olması gerekir, ilgili sayfa ve dikdörtgen imza adı ile bulunan imza alanından alınır (bkz. SigName parametresi).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Int32 | İmzanın atıldığı sayfa numarası. |
| SigName | String | İmza alanının adı. |
| SigReason | String | İmza nedeni. |
| SigContact | String | İmza iletişimi. |
| SigLocation | String | İmza yeri. |
| visible | Boolean | İmzanın görünürlüğü. |
| annotRect | Rectangle | İmzanın dikdörtgeni. |
| sig | Signature | İmzanın türü, PKCS1, PKCS7 ve PKCS7Detached olabilir. |

## Örnekler

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

### Ayrıca Bakınız

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Belirtilen türde imza ile belgeyi imzalayın, bu imza zaten mevcut olan imza alanına yerleştirilmiştir. İmza atmadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Böylece PDF belgesi zaten imza alanına sahiptir, imzayı damgalamak için yeri sağlamanız gerekmez, ilgili sayfa ve dikdörtgen imza adı ile bulunan imza alanından alınır (bkz. SigName parametresi). İmza nedeni, iletişim ve yer gibi veriler, Signature nesnesinin sig ile ilgili özellikleri tarafından sağlanmalıdır.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| SigName | String | İmza alanının adı. |
| sig | Signature | İmzanın türü, PKCS1 (Pkcs1Signature nesnesi), PKCS7 ve PKCS7 detached (Pkcs7Signature nesnesi) olabilir. |

## Örnekler

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

### Ayrıca Bakınız

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)