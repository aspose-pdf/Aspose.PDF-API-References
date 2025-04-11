---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 메서드. PDF 문서에 서명하기
type: docs
weight: 300
url: /ko/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

PDF 문서에 서명하기.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 서명이 이루어지는 페이지 번호. |
| SigReason | String | 서명의 이유. |
| SigContact | String | 서명의 연락처. |
| SigLocation | String | 서명의 위치. |
| visible | Boolean | 서명의 가시성. |
| annotRect | Rectangle | 서명의 사각형. |

## 예제

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

### 참조

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

주어진 유형의 서명으로 문서에 서명하기.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 서명이 이루어지는 페이지 번호. |
| SigReason | String | 서명의 이유. |
| SigContact | String | 서명의 연락처. |
| SigLocation | String | 서명의 위치. |
| visible | Boolean | 서명의 가시성. |
| annotRect | Rectangle | 서명의 사각형. |
| sig | Signature | 서명의 유형, PKCS1, PKCS7 및 PKCS7Detached일 수 있음. |

## 예제

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

### 참조

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

주어진 유형의 서명으로 문서에 서명하기.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 서명이 이루어지는 페이지 번호. |
| visible | Boolean | 서명의 가시성. |
| annotRect | Rectangle | 서명의 사각형. |
| sig | Signature | 서명의 유형, PKCS1, PKCS7 및 PKCS7Detached일 수 있음. 서명 이유, 연락처 및 위치와 같은 데이터는 이미 이 객체에 존재해야 함 (해당 속성 참조). |

## 예제

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

### 참조

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

이미 제공된 서명 필드에 배치된 주어진 유형의 서명으로 문서에 서명하기. 서명하기 전에 서명 필드는 비어 있어야 하며, 즉 필드에는 서명 사전이 포함되어서는 안 됨. 따라서 PDF 문서에는 이미 서명 필드가 있어야 하며, 서명을 찍을 장소를 제공할 필요가 없으며, 해당 페이지와 사각형은 서명 이름으로 찾은 서명 필드에서 가져옵니다 (SigName 매개변수 참조).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| SigName | String | 서명 필드의 이름. |
| SigReason | String | 서명의 이유. |
| SigContact | String | 서명의 연락처. |
| SigLocation | String | 서명의 위치. |
| sig | Signature | 서명의 유형, PKCS1, PKCS7 및 PKCS7Detached일 수 있음. |

## 예제

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

### 참조

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

이미 제공된 서명 필드에 배치된 주어진 유형의 서명으로 문서에 서명하기. 서명하기 전에 PDF 문서에는 이미 서명 필드가 있어야 하며, 해당 페이지와 사각형은 서명 이름으로 찾은 서명 필드에서 가져옵니다 (SigName 매개변수 참조).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 서명이 이루어지는 페이지 번호. |
| SigName | String | 서명 필드의 이름. |
| SigReason | String | 서명의 이유. |
| SigContact | String | 서명의 연락처. |
| SigLocation | String | 서명의 위치. |
| visible | Boolean | 서명의 가시성. |
| annotRect | Rectangle | 서명의 사각형. |
| sig | Signature | 서명의 유형, PKCS1, PKCS7 및 PKCS7Detached일 수 있음. |

## 예제

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

### 참조

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

이미 제공된 서명 필드에 배치된 주어진 유형의 서명으로 문서에 서명하기. 서명하기 전에 서명 필드는 비어 있어야 하며, 즉 필드에는 서명 사전이 포함되어서는 안 됨. 따라서 PDF 문서에는 이미 서명 필드가 있어야 하며, 서명을 찍을 장소를 제공할 필요가 없으며, 해당 페이지와 사각형은 서명 이름으로 찾은 서명 필드에서 가져옵니다 (SigName 매개변수 참조). 서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성으로 제공되어야 함.

```csharp
public void Sign(string SigName, Signature sig)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| SigName | String | 서명 필드의 이름. |
| sig | Signature | 서명의 유형, PKCS1 (Pkcs1Signature 객체), PKCS7 및 PKCS7 분리형 (Pkcs7Signature 객체)일 수 있음. |

## 예제

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

### 참조

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)