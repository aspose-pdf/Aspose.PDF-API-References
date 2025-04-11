---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 메서드. 문서에서 모든 수준의 북마크를 추출합니다.
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

문서에 존재하는 모든 북마크의 북마크 컬렉션입니다.

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 참조

* 클래스 [Bookmarks](../../bookmarks/)
* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

문서에서 모든 수준의 북마크를 추출합니다.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| upperLevel | Boolean | true인 경우, 상위 수준의 북마크만 추출합니다. 그렇지 않으면 모든 북마크를 재귀적으로 추출합니다. |

### 반환 값

추출된 북마크 목록입니다.

### 참조

* 클래스 [Bookmarks](../../bookmarks/)
* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

지정된 제목의 북마크를 추출합니다.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| title | String | 추출된 항목 제목입니다. |

### 반환 값

같은 제목을 가진 항목이 있는 북마크 컬렉션입니다.

## 예제

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 참조

* 클래스 [Bookmarks](../../bookmarks/)
* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

지정된 북마크와 같은 제목을 가진 북마크의 자식을 추출합니다.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bookmark | Bookmark | 지정된 북마크입니다. |

### 반환 값

자식 북마크가 포함된 북마크 컬렉션입니다.

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

### 참조

* 클래스 [Bookmarks](../../bookmarks/)
* 클래스 [Bookmark](../../bookmark/)
* 클래스 [PdfBookmarkEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)