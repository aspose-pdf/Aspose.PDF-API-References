---
title: Sign
second_title: Aspose.PDF für .NET-API-Referenz
description: Unterschreiben Sie das PDF-Dokument.
type: docs
weight: 280
url: /de/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Unterschreiben Sie das PDF-Dokument.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seitenzahl, auf der die Unterschrift geleistet wird. |
| SigReason | String | Der Grund der Unterschrift. |
| SigContact | String | Der Kontakt der Unterschrift. |
| SigLocation | String | Der Ort der Signatur. |
| visible | Boolean | Die Sichtbarkeit der Unterschrift. |
| annotRect | Rectangle | Das Rechteck der Unterschrift. |

### Beispiele

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

### Siehe auch

* class [PdfFileSignature](../../pdffilesignature)
* namensraum [Aspose.Pdf.Facades](../../pdffilesignature)
* Montage [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Unterschreiben Sie das Dokument mit der angegebenen Typsignatur.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seitenzahl, auf der die Unterschrift geleistet wird. |
| SigReason | String | Der Grund der Unterschrift. |
| SigContact | String | Der Kontakt der Unterschrift. |
| SigLocation | String | Der Ort der Signatur. |
| visible | Boolean | Die Sichtbarkeit der Unterschrift. |
| annotRect | Rectangle | Das Rechteck der Unterschrift. |
| sig | Signature | Der Typ der Signatur könnte PKCS1, PKCS7 und PKCS7Detached sein. |

### Beispiele

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

### Siehe auch

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namensraum [Aspose.Pdf.Facades](../../pdffilesignature)
* Montage [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Unterschreiben Sie das Dokument mit der angegebenen Typsignatur.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seitenzahl, auf der die Unterschrift geleistet wird. |
| visible | Boolean | Die Sichtbarkeit der Unterschrift. |
| annotRect | Rectangle | Das Rechteck der Unterschrift. |
| sig | Signature | Die Art der Signatur, könnte PKCS1, PKCS7 und PKCS7Detached sein. Solche Daten wie Signaturgrund, Kontakt und Ort müssen bereits in diesem Objekt vorhanden sein (siehe entsprechende Eigenschaften). |

### Beispiele

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

### Siehe auch

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namensraum [Aspose.Pdf.Facades](../../pdffilesignature)
* Montage [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Unterschreiben Sie das Dokument mit der gegebenen Unterschriftsart, die in das bereits vorhandene Unterschriftsfeld eingefügt wird. Vor dem Unterschreiben muss das Unterschriftsfeld leer sein, dh das Feld darf kein Unterschriftswörterbuch enthalten. Damit das PDF-Dokument bereits ein Unterschriftsfeld hat, sollten Sie den Ort nicht angeben Um die Signatur zu stempeln, werden die entsprechende Seite und das entsprechende Rechteck aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe Parameter SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| SigName | String | Der Name des Signaturfelds. |
| SigReason | String | Der Grund der Unterschrift. |
| SigContact | String | Der Kontakt der Unterschrift. |
| SigLocation | String | Der Ort der Signatur. |
| sig | Signature | Der Typ der Signatur könnte PKCS1, PKCS7 und PKCS7Detached sein. |

### Beispiele

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

### Siehe auch

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namensraum [Aspose.Pdf.Facades](../../pdffilesignature)
* Montage [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Signieren Sie das Dokument mit der angegebenen Signatur, die in das bereits angezeigte Signaturfeld eingefügt wird. Vor dem Signieren des PDF-Dokuments sollte bereits ein Signaturfeld vorhanden sein. Die entsprechende Seite und das Rechteck werden aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe SigName-Parameter) .

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seitenzahl, auf der die Unterschrift geleistet wird. |
| SigName | String | Der Name des Signaturfelds. |
| SigReason | String | Der Grund der Unterschrift. |
| SigContact | String | Der Kontakt der Unterschrift. |
| SigLocation | String | Der Ort der Signatur. |
| visible | Boolean | Die Sichtbarkeit der Unterschrift. |
| annotRect | Rectangle | Das Rechteck der Unterschrift. |
| sig | Signature | Der Typ der Signatur könnte PKCS1, PKCS7 und PKCS7Detached sein. |

### Beispiele

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

### Siehe auch

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namensraum [Aspose.Pdf.Facades](../../pdffilesignature)
* Montage [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Unterschreiben Sie das Dokument mit der gegebenen Unterschriftsart, die in das bereits vorhandene Unterschriftsfeld eingefügt wird. Vor dem Unterschreiben muss das Unterschriftsfeld leer sein, dh das Feld darf kein Unterschriftswörterbuch enthalten. Damit das PDF-Dokument bereits ein Unterschriftsfeld hat, sollten Sie den Ort nicht angeben Um die Signatur zu stempeln, werden die entsprechende Seite und das entsprechende Rechteck aus dem Signaturfeld entnommen, das durch den Signaturnamen gefunden wird (siehe Parameter SigName). Solche Daten wie Signaturgrund, Kontakt und Ort müssen von entsprechenden Eigenschaften des Signaturobjekts sig. bereitgestellt werden.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| SigName | String | Der Name des Signaturfelds. |
| sig | Signature | Der Typ der Signatur könnte PKCS1 (Pkcs1Signature-Objekt), PKCS7 und PKCS7 Detached (Pkcs7Signature-Objekt) sein. |

### Beispiele

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

### Siehe auch

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* namensraum [Aspose.Pdf.Facades](../../pdffilesignature)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
