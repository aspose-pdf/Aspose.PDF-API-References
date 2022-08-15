---
title: Sign
second_title: Référence de l'API Aspose.PDF pour .NET
description: Faire une signature sur le document pdf.
type: docs
weight: 280
url: /fr/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Faire une signature sur le document pdf.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| page | Int32 | Le numéro de la page sur laquelle la signature est faite. |
| SigReason | String | La raison de la signature. |
| SigContact | String | Le contact de signature. |
| SigLocation | String | L'emplacement de la signature. |
| visible | Boolean | La visibilité de la signature. |
| annotRect | Rectangle | Le recto de la signature. |

### Exemples

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

### Voir également

* class [PdfFileSignature](../../pdffilesignature)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesignature)
* Assemblée [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Signez le document avec le type de signature donné.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| page | Int32 | Le numéro de la page sur laquelle la signature est faite. |
| SigReason | String | La raison de la signature. |
| SigContact | String | Le contact de signature. |
| SigLocation | String | L'emplacement de la signature. |
| visible | Boolean | La visibilité de la signature. |
| annotRect | Rectangle | Le recto de la signature. |
| sig | Signature | Le type de signature peut être PKCS1, PKCS7 et PKCS7Detached. |

### Exemples

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

### Voir également

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesignature)
* Assemblée [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Signez le document avec le type de signature donné.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| page | Int32 | Le numéro de la page sur laquelle la signature est faite. |
| visible | Boolean | La visibilité de la signature. |
| annotRect | Rectangle | Le recto de la signature. |
| sig | Signature | Le type de signature peut être PKCS1, PKCS7 et PKCS7Detached. Des données telles que le motif de la signature, le contact et l'emplacement doivent déjà être présentes dans cet objet (voir les propriétés correspondantes). |

### Exemples

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

### Voir également

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesignature)
* Assemblée [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Signez le document avec la signature de type donnée qui est placée dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir le lieu pour tamponner la signature, la page et le rectangle correspondants sont extraits du champ de signature qui se trouve par nom de signature (voir paramètre SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| SigName | String | Le nom du champ de signature. |
| SigReason | String | La raison de la signature. |
| SigContact | String | Le contact de signature. |
| SigLocation | String | L'emplacement de la signature. |
| sig | Signature | Le type de signature peut être PKCS1, PKCS7 et PKCS7Detached. |

### Exemples

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

### Voir également

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesignature)
* Assemblée [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Signez le document avec la signature de type donnée qui est placée dans le champ de signature déjà présenté. Avant de signer le document pdf doit déjà avoir un champ de signature, la page et le rectangle correspondants sont tirés du champ de signature qui se trouve par nom de signature (voir le paramètre SigName) .

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| page | Int32 | Le numéro de la page sur laquelle la signature est faite. |
| SigName | String | Le nom du champ de signature. |
| SigReason | String | La raison de la signature. |
| SigContact | String | Le contact de signature. |
| SigLocation | String | L'emplacement de la signature. |
| visible | Boolean | La visibilité de la signature. |
| annotRect | Rectangle | Le recto de la signature. |
| sig | Signature | Le type de signature peut être PKCS1, PKCS7 et PKCS7Detached. |

### Exemples

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

### Voir également

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesignature)
* Assemblée [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Signez le document avec la signature de type donnée qui est placée dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir le lieu pour tamponner la signature, la page et le rectangle correspondants sont tirés du champ de signature qui se trouve par le nom de la signature (voir le paramètre SigName). Des données telles que le motif de la signature, le contact et l'emplacement doivent être fournies par les propriétés correspondantes de l'objet Signature sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| SigName | String | Le nom du champ de signature. |
| sig | Signature | Le type de signature peut être PKCS1 (objet Pkcs1Signature), PKCS7 et PKCS7 détaché (objet Pkcs7Signature) |

### Exemples

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

### Voir également

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* espace de noms [Aspose.Pdf.Facades](../../pdffilesignature)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
