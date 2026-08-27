---
title: "PdfFileStamp.AddFooter"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileStamp 메서드. 문서 페이지에 푸터를 추가합니다"
type: docs
weight: 110
url: /ko/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

문서 페이지에 푸터를 추가합니다.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText 객체는 푸터 텍스트와 텍스트 속성을 포함합니다. |
| bottomMargin | Single | 페이지 상단 여백. |

## 예제

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### 또 보기

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

문서 페이지에 푸터를 추가합니다.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText 객체는 푸터 텍스트와 텍스트 속성을 포함합니다. |
| bottomMargin | Single | 페이지 하단 여백. |
| leftMargin | Single | 페이지 왼쪽 여백. |
| rightMargin | Single | 페이지 오른쪽 여백. |

## 예제

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### 또 보기

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

문서 페이지에 푸터 이미지로 추가합니다.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageFile | String | 이미지 파일 이름 및 경로입니다. |
| bottomMargin | Single | 페이지 하단 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

페이지 하단에 이미지를 추가합니다.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageFile | String | 이미지 파일 이름 및 경로. |
| bottomMargin | Single | 페이지 하단 여백. |
| leftMargin | Single | 페이지 왼쪽 여백. |
| rightMargin | Single | 페이지 오른쪽 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

페이지의 푸터로 이미지를 추가합니다.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 스트림에 이미지 데이터가 포함되어 있습니다. |
| bottomMargin | Single | 페이지 하단 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

페이지의 푸터로 이미지를 추가합니다.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 스트림에 이미지 데이터가 포함되어 있습니다. |
| bottomMargin | Single | 페이지 하단 여백. |
| leftMargin | Single | 페이지 왼쪽 여백. |
| rightMargin | Single | 페이지 오른쪽 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


