---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 方法。在 pdf 文档上进行签名
type: docs
weight: 300
url: /zh/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

在 pdf 文档上进行签名。

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 签名所在的页码。 |
| SigReason | String | 签名的原因。 |
| SigContact | String | 签名的联系方式。 |
| SigLocation | String | 签名的位置。 |
| visible | Boolean | 签名的可见性。 |
| annotRect | Rectangle | 签名的矩形区域。 |

## 示例

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

### 另请参见

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

使用给定类型的签名对文档进行签名。

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 签名所在的页码。 |
| SigReason | String | 签名的原因。 |
| SigContact | String | 签名的联系方式。 |
| SigLocation | String | 签名的位置。 |
| visible | Boolean | 签名的可见性。 |
| annotRect | Rectangle | 签名的矩形区域。 |
| sig | Signature | 签名的类型，可以是 PKCS1、PKCS7 和 PKCS7Detached。 |

## 示例

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

### 另请参见

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

使用给定类型的签名对文档进行签名。

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 签名所在的页码。 |
| visible | Boolean | 签名的可见性。 |
| annotRect | Rectangle | 签名的矩形区域。 |
| sig | Signature | 签名的类型，可以是 PKCS1、PKCS7 和 PKCS7Detached。签名原因、联系方式和位置等数据必须已经存在于此对象中（请参见相应属性）。 |

## 示例

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

### 另请参见

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

使用给定类型的签名对文档进行签名，该签名放置在已经存在的签名字段中。在签名之前，签名字段必须为空，即字段不能包含签名字典。因此 pdf 文档已经有签名字段，您不需要提供签名的印章位置，相应的页码和矩形区域将从通过签名名称找到的签名字段中获取（请参见 SigName 参数）。

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| SigName | String | 签名字段的名称。 |
| SigReason | String | 签名的原因。 |
| SigContact | String | 签名的联系方式。 |
| SigLocation | String | 签名的位置。 |
| sig | Signature | 签名的类型，可以是 PKCS1、PKCS7 和 PKCS7Detached。 |

## 示例

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

### 另请参见

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

使用给定类型的签名对文档进行签名，该签名放置在已经存在的签名字段中。在签名之前，pdf 文档必须已经有签名字段，相应的页码和矩形区域将从通过签名名称找到的签名字段中获取（请参见 SigName 参数）。

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 签名所在的页码。 |
| SigName | String | 签名字段的名称。 |
| SigReason | String | 签名的原因。 |
| SigContact | String | 签名的联系方式。 |
| SigLocation | String | 签名的位置。 |
| visible | Boolean | 签名的可见性。 |
| annotRect | Rectangle | 签名的矩形区域。 |
| sig | Signature | 签名的类型，可以是 PKCS1、PKCS7 和 PKCS7Detached。 |

## 示例

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

### 另请参见

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

使用给定类型的签名对文档进行签名，该签名放置在已经存在的签名字段中。在签名之前，签名字段必须为空，即字段不能包含签名字典。因此 pdf 文档已经有签名字段，您不需要提供签名的印章位置，相应的页码和矩形区域将从通过签名名称找到的签名字段中获取（请参见 SigName 参数）。签名原因、联系方式和位置等数据必须通过签名对象 sig 的相应属性提供。

```csharp
public void Sign(string SigName, Signature sig)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| SigName | String | 签名字段的名称。 |
| sig | Signature | 签名的类型，可以是 PKCS1（Pkcs1Signature 对象）、PKCS7 和 PKCS7 分离（Pkcs7Signature 对象） |

## 示例

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

### 另请参见

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)