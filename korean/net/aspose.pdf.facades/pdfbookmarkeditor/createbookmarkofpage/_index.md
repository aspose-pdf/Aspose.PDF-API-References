---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 메서드. 지정된 페이지에 대한 북마크를 생성합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

지정된 페이지에 대한 북마크를 생성합니다.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bookmarkName | String | 지정된 북마크 이름. |
| pageNumber | Int32 | 지정된 대상 페이지. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### 참조

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

지정된 페이지에 대한 북마크를 생성합니다.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bookmarkName | String[] | 북마크 제목 배열. |
| pageNumber | Int32[] | 북마크 대상 페이지 배열. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### 참조

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)