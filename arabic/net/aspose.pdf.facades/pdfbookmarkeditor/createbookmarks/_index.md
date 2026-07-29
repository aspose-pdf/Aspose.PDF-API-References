---
title: "PdfBookmarkEditor.CreateBookmarks"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfBookmarkEditor. تنشئ إشارات مرجعية لجميع الصفحات"
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

ينشئ إشارات مرجعية لجميع الصفحات.

```csharp
public void CreateBookmarks()
```

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

ينشئ الإشارة المرجعية المحددة في PDF Document. يمكن استخدام الطريقة لتكوين تسلسل هرمي للإشارات المرجعية المتداخلة.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| علامة مرجعية | علامة مرجعية | سيتم إضافة الإشارة المرجعية إلى المستند. |

## أمثلة

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

### انظر أيضًا

* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

إنشاء إشارات مرجعية لجميع الصفحات باللون والنمط المحددين (عريض، مائل).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| color | Color | لون العنوان. |
| boldFlag | Boolean | علامة الخط العريض. |
| italicFlag | Boolean | علامة الخط المائل. |

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


