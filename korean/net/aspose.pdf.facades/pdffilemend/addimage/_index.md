---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: PdfFileMend 메서드. 지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 입력 이미지 스트림. |
| pageNum | Int32 | 이미지를 받을 페이지 번호. |
| lowerLeftX | Single | 이미지 사각형의 왼쪽 아래 x. |
| lowerLeftY | Single | 이미지 사각형의 왼쪽 아래 y. |
| upperRightX | Single | 이미지 사각형의 오른쪽 위 x. |
| upperRightY | Single | 이미지 사각형의 오른쪽 위 y. |

### 반환 값

성공하면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### 참조

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 입력 이미지 스트림. |
| pageNum | Int32 | 이미지를 받을 페이지 번호. |
| lowerLeftX | Single | 이미지 사각형의 왼쪽 아래 x. |
| lowerLeftY | Single | 이미지 사각형의 왼쪽 아래 y. |
| upperRightX | Single | 이미지 사각형의 오른쪽 위 x. |
| upperRightY | Single | 이미지 사각형의 오른쪽 위 y. |
| compositingParameters | CompositingParameters | 이미지의 그래픽 합성 매개변수. |

### 반환 값

성공하면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### 참조

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 입력 이미지 스트림. |
| pageNums | Int32[] | 이미지를 받을 페이지 번호들. |
| lowerLeftX | Single | 이미지 사각형의 왼쪽 아래 x. |
| lowerLeftY | Single | 이미지 사각형의 왼쪽 아래 y. |
| upperRightX | Single | 이미지 사각형의 오른쪽 위 x. |
| upperRightY | Single | 이미지 사각형의 오른쪽 위 y. |

### 반환 값

성공하면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### 참조

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageStream | Stream | 입력 이미지 스트림. |
| pageNums | Int32[] | 이미지를 받을 페이지 번호들. |
| lowerLeftX | Single | 이미지 사각형의 왼쪽 아래 x. |
| lowerLeftY | Single | 이미지 사각형의 왼쪽 아래 y. |
| upperRightX | Single | 이미지 사각형의 오른쪽 위 x. |
| upperRightY | Single | 이미지 사각형의 오른쪽 위 y. |
| compositingParameters | CompositingParameters | 이미지의 그래픽 합성 매개변수. |

### 반환 값

성공하면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### 참조

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageName | String | 입력 이미지 파일의 경로. |
| pageNum | Int32 | 이미지를 받을 페이지 번호. |
| lowerLeftX | Single | 이미지 사각형의 왼쪽 아래 x. |
| lowerLeftY | Single | 이미지 사각형의 왼쪽 아래 y. |
| upperRightX | Single | 이미지 사각형의 오른쪽 위 x. |
| upperRightY | Single | 이미지 사각형의 오른쪽 위 y. |

### 반환 값

성공하면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 참조

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageName | String | 입력 이미지 파일의 경로. |
| pageNum | Int32 | 이미지를 받을 페이지 번호. |
| lowerLeftX | Single | 이미지 사각형의 왼쪽 아래 x. |
| lowerLeftY | Single | 이미지 사각형의 왼쪽 아래 y. |
| upperRightX | Single | 이미지 사각형의 오른쪽 위 x. |
| upperRightY | Single | 이미지 사각형의 오른쪽 위 y. |
| compositingParameters | CompositingParameters | 이미지의 그래픽 합성 매개변수. |

### 반환 값

성공하면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 참조

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageName | String | 입력 이미지 파일의 경로. |
| pageNums | Int32[] | 이미지를 받을 페이지 번호들. |
| lowerLeftX | Single | 이미지 사각형의 왼쪽 아래 x. |
| lowerLeftY | Single | 이미지 사각형의 왼쪽 아래 y. |
| upperRightX | Single | 이미지 사각형의 오른쪽 위 x. |
| upperRightY | Single | 이미지 사각형의 오른쪽 위 y. |

### 반환 값

성공하면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 참조

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

지정된 좌표에서 PDF 문서의 지정된 페이지에 이미지를 추가합니다.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageName | String | 입력 이미지 파일의 경로. |
| pageNums | Int32[] | 이미지를 받을 페이지 번호들. |
| lowerLeftX | Single | 이미지 사각형의 왼쪽 아래 x. |
| lowerLeftY | Single | 이미지 사각형의 왼쪽 아래 y. |
| upperRightX | Single | 이미지 사각형의 오른쪽 위 x. |
| upperRightY | Single | 이미지 사각형의 오른쪽 위 y. |
| compositingParameters | CompositingParameters | 이미지의 그래픽 합성 매개변수. |

### 반환 값

성공하면 True, 그렇지 않으면 false.

## 예제

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 참조

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)