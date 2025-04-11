---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSignature. Fai una firma sul documento pdf
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Fai una firma sul documento pdf.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero di pagina su cui viene effettuata la firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |

## Esempi

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

### Vedi Anche

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Firma il documento con il tipo di firma fornito.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero di pagina su cui viene effettuata la firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |
| sig | Signature | Il tipo della firma, può essere PKCS1, PKCS7 e PKCS7Detached. |

## Esempi

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

### Vedi Anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Firma il documento con il tipo di firma fornito.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero di pagina su cui viene effettuata la firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |
| sig | Signature | Il tipo della firma, può essere PKCS1, PKCS7 e PKCS7Detached. I dati come il motivo della firma, il contatto e la posizione devono essere già presenti in questo oggetto (vedi le proprietà corrispondenti). |

## Esempi

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

### Vedi Anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Firma il documento con il tipo di firma fornito che è posizionato nel campo di firma già presentato. Prima di firmare, il campo di firma deve essere vuoto, cioè il campo non deve contenere un dizionario di firma. Pertanto, il documento pdf ha già un campo di firma, non è necessario fornire il luogo per apporre la firma, la pagina corrispondente e il rettangolo sono presi dal campo di firma che si trova per nome della firma (vedi parametro SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| SigName | String | Il nome del campo di firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| sig | Signature | Il tipo della firma, può essere PKCS1, PKCS7 e PKCS7Detached. |

## Esempi

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

### Vedi Anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Firma il documento con il tipo di firma fornito che è posizionato nel campo di firma già presentato. Prima di firmare, il documento pdf deve già avere un campo di firma, la pagina corrispondente e il rettangolo sono presi dal campo di firma che si trova per nome della firma (vedi parametro SigName).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero di pagina su cui viene effettuata la firma. |
| SigName | String | Il nome del campo di firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |
| sig | Signature | Il tipo della firma, può essere PKCS1, PKCS7 e PKCS7Detached. |

## Esempi

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

### Vedi Anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Firma il documento con il tipo di firma fornito che è posizionato nel campo di firma già presentato. Prima di firmare, il campo di firma deve essere vuoto, cioè il campo non deve contenere un dizionario di firma. Pertanto, il documento pdf ha già un campo di firma, non è necessario fornire il luogo per apporre la firma, la pagina corrispondente e il rettangolo sono presi dal campo di firma che si trova per nome della firma (vedi parametro SigName). I dati come il motivo della firma, il contatto e la posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Signature sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| SigName | String | Il nome del campo di firma. |
| sig | Signature | Il tipo della firma, può essere PKCS1 (oggetto Pkcs1Signature), PKCS7 e PKCS7 detached (oggetto Pkcs7Signature) |

## Esempi

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

### Vedi Anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)