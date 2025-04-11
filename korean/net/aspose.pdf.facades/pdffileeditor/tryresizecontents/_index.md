---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 문서의 페이지 내용을 크기 조정합니다.
type: docs
weight: 450
url: /ko/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

문서의 페이지 내용을 크기 조정합니다. 페이지가 축소되면 페이지 주위에 빈 여백이 추가됩니다. 결과는 HttpResponse 객체에 저장됩니다.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | String | 원본 파일의 경로입니다. |
| pages | Int32[] | 크기 조정할 페이지 배열입니다. |
| parameters | ContentsResizeParameters | 크기 조정 매개변수입니다. |
| response | HttpResponse | 결과가 저장되는 HttpResponse 객체입니다. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false입니다.

## 비고

TryResizeContents 메서드는 ResizeContents 메서드와 유사하지만, TryResizeContents 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

문서의 페이지 내용을 크기 조정합니다. 페이지가 축소되면 페이지 주위에 빈 여백이 추가됩니다. 결과는 HttpResponse 객체에 저장됩니다.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | Stream | 원본 파일의 스트림입니다. |
| pages | Int32[] | 크기 조정할 페이지 배열입니다. |
| parameters | ContentsResizeParameters | 크기 조정 매개변수입니다. |
| response | HttpResponse | 결과가 저장되는 HttpResponse 객체입니다. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false입니다.

## 비고

TryResizeContents 메서드는 ResizeContents 메서드와 유사하지만, TryResizeContents 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

문서의 페이지 내용을 크기 조정합니다.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | Stream | 원본 문서가 포함된 스트림입니다. |
| destination | Stream | 결과 문서가 저장될 스트림입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. |
| parameters | ContentsResizeParameters | 크기 조정 매개변수입니다. |

### 반환 값

성공하면 true를 반환합니다.

## 비고

TryResizeContents 메서드는 ResizeContents 메서드와 유사하지만, TryResizeContents 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### 참조

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 내용의 새로운 크기는 기본 공간 단위로 지정됩니다.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | Stream | 원본 문서를 포함하는 스트림입니다. |
| destination | Stream | 결과 문서가 저장될 스트림입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| newWidth | Double | 기본 공간 단위로 페이지 내용의 새로운 너비입니다. |
| newHeight | Double | 기본 공간 단위로 페이지 내용의 새로운 높이입니다. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false입니다.

## 비고

TryResizeContents 메서드는 ResizeContents 메서드와 유사하지만, TryResizeContents 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

문서의 페이지 내용을 크기 조정합니다. 페이지가 축소되면 페이지 주위에 빈 여백이 추가됩니다.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
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

## 비고

TryResizeContents 메서드는 ResizeContents 메서드와 유사하지만, TryResizeContents 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### 참조

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)