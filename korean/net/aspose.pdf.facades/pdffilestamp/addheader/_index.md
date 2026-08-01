---
title: "PdfFileStamp.AddHeader"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileStamp 메서드. 페이지에 헤더를 추가합니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

페이지에 헤더를 추가합니다.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 헤더 텍스트 및 텍스트 속성. |
| topMargin | Single | 페이지 상단 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### 또 보기

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

파일의 페이지에 헤더를 추가합니다.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 페이지 텍스트와 해당 속성을 포함하는 서식이 지정된 텍스트 객체. |
| topMargin | Single | 페이지 상단 여백. |
| leftMargin | Single | 페이지 왼쪽 여백. |
| rightMargin | Single | 페이지 오른쪽 여백. |

## 예제

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### 또 보기

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

파일의 페이지에 헤더로 이미지를 추가합니다.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageFile | String | 이미지 파일 경로. |
| topMargin | Single | 페이지 상단 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

페이지에 헤더로 이미지를 추가합니다.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageFile | String | 이미지 파일 경로. |
| topMargin | Single | 페이지 상단 여백. |
| leftMargin | Single | 페이지 왼쪽 여백. |
| rightMargin | Single | 페이지 오른쪽 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

페이지에 헤더로 이미지를 추가합니다.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 이미지 스트림. |
| topMargin | Single | 페이지 상단 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

페이지 상단에 이미지를 추가합니다.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 이미지 데이터를 포함하는 스트림입니다. |
| topMargin | Single | 페이지 상단 여백. |
| leftMargin | Single | 페이지 왼쪽 여백. |
| rightMargin | Single | 페이지 오른쪽 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


