---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 메서드. 파일에 페이지 번호를 추가합니다. 페이지 번호 텍스트에는 페이지 번호로 대체될 # 기호가 포함될 수 있습니다. 페이지 번호는 페이지 하단 중앙에 배치됩니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

파일에 페이지 번호를 추가합니다. 페이지 번호 텍스트에는 페이지 번호로 대체될 # 기호가 포함될 수 있습니다. 페이지 번호는 페이지 하단 중앙에 배치됩니다.

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

### 참조

* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

페이지에 페이지 번호를 추가합니다. 페이지 번호에는 페이지 번호로 대체될 # 기호가 포함될 수 있습니다. 페이지 번호는 페이지 하단 중앙에 배치됩니다.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText로 표현된 페이지 번호 형식 문자열. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### 참조

* 클래스 [FormattedText](../../formattedtext/)
* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

문서의 페이지에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formatString | String | 페이지 번호 형식 문자열. |
| position | Int32 | 페이지 번호가 페이지에 배치될 위치. 0-하단 중앙, 1-하단 오른쪽, 2-상단 오른쪽, 3-측면 오른쪽, 4-상단 중앙, 5-하단 왼쪽, 6-측면 왼쪽, 7-상단 왼쪽. 다음 상수를 사용할 수 있습니다: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | 페이지의 왼쪽 가장자리 여백. |
| rightMargin | Single | 페이지의 오른쪽 가장자리 여백. |
| topMargin | Single | 페이지의 상단 가장자리 여백. |
| bottomMargin | Single | 페이지의 하단 가장자리 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 참조

* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

지정된 위치에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formatString | String | 형식 문자열. 형식 문자열에는 페이지 번호로 대체될 # 기호가 포함될 수 있습니다. |
| x | Single | 페이지 번호의 X 좌표. |
| y | Single | 페이지 번호의 Y 좌표. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 참조

* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

문서의 페이지에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 페이지 번호 형식과 텍스트 속성을 나타내는 FormattedText 객체. |
| position | Int32 | 페이지 번호가 페이지에 배치될 위치. 0-하단 중앙, 1-하단 오른쪽, 2-상단 오른쪽, 3-측면 오른쪽, 4-상단 중앙, 5-하단 왼쪽, 6-측면 왼쪽, 7-상단 왼쪽. 다음 상수를 사용할 수 있습니다: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | 페이지의 왼쪽 가장자리 여백. |
| rightMargin | Single | 페이지의 오른쪽 가장자리 여백. |
| topMargin | Single | 페이지의 상단 가장자리 여백. |
| bottomMargin | Single | 페이지의 하단 가장자리 여백. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 참조

* 클래스 [FormattedText](../../formattedtext/)
* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

지정된 위치에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 페이지 번호 형식과 텍스트 속성을 나타내는 포맷된 텍스트. 형식 문자열에는 페이지 번호로 대체될 # 기호가 포함될 수 있습니다. |
| x | Single | 페이지 번호의 X 좌표. |
| y | Single | 페이지 번호의 Y 좌표. |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 참조

* 클래스 [FormattedText](../../formattedtext/)
* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

페이지에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(string formatString, int position)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formatString | String | 페이지 번호의 형식. 이 텍스트에는 페이지 번호로 대체될 #가 포함될 수 있습니다. |
| position | Int32 | 페이지 번호가 페이지에 배치될 위치. 0-하단 중앙, 1-하단 오른쪽, 2-상단 오른쪽, 3-측면 오른쪽, 4-상단 중앙, 5-하단 왼쪽, 6-측면 왼쪽, 7-상단 왼쪽. 다음 상수를 사용할 수 있습니다: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 참조

* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

페이지에 페이지 번호를 추가합니다.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formattedText | FormattedText | 페이지 번호 형식과 텍스트 속성을 포함하는 FormattedText 객체. 이 텍스트에는 페이지 번호로 대체될 #가 포함될 수 있습니다. |
| position | Int32 | 페이지 번호가 페이지에 배치될 위치. 0-하단 중앙, 1-하단 오른쪽, 2-상단 오른쪽, 3-측면 오른쪽, 4-상단 중앙, 5-하단 왼쪽, 6-측면 왼쪽, 7-상단 왼쪽. 다음 상수를 사용할 수 있습니다: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 참조

* 클래스 [FormattedText](../../formattedtext/)
* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)