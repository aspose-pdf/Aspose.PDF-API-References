---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfBookmarkEditor. تنشئ إشارات مرجعية لجميع الصفحات
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

تنشئ إشارات مرجعية لجميع الصفحات.

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

تنشئ الإشارة المرجعية المحددة في المستند. يمكن استخدام الطريقة لتشكيل تسلسل هرمي للإشارات المرجعية المتداخلة.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | Bookmark | ستتم إضافة الإشارة المرجعية إلى المستند. |

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

إنشاء إشارات مرجعية لجميع الصفحات مع اللون والنمط المحددين (عريض، مائل).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| color | Color | لون العنوان. |
| boldFlag | Boolean | علامة نسبة العريض. |
| italicFlag | Boolean | علامة نسبة المائل. |

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