---
title: Sign
second_title: Aspose.PDF per .NET API Reference
description: Apporta una firma sul documento pdf.
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Apporta una firma sul documento pdf.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero di pagina su cui viene eseguita la firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | Il luogo della firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il diritto di firma. |

### Esempi

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

### Guarda anche

* class [PdfFileSignature](../../pdffilesignature)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesignature)
* assemblea [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Firma il documento con la firma di tipo specificata.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero di pagina su cui viene eseguita la firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | Il luogo della firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il diritto di firma. |
| sig | Signature | Il tipo di firma, potrebbe essere PKCS1, PKCS7 e PKCS7Detached. |

### Esempi

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

### Guarda anche

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesignature)
* assemblea [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Firma il documento con la firma di tipo specificata.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero di pagina su cui viene eseguita la firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il diritto di firma. |
| sig | Signature | Il tipo della firma, potrebbe essere PKCS1, PKCS7 e PKCS7Detached. Tali dati come motivo firma, contatto e posizione devono essere già presenti in questo oggetto (vedi proprietà corrispondenti). |

### Esempi

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

### Guarda anche

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesignature)
* assemblea [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Firma il documento con il tipo specificato firma che è posto nel campo firma già presentato. Prima di firmare il campo firma deve essere vuoto, cioè il campo non deve contenere dizionario firme. Quindi il documento pdf ha già il campo firma, non dovresti fornire il luogo per apporre la firma, la pagina e il rettangolo corrispondenti sono presi dal campo della firma che si trova per nome della firma (vedi parametro SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| SigName | String | Il nome del campo della firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | Il luogo della firma. |
| sig | Signature | Il tipo di firma, potrebbe essere PKCS1, PKCS7 e PKCS7Detached. |

### Esempi

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

### Guarda anche

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesignature)
* assemblea [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Firma il documento con la firma del tipo specificata che è inserita nel campo della firma già presentato. Prima di firmare il documento pdf dovrebbe avere già il campo della firma, la pagina e il rettangolo corrispondenti sono presi dal campo della firma che si trova dal nome della firma (vedi parametro SigName) .

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero di pagina su cui viene eseguita la firma. |
| SigName | String | Il nome del campo della firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | Il luogo della firma. |
| visible | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il diritto di firma. |
| sig | Signature | Il tipo di firma, potrebbe essere PKCS1, PKCS7 e PKCS7Detached. |

### Esempi

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

### Guarda anche

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesignature)
* assemblea [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Firma il documento con il tipo specificato firma che è posto nel campo firma già presentato. Prima di firmare il campo firma deve essere vuoto, cioè il campo non deve contenere dizionario firme. Quindi il documento pdf ha già il campo firma, non dovresti fornire il luogo per apporre la firma, pagina e rettangolo corrispondenti sono presi dal campo firma che si trova per nome firma (vedi parametro SigName). Tali dati come motivo firma, contatto e posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Firma sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| SigName | String | Il nome del campo della firma. |
| sig | Signature | Il tipo di firma, potrebbe essere PKCS1 (oggetto Pkcs1Signature), PKCS7 e PKCS7 staccato (oggetto Pkcs7Signature) |

### Esempi

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

### Guarda anche

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesignature)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
