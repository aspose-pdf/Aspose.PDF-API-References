---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfBookmarkEditor. تستخرج العلامات المرجعية من جميع المستويات من الوثيقة
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

تستخرج العلامات المرجعية من جميع المستويات من الوثيقة.

```csharp
public Bookmarks ExtractBookmarks()
```

### Return Value

مجموعة العلامات المرجعية لجميع العلامات المرجعية الموجودة في الوثيقة.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

تستخرج العلامات المرجعية من جميع المستويات من الوثيقة.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel | Boolean | إذا كانت صحيحة، تستخرج فقط العلامات المرجعية من المستوى الأعلى. خلاف ذلك، تستخرج جميع العلامات المرجعية بشكل متكرر. |

### Return Value

قائمة بالعلامات المرجعية المستخرجة.

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

تستخرج العلامات المرجعية بالعنوان المحدد.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| title | String | عنوان العنصر المستخرج. |

### Return Value

مجموعة العلامات المرجعية تحتوي على عناصر بنفس العنوان.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

تستخرج الأطفال من علامة مرجعية بعنوان مشابه للعلامة المرجعية المحددة.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | Bookmark | العلامة المرجعية المحددة. |

### Return Value

مجموعة العلامات المرجعية مع العلامات المرجعية الفرعية.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)