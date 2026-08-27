---
title: "PdfBookmarkEditor.ExtractBookmarks"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfBookmarkEditor метод. Извлекает закладки всех уровней из документа"
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Извлекает закладки всех уровней из document.

```csharp
public Bookmarks ExtractBookmarks()
```

### Возвращаемое значение

Коллекция закладок всех закладок, существующих в документе.

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### См. также

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Извлекает закладки всех уровней из document.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| upperLevel | Boolean | Если true, извлекает только закладки верхнего уровня. Иначе, извлекает все закладки рекурсивно. |

### Возвращаемое значение

Список извлечённых закладок.

### См. также

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Извлекает закладки с указанным заголовком.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | String | Заголовок извлечённого элемента. |

### Возвращаемое значение

Коллекция закладок содержит элементы с одинаковым заголовком.

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### См. также

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Извлекает дочерние элементы закладки с заголовком, аналогичным указанной закладке.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| закладка | Закладка | Указанная закладка. |

### Возвращаемое значение

Коллекция закладок с дочерними закладками.

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### См. также

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


