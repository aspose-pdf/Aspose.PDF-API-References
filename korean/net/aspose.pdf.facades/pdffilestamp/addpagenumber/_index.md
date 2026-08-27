---
title: "PdfFileStamp.AddPageNumber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileStamp 메서드. 파일에 페이지 번호를 추가합니다. 페이지 번호 텍스트에 # 기호가 포함될 수 있으며, 해당 기호는 페이지 번호로 대체됩니다. 페이지 번호는 페이지 하단에 가로로 가운데 정렬되어 배치됩니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

파일에 페이지 번호를 추가합니다. 페이지 번호 텍스트는 # 기호를 포함할 수 있으며, 이는 페이지 번호로 대체됩니다. 페이지 번호는 페이지 하단에 수평으로 가운데 정렬되어 배치됩니다.

```csharp
public void AddPageNumber(string formatString)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formatString | String | 페이지 번호 텍스트 |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

페이지에 페이지 번호를 추가합니다. 페이지 번호는 # 기호를 포함할 수 있으며, 이는 페이지 번호로 대체됩니다. 페이지 번호는 페이지 하단에 수평으로 가운데 정렬되어 배치됩니다.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 페이지 번호에 대한 형식 문자열은 FormattedText로 표현됩니다. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### 또 보기

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

문서의 페이지에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formatString | String | 페이지 번호에 대한 형식 문자열. |
| position | Int32 | 페이지 번호가 페이지에 배치될 위치입니다. 0-하단 가운데, 1-하단 오른쪽, 2-상단 오른쪽, 3-우측 측면, 4-상단 가운데, 5-하단 왼쪽, 6-좌측 측면, 7-상단 왼쪽. 다음 상수를 사용할 수 있습니다: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | 페이지 왼쪽 가장자리 여백. |
| rightMargin | Single | 페이지 오른쪽 가장자리 여백. |
| topMargin | Single | 페이지 상단 가장자리 여백. |
| bottomMargin | Single | 페이지 하단 가장자리 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

페이지의 지정된 위치에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formatString | String | 형식 문자열. 형식 문자열에 # 기호가 포함될 수 있으며, 이는 페이지 번호로 대체됩니다. |
| x | Single | 페이지 번호의 X 좌표. |
| y | Single | 페이지 번호의 Y 좌표. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

문서의 페이지에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 페이지 번호 형식 및 텍스트 속성을 나타내는 FormattedText 객체. |
| position | Int32 | 페이지 번호가 페이지에 배치될 위치입니다. 0-하단 가운데, 1-하단 오른쪽, 2-상단 오른쪽, 3-우측 측면, 4-상단 가운데, 5-하단 왼쪽, 6-좌측 측면, 7-상단 왼쪽. 다음 상수를 사용할 수 있습니다: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | 페이지 왼쪽 가장자리 여백. |
| rightMargin | Single | 페이지 오른쪽 가장자리 여백. |
| topMargin | Single | 페이지 상단 가장자리 여백. |
| bottomMargin | Single | 페이지 하단 가장자리 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 또 보기

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

페이지의 지정된 위치에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 페이지 번호 형식 및 텍스트 속성을 나타내는 포맷된 텍스트. 형식 문자열에 # 기호가 포함될 수 있으며, 이는 페이지 번호로 대체됩니다. |
| x | Single | 페이지 번호의 X 좌표. |
| y | Single | 페이지 번호의 Y 좌표. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 또 보기

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

페이지에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(string formatString, int position)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formatString | String | 페이지 번호의 형식. 이 텍스트에 #가 포함될 수 있으며, 페이지 번호로 대체됩니다. |
| position | Int32 | 페이지 번호가 페이지에 배치될 위치입니다. 0-하단 가운데, 1-하단 오른쪽, 2-상단 오른쪽, 3-우측 측면, 4-상단 가운데, 5-하단 왼쪽, 6-좌측 측면, 7-상단 왼쪽. 다음 상수를 사용할 수 있습니다: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

페이지에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 페이지 번호 형식과 텍스트 속성을 포함하는 FormattedText 객체. 이 텍스트에 #가 포함될 수 있으며, 페이지 번호로 대체됩니다. |
| position | Int32 | 페이지 번호가 페이지에 배치될 위치입니다. 0-하단 가운데, 1-하단 오른쪽, 2-상단 오른쪽, 3-우측 측면, 4-상단 가운데, 5-하단 왼쪽, 6-좌측 측면, 7-상단 왼쪽. 다음 상수를 사용할 수 있습니다: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 또 보기

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


