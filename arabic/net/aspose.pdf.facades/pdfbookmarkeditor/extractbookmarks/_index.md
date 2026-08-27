---
title: "PdfBookmarkEditor.ExtractBookmarks"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfBookmarkEditor. تستخرج العلامات المرجعية من جميع المستويات من المستند"
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

يستخرج الإشارات المرجعية من جميع المستويات في Document.

```csharp
public Bookmarks ExtractBookmarks()
```

### قيمة الإرجاع

مجموعة العلامات المرجعية لجميع العلامات المرجعية الموجودة في المستند.

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### انظر أيضًا

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

يستخرج الإشارات المرجعية من جميع المستويات في Document.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| upperLevel | Boolean | إذا كان صحيحًا، يستخرج فقط العلامات المرجعية من المستوى الأعلى. وإلا، يستخرج جميع العلامات المرجعية بشكل متكرر. |

### قيمة الإرجاع

قائمة العلامات المرجعية المستخرجة.

### انظر أيضًا

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

يستخرج الإشارات المرجعية ذات العنوان المحدد.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| title | String | عنوان العنصر المستخرج. |

### قيمة الإرجاع

مجموعة العلامات المرجعية تحتوي على عناصر بنفس العنوان.

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### انظر أيضًا

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

يستخرج العناصر الفرعية لbookmark بعنوان مشابه للعنوان في bookmark المحدد.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| علامة مرجعية | علامة مرجعية | العلامة المرجعية المحددة. |

### قيمة الإرجاع

مجموعة العلامات المرجعية التي تحتوي على علامات مرجعية فرعية.

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### انظر أيضًا

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


