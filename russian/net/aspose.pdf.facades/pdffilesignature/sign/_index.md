---
title: PdfFileSignature.Sign
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSignature. Сделать подпись на pdf документе
type: docs
weight: 300
url: /ru/net/aspose.pdf.facades/pdffilesignature/sign/
---
## Sign(int, string, string, string, bool, Rectangle) {#sign_1}

Сделать подпись на pdf документе.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Номер страницы, на которой сделана подпись. |
| SigReason | String | Причина подписи. |
| SigContact | String | Контакт подписи. |
| SigLocation | String | Место подписи. |
| visible | Boolean | Видимость подписи. |
| annotRect | Rectangle | Прямоугольник подписи. |

## Примеры

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

### См. также

* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, bool, Rectangle, Signature) {#sign_2}

Подписать документ с заданным типом подписи.

```csharp
public void Sign(int page, string SigReason, string SigContact, string SigLocation, bool visible, 
    Rectangle annotRect, Signature sig)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Номер страницы, на которой сделана подпись. |
| SigReason | String | Причина подписи. |
| SigContact | String | Контакт подписи. |
| SigLocation | String | Место подписи. |
| visible | Boolean | Видимость подписи. |
| annotRect | Rectangle | Прямоугольник подписи. |
| sig | Signature | Тип подписи, может быть PKCS1, PKCS7 и PKCS7Detached. |

## Примеры

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

### См. также

* класс [Signature](../../../aspose.pdf.forms/signature/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Sign(int, bool, Rectangle, Signature) {#sign}

Подписать документ с заданным типом подписи.

```csharp
public void Sign(int page, bool visible, Rectangle annotRect, Signature sig)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Номер страницы, на которой сделана подпись. |
| visible | Boolean | Видимость подписи. |
| annotRect | Rectangle | Прямоугольник подписи. |
| sig | Signature | Тип подписи, может быть PKCS1, PKCS7 и PKCS7Detached. Такие данные, как причина подписи, контакт и место, должны уже присутствовать в этом объекте (см. соответствующие свойства). |

## Примеры

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

### См. также

* класс [Signature](../../../aspose.pdf.forms/signature/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Sign(string, string, string, string, Signature) {#sign_5}

Подписать документ с заданным типом подписи, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, pdf документ уже имеет поле подписи, вы не должны указывать место для печати подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName).

```csharp
public void Sign(string SigName, string SigReason, string SigContact, string SigLocation, 
    Signature sig)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| SigName | String | Имя поля подписи. |
| SigReason | String | Причина подписи. |
| SigContact | String | Контакт подписи. |
| SigLocation | String | Место подписи. |
| sig | Signature | Тип подписи, может быть PKCS1, PKCS7 и PKCS7Detached. |

## Примеры

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

### См. также

* класс [Signature](../../../aspose.pdf.forms/signature/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Sign(int, string, string, string, string, bool, Rectangle, Signature) {#sign_3}

Подписать документ с заданным типом подписи, которая размещена в уже представленном поле подписи. Перед подписанием pdf документ должен уже иметь поле подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName).

```csharp
public void Sign(int page, string SigName, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, Signature sig)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Номер страницы, на которой сделана подпись. |
| SigName | String | Имя поля подписи. |
| SigReason | String | Причина подписи. |
| SigContact | String | Контакт подписи. |
| SigLocation | String | Место подписи. |
| visible | Boolean | Видимость подписи. |
| annotRect | Rectangle | Прямоугольник подписи. |
| sig | Signature | Тип подписи, может быть PKCS1, PKCS7 и PKCS7Detached. |

## Примеры

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

### См. также

* класс [Signature](../../../aspose.pdf.forms/signature/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Sign(string, Signature) {#sign_4}

Подписать документ с заданным типом подписи, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, pdf документ уже имеет поле подписи, вы не должны указывать место для печати подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName). Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig.

```csharp
public void Sign(string SigName, Signature sig)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| SigName | String | Имя поля подписи. |
| sig | Signature | Тип подписи, может быть PKCS1 (объект Pkcs1Signature), PKCS7 и PKCS7 detached (объект Pkcs7Signature) |

## Примеры

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

### См. также

* класс [Signature](../../../aspose.pdf.forms/signature/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)