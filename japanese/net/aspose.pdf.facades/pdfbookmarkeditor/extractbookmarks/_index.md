---
title: "PdfBookmarkEditor.ExtractBookmarks"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfBookmarkEditor メソッド。ドキュメントからすべてのレベルのブックマークを抽出します"
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Document からすべてのレベルのブックマークを抽出します。

```csharp
public Bookmarks ExtractBookmarks()
```

### 戻り値

ドキュメントに存在するすべてのブックマークのコレクションです。

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 関連項目

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Document からすべてのレベルのブックマークを抽出します。

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| upperLevel | Boolean | true の場合、上位レベルのブックマークのみを抽出します。false の場合、すべてのブックマークを再帰的に抽出します。 |

### 戻り値

抽出されたブックマークの一覧です。

### 関連項目

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

指定されたタイトルのブックマークを抽出します。

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| title | String | 抽出された項目のタイトル。 |

### 戻り値

ブックマークコレクションに同じタイトルの項目があります。

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 関連項目

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

指定されたブックマークと同様のタイトルを持つブックマークの子要素を抽出します。

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ブックマーク | ブックマーク | 指定された bookamrk。 |

### 戻り値

子ブックマークを含むブックマークコレクションです。

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### 関連項目

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


