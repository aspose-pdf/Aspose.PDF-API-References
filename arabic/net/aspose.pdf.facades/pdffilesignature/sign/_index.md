---
title: "PdfFileSignature.Sign"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSignature. إنشاء توقيع على مستند pdf"
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

أنشئ توقيعًا على مستند PDF.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | رقم الصفحة التي يُجرى فيها التوقيع. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة الاتصال للتوقيع. |
| SigLocation | String | موقع التوقيع. |
| مرئي | Boolean | ظهور التوقيع. |
| annotRect | Rectangle | مستطيل التوقيع. |

## أمثلة

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

### انظر أيضًا

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

وقّع المستند باستخدام نوع التوقيع المحدد.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | رقم الصفحة التي يُجرى فيها التوقيع. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة الاتصال للتوقيع. |
| SigLocation | String | موقع التوقيع. |
| مرئي | Boolean | ظهور التوقيع. |
| annotRect | Rectangle | مستطيل التوقيع. |
| sig | Signature | نوع التوقيع، يمكن أن يكون PKCS1 أو PKCS7 و PKCS7Detached. |

## أمثلة

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

### انظر أيضًا

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

وقّع المستند باستخدام نوع التوقيع المحدد.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | رقم الصفحة التي يُجرى فيها التوقيع. |
| مرئي | Boolean | ظهور التوقيع. |
| annotRect | Rectangle | مستطيل التوقيع. |
| sig | Signature | نوع التوقيع، يمكن أن يكون PKCS1 أو PKCS7 و PKCS7Detached. يجب أن تكون بيانات مثل سبب التوقيع، جهة الاتصال والموقع موجودة بالفعل في هذا الكائن (انظر الخصائص المقابلة). |

## أمثلة

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

### انظر أيضًا

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

وقّع المستند باستخدام نوع التوقيع المحدد والذي يتم وضعه في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي الحقل على قاموس توقيع. وبالتالي يحتوي مستند PDF بالفعل على حقل توقيع، لا تحتاج إلى تحديد مكان وضع التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| SigName | String | اسم حقل التوقيع. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة الاتصال للتوقيع. |
| SigLocation | String | موقع التوقيع. |
| sig | Signature | نوع التوقيع، يمكن أن يكون PKCS1 أو PKCS7 و PKCS7Detached. |

## أمثلة

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

### انظر أيضًا

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

وقّع المستند باستخدام نوع التوقيع المحدد والذي يتم وضعه في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يحتوي مستند PDF بالفعل على حقل توقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | رقم الصفحة التي يُجرى فيها التوقيع. |
| SigName | String | اسم حقل التوقيع. |
| SigReason | String | سبب التوقيع. |
| SigContact | String | جهة الاتصال للتوقيع. |
| SigLocation | String | موقع التوقيع. |
| مرئي | Boolean | ظهور التوقيع. |
| annotRect | Rectangle | مستطيل التوقيع. |
| sig | Signature | نوع التوقيع، يمكن أن يكون PKCS1 أو PKCS7 و PKCS7Detached. |

## أمثلة

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

### انظر أيضًا

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

وقّع المستند باستخدام نوع التوقيع المحدد والذي يتم وضعه في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي الحقل على قاموس توقيع. وبالتالي يحتوي مستند PDF بالفعل على حقل توقيع، لا تحتاج إلى تحديد مكان وضع التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName). يجب توفير بيانات مثل سبب التوقيع، ومعلومات الاتصال، والموقع عبر الخصائص المقابلة لكائن Signature المسمى sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| SigName | String | اسم حقل التوقيع. |
| sig | Signature | نوع التوقيع، يمكن أن يكون PKCS1 (كائن Pkcs1Signature)، PKCS7 و PKCS7 detached (كائن Pkcs7Signature) |

## أمثلة

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

### انظر أيضًا

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


