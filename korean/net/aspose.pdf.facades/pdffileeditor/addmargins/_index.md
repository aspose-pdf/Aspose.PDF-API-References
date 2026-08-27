---
title: "PdfFileEditor.AddMargins"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 기본 공간 단위로 지정됩니다."
type: docs
weight: 220
url: /ko/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 기본 공간 단위로 지정됩니다.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | Stream | 원본 문서를 포함하는 스트림. |
| 대상 | Stream | 결과 문서가 저장될 스트림. |
| 페이지 | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| leftMargin | Double | 왼쪽 여백. |
| rightMargin | Double | 오른쪽 여백. |
| topMargin | Double | 위쪽 여백. |
| bottomMargin | Double | 아래쪽 여백. |

### 반환 값

작업이 성공했으면 true.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //페이지 1, 2, 3을 처리합니다
    new int[] { 1, 2, 3}, 
    //왼쪽 여백은 10 단위입니다
    10, 
    //오른쪽 여백은 5 단위입니다
    5, 
    //상단 여백은 5 단위입니다.
    5, 
    //하단 여백은 5 단위입니다.
    5);
    dest.Close();
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 기본 공간 단위로 지정됩니다.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | String | 원본 문서의 경로입니다. |
| 대상 | String | 결과 문서가 저장될 경로입니다. |
| 페이지 | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| leftMargin | Double | 왼쪽 여백. |
| rightMargin | Double | 오른쪽 여백. |
| topMargin | Double | 위쪽 여백. |
| bottomMargin | Double | 아래쪽 여백. |

### 반환 값

크기 조정이 성공하면 true입니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //페이지 1, 2, 3을 처리합니다
    new int[] { 1, 2, 3}, 
    //왼쪽 여백은 10 단위입니다
    10, 
    //오른쪽 여백은 5 단위입니다
    5, 
    //상단 여백은 5 단위입니다.
    5, 
    //하단 여백은 5 단위입니다.
    5);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


