---
title: "PdfFileSignature.Sign"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfFileSignature metodo. Crea una firma sul documento pdf"
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Crea una firma sul documento PDF.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Int32 | Il numero di pagina su cui viene effettuata la firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| visibile | Boolean | La visibilità della firma. |
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

### Vedi anche

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Firma il documento con la firma di tipo specificato.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Int32 | Il numero di pagina su cui viene effettuata la firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| visibile | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |
| sig | Firma | Il tipo della firma, potrebbe essere PKCS1, PKCS7 e PKCS7Detached. |

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

### Vedi anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Firma il documento con la firma di tipo specificato.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Int32 | Il numero di pagina su cui viene effettuata la firma. |
| visibile | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |
| sig | Firma | Il tipo della firma, potrebbe essere PKCS1, PKCS7 e PKCS7Detached. Dati come il motivo della firma, il contatto e la posizione devono già essere presenti in questo oggetto (vedi le proprietà corrispondenti). |

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

### Vedi anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè non deve contenere un dizionario firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo per apporre la firma, la pagina corrispondente e il rettangolo vengono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| SigName | String | Il nome del campo della firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| sig | Firma | Il tipo della firma, potrebbe essere PKCS1, PKCS7 e PKCS7Detached. |

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

### Vedi anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il documento PDF dovrebbe già avere un campo firma; la pagina corrispondente e il rettangolo vengono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Int32 | Il numero di pagina su cui viene effettuata la firma. |
| SigName | String | Il nome del campo della firma. |
| SigReason | String | Il motivo della firma. |
| SigContact | String | Il contatto della firma. |
| SigLocation | String | La posizione della firma. |
| visibile | Boolean | La visibilità della firma. |
| annotRect | Rectangle | Il rettangolo della firma. |
| sig | Firma | Il tipo della firma, potrebbe essere PKCS1, PKCS7 e PKCS7Detached. |

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

### Vedi anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè non deve contenere un dizionario firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo per apporre la firma, la pagina corrispondente e il rettangolo vengono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName). Dati come il motivo della firma, il contatto e la posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Signature sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| SigName | String | Il nome del campo della firma. |
| sig | Firma | Il tipo della firma, potrebbe essere PKCS1 (oggetto Pkcs1Signature), PKCS7 e PKCS7 detached (oggetto Pkcs7Signature) |

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

### Vedi anche

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


