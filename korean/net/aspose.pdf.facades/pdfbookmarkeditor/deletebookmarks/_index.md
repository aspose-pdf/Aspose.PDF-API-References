---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfBookmarkEditor 메서드. PDF 문서의 모든 북마크를 삭제합니다"
type: docs
weight: 40
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

PDF 문서의 모든 북마크를 삭제합니다.

```csharp
public void DeleteBookmarks()
```

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

PDF 문서의 북마크를 삭제합니다.

```csharp
public void DeleteBookmarks(string title)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 제목 | String | 삭제된 북마크의 제목. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


