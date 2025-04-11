---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature メソッド。PDF ドキュメントに署名を作成します
type: docs
weight: 300
url: /ja/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

PDF ドキュメントに署名を作成します。

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 署名が作成されるページ番号。 |
| SigReason | String | 署名の理由。 |
| SigContact | String | 署名の連絡先。 |
| SigLocation | String | 署名の場所。 |
| visible | Boolean | 署名の可視性。 |
| annotRect | Rectangle | 署名の矩形。 |

## 例

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

### 参照

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

指定されたタイプの署名でドキュメントに署名します。

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 署名が作成されるページ番号。 |
| SigReason | String | 署名の理由。 |
| SigContact | String | 署名の連絡先。 |
| SigLocation | String | 署名の場所。 |
| visible | Boolean | 署名の可視性。 |
| annotRect | Rectangle | 署名の矩形。 |
| sig | Signature | 署名のタイプ。PKCS1、PKCS7、および PKCS7Detached である可能性があります。 |

## 例

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

### 参照

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

指定されたタイプの署名でドキュメントに署名します。

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 署名が作成されるページ番号。 |
| visible | Boolean | 署名の可視性。 |
| annotRect | Rectangle | 署名の矩形。 |
| sig | Signature | 署名のタイプ。PKCS1、PKCS7、および PKCS7Detached である可能性があります。署名の理由、連絡先、および場所などのデータは、このオブジェクトにすでに存在している必要があります（対応するプロパティを参照）。 |

## 例

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

### 参照

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

既に存在する署名フィールドに配置された指定されたタイプの署名でドキュメントに署名します。署名する前に、署名フィールドは空でなければなりません。つまり、フィールドには署名辞書が含まれていてはなりません。したがって、PDF ドキュメントにはすでに署名フィールドが存在し、署名を押す場所を提供する必要はありません。対応するページと矩形は、署名名によって見つかった署名フィールドから取得されます（SigName パラメータを参照）。

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| SigName | String | 署名フィールドの名前。 |
| SigReason | String | 署名の理由。 |
| SigContact | String | 署名の連絡先。 |
| SigLocation | String | 署名の場所。 |
| sig | Signature | 署名のタイプ。PKCS1、PKCS7、および PKCS7Detached である可能性があります。 |

## 例

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

### 参照

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

既に存在する署名フィールドに配置された指定されたタイプの署名でドキュメントに署名します。署名する前に、PDF ドキュメントにはすでに署名フィールドが存在している必要があります。対応するページと矩形は、署名名によって見つかった署名フィールドから取得されます（SigName パラメータを参照）。

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 署名が作成されるページ番号。 |
| SigName | String | 署名フィールドの名前。 |
| SigReason | String | 署名の理由。 |
| SigContact | String | 署名の連絡先。 |
| SigLocation | String | 署名の場所。 |
| visible | Boolean | 署名の可視性。 |
| annotRect | Rectangle | 署名の矩形。 |
| sig | Signature | 署名のタイプ。PKCS1、PKCS7、および PKCS7Detached である可能性があります。 |

## 例

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

### 参照

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

既に存在する署名フィールドに配置された指定されたタイプの署名でドキュメントに署名します。署名する前に、署名フィールドは空でなければなりません。つまり、フィールドには署名辞書が含まれていてはなりません。したがって、PDF ドキュメントにはすでに署名フィールドが存在し、署名を押す場所を提供する必要はありません。対応するページと矩形は、署名名によって見つかった署名フィールドから取得されます（SigName パラメータを参照）。署名の理由、連絡先、および場所などのデータは、Signature オブジェクト sig の対応するプロパティによって提供される必要があります。

```csharp
public void Sign(string SigName, Signature sig)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| SigName | String | 署名フィールドの名前。 |
| sig | Signature | 署名のタイプ。PKCS1（Pkcs1Signature オブジェクト）、PKCS7、および PKCS7 detached（Pkcs7Signature オブジェクト）である可能性があります。 |

## 例

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

### 参照

* class [Signature](../../../aspose.pdf.forms/signature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)