---
title: "PdfFileEditor.TryResizeContents"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. 문서 페이지의 내용을 크기 조정합니다."
type: docs
weight: 450
url: /ko/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

문서 페이지의 내용을 크기 조정합니다.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | Stream | 원본 문서가 포함된 스트림입니다. |
| 대상 | Stream | 대상 문서가 포함된 스트림입니다. |
| 페이지 | Int32[] | 페이지 인덱스 배열입니다. |
| 매개변수 | ContentsResizeParameters | 크기 조정 매개변수입니다. |

### 반환 값

성공하면 true를 반환합니다.

## 비고

TryResizeContents 메서드는 ResizeContents 메서드와 유사하지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //왼쪽 여백 = 페이지 너비의 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //새 내용 너비는 자동으로 width - left margin - right margin (100% - 10% - 10% = 80%) 로 계산됩니다.
    null,
    //오른쪽 여백은 페이지의 10%입니다.
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //상단 여백 = 높이의 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //새 내용 높이는 자동으로 계산됩니다 (너비와 유사).
    null,
    //하단 여백은 10%입니다.
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### 또 보기

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
| 소스 | Stream | 원본 문서를 포함하는 스트림. |
| 대상 | Stream | 결과 문서가 저장될 스트림. |
| 페이지 | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| newWidth | Double | 기본 공간 단위로 페이지 내용의 새 너비입니다. |
| newHeight | Double | 기본 공간 단위로 페이지 내용의 새 높이입니다. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryResizeContents 메서드는 ResizeContents 메서드와 유사하지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//문서의 모든 페이지를 크기 조정합니다.
null, 
//새 콘텐츠 너비 = 200
200, 
//새 콘텐츠 높이 = 300
300);
// 페이지의 나머지 영역은 비게 됩니다.
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

문서의 페이지 내용을 크기 조정합니다. 페이지가 축소되면 페이지 주변에 빈 여백이 추가됩니다.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | String | 소스 문서 경로. |
| 대상 | String | 대상 문서 경로. |
| 페이지 | Int32[] | 페이지 인덱스 배열 (페이지 인덱스는 1부터 시작합니다). |
| 매개변수 | ContentsResizeParameters | 페이지 크기 조정 매개변수. |

### 반환 값

크기 조정이 성공하면 true입니다.

## 비고

TryResizeContents 메서드는 ResizeContents 메서드와 유사하지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //왼쪽 여백 = 페이지 너비의 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //새 내용 너비는 자동으로 width - left margin - right margin (100% - 10% - 10% = 80%) 로 계산됩니다.
    null,
    //오른쪽 여백은 페이지의 10%입니다.
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //상단 여백 = 높이의 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //새 내용 높이는 자동으로 계산됩니다 (너비와 유사).
    null,
    //하단 여백은 10%입니다.
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### 또 보기

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


