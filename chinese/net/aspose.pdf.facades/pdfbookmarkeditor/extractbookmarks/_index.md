---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 方法。提取文档中所有级别的书签
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

提取文档中所有级别的书签。

```csharp
public Bookmarks ExtractBookmarks()
```

### 返回值

文档中存在的所有书签的书签集合。

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 另见

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

提取文档中所有级别的书签。

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| upperLevel | 布尔 | 如果为 true，则仅提取上级书签。否则，递归提取所有书签。 |

### 返回值

提取的书签列表。

### 另见

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

提取具有指定标题的书签。

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| title | 字符串 | 提取的项目标题。 |

### 返回值

书签集合包含具有相同标题的项目。

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 另见

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

提取具有指定书签中标题的子书签。

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bookmark | 书签 | 指定的书签。 |

### 返回值

包含子书签的书签集合。

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 另见

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)