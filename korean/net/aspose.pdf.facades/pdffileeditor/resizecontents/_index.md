---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 문서 페이지의 내용을 크기 조정합니다.
type: docs
weight: 320
url: /ko/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

문서의 페이지 내용을 크기 조정합니다.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | Stream | 원본 문서가 있는 스트림입니다. |
| destination | Stream | 대상 문서가 있는 스트림입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. |
| parameters | ContentsResizeParameters | 크기 조정 매개변수입니다. |

### 반환 값

성공하면 true를 반환합니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### 참조

* 클래스 [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 내용의 새로운 크기는 기본 공간 단위로 지정됩니다.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | Stream | 원본 문서를 포함하는 스트림입니다. |
| destination | Stream | 결과 문서가 저장될 스트림입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. null이면 모든 문서 페이지가 처리됩니다. |
| newWidth | Double | 기본 공간 단위로 페이지 내용의 새로운 너비입니다. |
| newHeight | Double | 기본 공간 단위로 페이지 내용의 새로운 높이입니다. |

### 반환 값

크기 조정이 성공하면 true입니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 내용의 새로운 크기는 기본 공간 단위로 지정됩니다.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | String | 원본 문서의 경로입니다. |
| destination | String | 결과 문서가 저장될 경로입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. null이면 모든 문서 페이지가 처리됩니다. |
| newWidth | Double | 기본 공간 단위로 페이지 내용의 새로운 너비입니다. |
| newHeight | Double | 기본 공간 단위로 페이지 내용의 새로운 높이입니다. |

### 반환 값

크기 조정이 성공하면 true입니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

문서의 페이지 내용을 크기 조정합니다. 페이지가 축소되면 페이지 주위에 빈 여백이 추가됩니다.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | String | 원본 문서 경로입니다. |
| destination | String | 대상 문서 경로입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다 (페이지 인덱스는 1부터 시작합니다). |
| parameters | ContentsResizeParameters | 페이지 크기 조정 매개변수입니다. |

### 반환 값

크기 조정이 성공하면 true입니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### 참조

* 클래스 [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

문서의 페이지를 크기 조정합니다. 축소된 페이지 주위에 빈 여백이 추가됩니다.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | Document | 원본 문서입니다. |
| pages | Int32[] | 페이지 인덱스 목록입니다. |
| parameters | ContentsResizeParameters | 크기 조정 매개변수입니다. |

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### 참조

* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

문서의 페이지를 크기 조정합니다. 축소된 페이지 주위에 빈 여백이 추가됩니다.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | Document | 원본 문서입니다. |
| parameters | ContentsResizeParameters | 크기 조정 매개변수입니다. |

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### 참조

* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)