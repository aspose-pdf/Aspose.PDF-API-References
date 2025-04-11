---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfBookmarkEditor. Извлекает закладки всех уровней из документа
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Извлекает закладки всех уровней из документа.

```csharp
public Bookmarks ExtractBookmarks()
```

### Return Value

Коллекция закладок всех закладок, которые существуют в документе.

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

Извлекает закладки всех уровней из документа.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel | Boolean | Если true, извлекает только закладки верхнего уровня. В противном случае извлекает все закладки рекурсивно. |

### Return Value

Список извлеченных закладок.

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| title | String | Заголовок извлеченного элемента. |

### Return Value

Коллекция закладок содержит элементы с одинаковым заголовком.

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

Извлекает дочерние элементы закладки с заголовком, как в указанной закладке.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | Bookmark | Указанная закладка. |

### Return Value

Коллекция закладок с дочерними закладками.

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