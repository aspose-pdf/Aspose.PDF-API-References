---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSignature. Faça uma assinatura no documento pdf
type: docs
weight: 300
url: /pt/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Faça uma assinatura no documento pdf.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | O número da página na qual a assinatura é feita. |
| SigReason | String | O motivo da assinatura. |
| SigContact | String | O contato da assinatura. |
| SigLocation | String | A localização da assinatura. |
| visible | Boolean | A visibilidade da assinatura. |
| annotRect | Rectangle | O retângulo da assinatura. |

## Exemplos

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

### Veja Também

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Assine o documento com o tipo de assinatura fornecido.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | O número da página na qual a assinatura é feita. |
| SigReason | String | O motivo da assinatura. |
| SigContact | String | O contato da assinatura. |
| SigLocation | String | A localização da assinatura. |
| visible | Boolean | A visibilidade da assinatura. |
| annotRect | Rectangle | O retângulo da assinatura. |
| sig | Signature | O tipo da assinatura, pode ser PKCS1, PKCS7 e PKCS7Detached. |

## Exemplos

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

### Veja Também

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Assine o documento com o tipo de assinatura fornecido.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | O número da página na qual a assinatura é feita. |
| visible | Boolean | A visibilidade da assinatura. |
| annotRect | Rectangle | O retângulo da assinatura. |
| sig | Signature | O tipo da assinatura, pode ser PKCS1, PKCS7 e PKCS7Detached. Os dados como motivo da assinatura, contato e localização devem já estar presentes neste objeto (veja as propriedades correspondentes). |

## Exemplos

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

### Veja Também

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Assine o documento com o tipo de assinatura fornecido que está colocado em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter um dicionário de assinatura. Assim, o documento pdf já possui um campo de assinatura, você não deve fornecer o local para carimbar a assinatura, a página correspondente e o retângulo são retirados do campo de assinatura que é encontrado pelo nome da assinatura (veja o parâmetro SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| SigName | String | O nome do campo de assinatura. |
| SigReason | String | O motivo da assinatura. |
| SigContact | String | O contato da assinatura. |
| SigLocation | String | A localização da assinatura. |
| sig | Signature | O tipo da assinatura, pode ser PKCS1, PKCS7 e PKCS7Detached. |

## Exemplos

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

### Veja Também

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Assine o documento com o tipo de assinatura fornecido que está colocado em um campo de assinatura já apresentado. Antes de assinar, o documento pdf deve já ter um campo de assinatura, a página correspondente e o retângulo são retirados do campo de assinatura que é encontrado pelo nome da assinatura (veja o parâmetro SigName).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | O número da página na qual a assinatura é feita. |
| SigName | String | O nome do campo de assinatura. |
| SigReason | String | O motivo da assinatura. |
| SigContact | String | O contato da assinatura. |
| SigLocation | String | A localização da assinatura. |
| visible | Boolean | A visibilidade da assinatura. |
| annotRect | Rectangle | O retângulo da assinatura. |
| sig | Signature | O tipo da assinatura, pode ser PKCS1, PKCS7 e PKCS7Detached. |

## Exemplos

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

### Veja Também

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Assine o documento com o tipo de assinatura fornecido que está colocado em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter um dicionário de assinatura. Assim, o documento pdf já possui um campo de assinatura, você não deve fornecer o local para carimbar a assinatura, a página correspondente e o retângulo são retirados do campo de assinatura que é encontrado pelo nome da assinatura (veja o parâmetro SigName). Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| SigName | String | O nome do campo de assinatura. |
| sig | Signature | O tipo da assinatura, pode ser PKCS1 (objeto Pkcs1Signature), PKCS7 e PKCS7 detached (objeto Pkcs7Signature) |

## Exemplos

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

### Veja Também

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)