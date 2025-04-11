---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature-Methode. Erstellen Sie eine Unterschrift im PDF-Dokument
type: docs
weight: 300
url: /de/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Erstellen Sie eine Unterschrift im PDF-Dokument.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seitenzahl, auf der die Unterschrift erstellt wird. |
| SigReason | String | Der Grund für die Unterschrift. |
| SigContact | String | Der Kontakt der Unterschrift. |
| SigLocation | String | Der Standort der Unterschrift. |
| visible | Boolean | Die Sichtbarkeit der Unterschrift. |
| annotRect | Rectangle | Das Rechteck der Unterschrift. |

## Beispiele

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

* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Unterzeichnen Sie das Dokument mit der angegebenen Typunterschrift.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seitenzahl, auf der die Unterschrift erstellt wird. |
| SigReason | String | Der Grund für die Unterschrift. |
| SigContact | String | Der Kontakt der Unterschrift. |
| SigLocation | String | Der Standort der Unterschrift. |
| visible | Boolean | Die Sichtbarkeit der Unterschrift. |
| annotRect | Rectangle | Das Rechteck der Unterschrift. |
| sig | Signature | Der Typ der Unterschrift, könnte PKCS1, PKCS7 und PKCS7Detached sein. |

## Beispiele

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

* Klasse [Signature](../../../aspose.pdf.forms/signature/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Unterzeichnen Sie das Dokument mit der angegebenen Typunterschrift.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seitenzahl, auf der die Unterschrift erstellt wird. |
| visible | Boolean | Die Sichtbarkeit der Unterschrift. |
| annotRect | Rectangle | Das Rechteck der Unterschrift. |
| sig | Signature | Der Typ der Unterschrift, könnte PKCS1, PKCS7 und PKCS7Detached sein. Solche Daten wie Unterschriftsgrund, Kontakt und Standort müssen bereits in diesem Objekt vorhanden sein (siehe entsprechende Eigenschaften). |

## Beispiele

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

* Klasse [Signature](../../../aspose.pdf.forms/signature/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Unterzeichnen Sie das Dokument mit der angegebenen Typunterschrift, die im bereits vorhandenen Unterschriftsfeld platziert ist. Vor der Unterzeichnung muss das Unterschriftsfeld leer sein, d.h. das Feld darf kein Unterschriftswörterbuch enthalten. Da das PDF-Dokument bereits ein Unterschriftsfeld hat, sollten Sie nicht den Platz für die Unterschrift angeben, die entsprechende Seite und das Rechteck werden aus dem Unterschriftsfeld entnommen, das durch den Unterschriftsnamen gefunden wird (siehe SigName-Parameter).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| SigName | String | Der Name des Unterschriftsfeldes. |
| SigReason | String | Der Grund für die Unterschrift. |
| SigContact | String | Der Kontakt der Unterschrift. |
| SigLocation | String | Der Standort der Unterschrift. |
| sig | Signature | Der Typ der Unterschrift, könnte PKCS1, PKCS7 und PKCS7Detached sein. |

## Beispiele

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

* Klasse [Signature](../../../aspose.pdf.forms/signature/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Unterzeichnen Sie das Dokument mit der angegebenen Typunterschrift, die im bereits vorhandenen Unterschriftsfeld platziert ist. Vor der Unterzeichnung muss das PDF-Dokument bereits ein Unterschriftsfeld haben, die entsprechende Seite und das Rechteck werden aus dem Unterschriftsfeld entnommen, das durch den Unterschriftsnamen gefunden wird (siehe SigName-Parameter).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Seitenzahl, auf der die Unterschrift erstellt wird. |
| SigName | String | Der Name des Unterschriftsfeldes. |
| SigReason | String | Der Grund für die Unterschrift. |
| SigContact | String | Der Kontakt der Unterschrift. |
| SigLocation | String | Der Standort der Unterschrift. |
| visible | Boolean | Die Sichtbarkeit der Unterschrift. |
| annotRect | Rectangle | Das Rechteck der Unterschrift. |
| sig | Signature | Der Typ der Unterschrift, könnte PKCS1, PKCS7 und PKCS7Detached sein. |

## Beispiele

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

* Klasse [Signature](../../../aspose.pdf.forms/signature/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Unterzeichnen Sie das Dokument mit der angegebenen Typunterschrift, die im bereits vorhandenen Unterschriftsfeld platziert ist. Vor der Unterzeichnung muss das Unterschriftsfeld leer sein, d.h. das Feld darf kein Unterschriftswörterbuch enthalten. Da das PDF-Dokument bereits ein Unterschriftsfeld hat, sollten Sie nicht den Platz für die Unterschrift angeben, die entsprechende Seite und das Rechteck werden aus dem Unterschriftsfeld entnommen, das durch den Unterschriftsnamen gefunden wird (siehe SigName-Parameter). Solche Daten wie Unterschriftsgrund, Kontakt und Standort müssen durch die entsprechenden Eigenschaften des Signature-Objekts sig bereitgestellt werden.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| SigName | String | Der Name des Unterschriftsfeldes. |
| sig | Signature | Der Typ der Unterschrift, könnte PKCS1 (Pkcs1Signature-Objekt), PKCS7 und PKCS7 detached (Pkcs7Signature-Objekt) sein. |

## Beispiele

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

* Klasse [Signature](../../../aspose.pdf.forms/signature/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)