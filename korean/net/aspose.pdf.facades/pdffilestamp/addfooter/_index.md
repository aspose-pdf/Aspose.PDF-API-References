---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 메서드. 문서의 페이지에 바닥글을 추가합니다.
type: docs
weight: 110
url: /ko/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

문서의 페이지에 바닥글을 추가합니다.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 바닥글의 텍스트와 텍스트 속성을 포함하는 FormattedText 객체입니다. |
| bottomMargin | Single | 페이지의 상단 여백입니다. |

## 예제

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### 참조

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

문서의 페이지에 바닥글을 추가합니다.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 바닥글 텍스트와 텍스트 속성을 포함하는 FormattedText 객체입니다. |
| bottomMargin | Single | 페이지의 하단 여백입니다. |
| leftMargin | Single | 페이지의 왼쪽 여백입니다. |
| rightMargin | Single | 페이지의 오른쪽 여백입니다. |

## 예제

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### 참조

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

이미지를 바닥글로 문서의 페이지에 추가합니다.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageFile | String | 이미지 파일 이름과 경로입니다. |
| bottomMargin | Single | 페이지의 하단 여백입니다. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### 참조

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

페이지의 바닥글로 이미지를 추가합니다.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageFile | String | 이미지 파일 이름과 경로입니다. |
| bottomMargin | Single | 페이지의 하단 여백입니다. |
| leftMargin | Single | 페이지의 왼쪽 여백입니다. |
| rightMargin | Single | 페이지의 오른쪽 여백입니다. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### 참조

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

페이지의 바닥글로 이미지를 추가합니다.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 이미지 데이터를 포함하는 스트림입니다. |
| bottomMargin | Single | 페이지의 하단 여백입니다. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### 참조

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

페이지의 바닥글로 이미지를 추가합니다.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 이미지 데이터를 포함하는 스트림입니다. |
| bottomMargin | Single | 페이지의 하단 여백입니다. |
| leftMargin | Single | 페이지의 왼쪽 여백입니다. |
| rightMargin | Single | 페이지의 오른쪽 여백입니다. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### 참조

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)