---
title: "PdfBookmarkEditor.CreateBookmarks"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfBookmarkEditor. Создаёт закладки для всех страниц"
type: docs
weight: 30
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Создает закладки для всех pages.

```csharp
public void CreateBookmarks()
```

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### См. также

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Создает указанную закладку в document. Этот метод можно использовать для формирования иерархии вложенных закладок.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| закладка | Закладка | Закладка будет добавлена в документ. |

## Примеры

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

### См. также

* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Создайте закладки для всех pages с указанным цветом и стилем (жирный, курсив).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | Color | Цвет заголовка. |
| boldFlag | Boolean | Флаг жирного начертания. |
| italicFlag | Boolean | Флаг курсивного начертания. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### См. также

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


