---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 초기 페이지 크기의 백분율로 지정됩니다.
type: docs
weight: 230
url: /ko/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 초기 페이지 크기의 백분율로 지정됩니다.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | 원본 문서가 포함된 스트림입니다. |
| destination | Stream | 결과 문서가 저장될 스트림입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| leftMargin | Double | 초기 페이지 크기의 백분율로 왼쪽 여백입니다. |
| rightMargin | Double | 초기 페이지 크기의 백분율로 오른쪽 여백입니다. |
| topMargin | Double | 초기 페이지 크기의 백분율로 위쪽 여백입니다. |
| bottomMargin | Double | 초기 페이지 크기의 백분율로 아래쪽 여백입니다. |

### Return Value

작업이 성공적으로 수행되면 true입니다.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

페이지 내용을 크기 조정하고 지정된 여백을 추가합니다. 여백은 초기 페이지 크기의 백분율로 지정됩니다.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | 원본 문서의 경로입니다. |
| destination | String | 결과 문서가 저장될 경로입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| leftMargin | Double | 초기 페이지 크기의 백분율로 왼쪽 여백입니다. |
| rightMargin | Double | 초기 페이지 크기의 백분율로 오른쪽 여백입니다. |
| topMargin | Double | 초기 페이지 크기의 백분율로 위쪽 여백입니다. |
| bottomMargin | Double | 초기 페이지 크기의 백분율로 아래쪽 여백입니다. |

### Return Value

크기 조정이 성공적이면 true입니다.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)