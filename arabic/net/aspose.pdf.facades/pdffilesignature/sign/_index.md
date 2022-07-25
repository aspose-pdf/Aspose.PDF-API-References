---
title: Sign
second_title: Aspose.PDF لمرجع .NET API
description: قم بعمل توقيع على مستند pdf .
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

قم بعمل توقيع على مستند pdf .

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| page | Int32 | رقم الصفحة التي تم التوقيع عليها. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة اتصال التوقيع. |
| SigLocation | String | موقع التوقيع. |
| visible | Boolean | رؤية التوقيع. |
| annotRect | Rectangle | وجه التوقيع. |

### أمثلة

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

### أنظر أيضا

* class [PdfFileSignature](../../pdffilesignature)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesignature)
* المجسم [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

وقّع على المستند باستخدام نوع التوقيع المحدد.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| page | Int32 | رقم الصفحة التي تم التوقيع عليها. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة اتصال التوقيع. |
| SigLocation | String | موقع التوقيع. |
| visible | Boolean | رؤية التوقيع. |
| annotRect | Rectangle | وجه التوقيع. |
| sig | Signature | يمكن أن يكون نوع التوقيع PKCS1 و PKCS7 و PKCS7 مفصول. |

### أمثلة

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

### أنظر أيضا

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesignature)
* المجسم [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

وقّع على المستند باستخدام نوع التوقيع المحدد.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| page | Int32 | رقم الصفحة التي تم التوقيع عليها. |
| visible | Boolean | رؤية التوقيع. |
| annotRect | Rectangle | وجه التوقيع. |
| sig | Signature | يمكن أن يكون نوع التوقيع PKCS1 و PKCS7 و PKCS7 منفصل . يجب أن تكون البيانات مثل سبب التوقيع وجهة الاتصال والموقع موجودة بالفعل في هذا الكائن (انظر الخصائص المقابلة) . |

### أمثلة

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

### أنظر أيضا

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesignature)
* المجسم [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

قم بتوقيع المستند بتوقيع النوع المحدد والذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا ، أي يجب ألا يحتوي الحقل على قاموس التوقيع. لختم التوقيع ، يتم أخذ الصفحة المقابلة والمستطيل من حقل التوقيع الموجود باسم التوقيع (انظر معلمة SigName) .

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| SigName | String | اسم حقل التوقيع. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة اتصال التوقيع. |
| SigLocation | String | موقع التوقيع. |
| sig | Signature | يمكن أن يكون نوع التوقيع PKCS1 و PKCS7 و PKCS7 مفصول. |

### أمثلة

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

### أنظر أيضا

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesignature)
* المجسم [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

قم بتوقيع المستند بتوقيع النوع المحدد والذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع يجب أن يحتوي مستند pdf بالفعل على حقل توقيع ، يتم أخذ الصفحة المقابلة والمستطيل من حقل التوقيع الذي تم العثور عليه بواسطة اسم التوقيع (انظر معلمة SigName) .

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| page | Int32 | رقم الصفحة التي تم التوقيع عليها. |
| SigName | String | اسم حقل التوقيع. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة اتصال التوقيع. |
| SigLocation | String | موقع التوقيع. |
| visible | Boolean | رؤية التوقيع. |
| annotRect | Rectangle | وجه التوقيع. |
| sig | Signature | يمكن أن يكون نوع التوقيع PKCS1 و PKCS7 و PKCS7 مفصول. |

### أمثلة

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

### أنظر أيضا

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesignature)
* المجسم [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

قم بتوقيع المستند بتوقيع النوع المحدد والذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا ، أي يجب ألا يحتوي الحقل على قاموس التوقيع. لختم التوقيع ، يتم أخذ الصفحة المقابلة والمستطيل من حقل التوقيع الذي تم العثور عليه بواسطة اسم التوقيع (انظر معلمة SigName) . يجب توفير البيانات مثل سبب التوقيع والاتصال والموقع من خلال الخصائص المقابلة لكائن التوقيع sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| SigName | String | اسم حقل التوقيع. |
| sig | Signature | يمكن أن يكون نوع التوقيع PKCS1 (كائن Pkcs1Signature) ، و PKCS7 و PKCS7 منفصلان (كائن Pkcs7Signature) |

### أمثلة

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

### أنظر أيضا

* class [Signature](../../../aspose.pdf.forms/signature)
* class [PdfFileSignature](../../pdffilesignature)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesignature)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
