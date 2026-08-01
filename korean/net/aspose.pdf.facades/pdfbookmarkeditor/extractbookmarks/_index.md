---
title: "PdfBookmarkEditor.ExtractBookmarks"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfBookmarkEditor 메서드. 문서에서 모든 수준의 북마크를 추출합니다"
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

문서에서 모든 수준의 북마크를 추출합니다.

```csharp
public Bookmarks ExtractBookmarks()
```

### 반환 값

문서에 존재하는 모든 북마크의 북마크 컬렉션.

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 또 보기

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

문서에서 모든 수준의 북마크를 추출합니다.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| upperLevel | Boolean | true이면 상위 수준 북마크만 추출합니다. 아니면 모든 북마크를 재귀적으로 추출합니다. |

### 반환 값

추출된 북마크 목록.

### 또 보기

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

지정된 제목을 가진 북마크를 추출합니다.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 제목 | String | 추출된 항목 제목. |

### 반환 값

북마크 컬렉션에 동일한 제목을 가진 항목이 있습니다.

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 또 보기

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

지정된 북마크와 같은 제목을 가진 북마크의 하위 항목을 추출합니다.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 북마크 | 북마크 | 지정된 bookamrk. |

### 반환 값

자식 북마크가 포함된 북마크 컬렉션.

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 또 보기

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


