---
title: Sign
second_title: Referencia de API de Aspose.PDF para .NET
description: Hacer una firma en el documento pdf.
type: docs
weight: 280
url: /es/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Hacer una firma en el documento pdf.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| page | Int32 | El número de página en la que se realiza la firma. |
| SigReason | String | El motivo de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El recto de la firma. |

### Ejemplos

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

### Ver también

* class [PdfFileSignature](../../pdffilesignature)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesignature)
* asamblea [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Firma el documento con el tipo de firma dado.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| page | Int32 | El número de página en la que se realiza la firma. |
| SigReason | String | El motivo de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El recto de la firma. |
| sig | Signature | El tipo de firma, podría ser PKCS1, PKCS7 y PKCS7Detached. |

### Ejemplos

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

### Ver también

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesignature)
* asamblea [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Firma el documento con el tipo de firma dado.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| page | Int32 | El número de página en la que se realiza la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El recto de la firma. |
| sig | Signature | El tipo de firma, podría ser PKCS1, PKCS7 y PKCS7Detached. Los datos como el motivo de la firma, el contacto y la ubicación ya deben estar presentes en este objeto (consulte las propiedades correspondientes). |

### Ejemplos

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

### Ver también

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesignature)
* asamblea [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Firme el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener el diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para estampar la firma, se toman la página y el rectángulo correspondientes del campo de firma que se encuentra por nombre de firma (consulte el parámetro SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| SigName | String | El nombre del campo de la firma. |
| SigReason | String | El motivo de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| sig | Signature | El tipo de firma, podría ser PKCS1, PKCS7 y PKCS7Detached. |

### Ejemplos

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

### Ver también

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesignature)
* asamblea [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Firme el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el documento pdf ya debe tener un campo de firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por nombre de firma (consulte el parámetro SigName) .

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| page | Int32 | El número de página en la que se realiza la firma. |
| SigName | String | El nombre del campo de la firma. |
| SigReason | String | El motivo de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El recto de la firma. |
| sig | Signature | El tipo de firma, podría ser PKCS1, PKCS7 y PKCS7Detached. |

### Ejemplos

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

### Ver también

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesignature)
* asamblea [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Firme el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener el diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para sellar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por nombre de firma (consulte el parámetro SigName).

```csharp
public void Sign(string SigName, Signature sig)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| SigName | String | El nombre del campo de la firma. |
| sig | Signature | El tipo de firma podría ser PKCS1 (objeto Pkcs1Signature), PKCS7 y PKCS7 separados (objeto Pkcs7Signature) |

### Ejemplos

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

### Ver también

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesignature)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
