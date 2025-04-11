---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 메서드. 모든 페이지에 대한 북마크를 생성합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

모든 페이지에 대한 북마크를 생성합니다.

```csharp
public void CreateBookmarks()
```

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### 참조

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

문서에 지정된 북마크를 생성합니다. 이 메서드는 중첩된 북마크 계층 구조를 형성하는 데 사용할 수 있습니다.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bookmark | Bookmark | 문서에 추가될 북마크입니다. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bm1=new Bookmark();
bm1.PageNumber=1;
bm1.Title="First child";
Bookmark bm2=new Bookmark();
bm2.PageNumber=2;
bm2.Title="Second child";
Bookmark bm=new Bookmark();
bm.Action="GoTo";
bm.PageNumber=1;
bm.Title="Parent";
Bookmarks bms=new Bookmarks();
bms.Add(bm1);
bms.Add(bm2);
bm.ChildItem=bms;
editor.CreateBookmarks(bm);
editor.Save("example_out.pdf");
```

### 참조

* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

지정된 색상과 스타일(굵게, 기울임꼴)로 모든 페이지에 대한 북마크를 생성합니다.

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| color | Color | 제목의 색상입니다. |
| boldFlag | Boolean | 굵게 속성의 플래그입니다. |
| italicFlag | Boolean | 기울임꼴 속성의 플래그입니다. |

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### 참조

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)