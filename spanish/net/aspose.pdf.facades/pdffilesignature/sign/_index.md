---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSignature. Hacer una firma en el documento pdf
type: docs
weight: 300
url: /es/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Hacer una firma en el documento pdf.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | El número de página en la que se realiza la firma. |
| SigReason | String | La razón de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El rectángulo de la firma. |

## Ejemplos

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

### Ver También

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Firmar el documento con el tipo de firma dado.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | El número de página en la que se realiza la firma. |
| SigReason | String | La razón de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El rectángulo de la firma. |
| sig | Signature | El tipo de la firma, puede ser PKCS1, PKCS7 y PKCS7Detached. |

## Ejemplos

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

### Ver También

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Firmar el documento con el tipo de firma dado.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | El número de página en la que se realiza la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El rectángulo de la firma. |
| sig | Signature | El tipo de la firma, puede ser PKCS1, PKCS7 y PKCS7Detached. Los datos como la razón de la firma, contacto y ubicación deben estar ya presentes en este objeto (ver propiedades correspondientes). |

## Ejemplos

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

### Ver También

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Firmar el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Así, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| SigName | String | El nombre del campo de firma. |
| SigReason | String | La razón de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| sig | Signature | El tipo de la firma, puede ser PKCS1, PKCS7 y PKCS7Detached. |

## Ejemplos

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

### Ver También

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Firmar el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el documento pdf ya debe tener un campo de firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | El número de página en la que se realiza la firma. |
| SigName | String | El nombre del campo de firma. |
| SigReason | String | La razón de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El rectángulo de la firma. |
| sig | Signature | El tipo de la firma, puede ser PKCS1, PKCS7 y PKCS7Detached. |

## Ejemplos

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

### Ver También

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Firmar el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Así, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). Los datos como la razón de la firma, contacto y ubicación deben ser proporcionados por las propiedades correspondientes del objeto Signature sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| SigName | String | El nombre del campo de firma. |
| sig | Signature | El tipo de la firma, puede ser PKCS1 (objeto Pkcs1Signature), PKCS7 y PKCS7 detached (objeto Pkcs7Signature) |

## Ejemplos

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

### Ver También

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)