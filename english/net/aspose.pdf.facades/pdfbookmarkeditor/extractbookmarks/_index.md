---
title: "PdfBookmarkEditor.ExtractBookmarks"
linktitle: "ExtractBookmarks"
articleTitle: "ExtractBookmarks"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfBookmarkEditor method. Extracts bookmarks of all levels from the document."
type: docs
weight: 110
url: "/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/"
product_version: "26.9.0"
---
## ExtractBookmarks() {#extractbookmarks}

Extracts bookmarks of all levels from the document.

```csharp
public Bookmarks ExtractBookmarks()
```

### Return Value

The bookmarks collection of all bookmarks that exist in the document.

### See Also

* class [Bookmarks](../../../aspose.pdf.facades/bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_1}

Extracts bookmarks of all levels from the document.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel | Boolean | If true, extracts only upper level bookmarks. Else, extracts all bookmarks recursively. |

### Return Value

List of extracted bookmarks.

### See Also

* class [Bookmarks](../../../aspose.pdf.facades/bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_2}

Extracts the bookmarks with the specified title.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| title | String | Extracted item title. |

### Return Value

Bookmark collection has items with the same title.

### See Also

* class [Bookmarks](../../../aspose.pdf.facades/bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks([Bookmark](../../../aspose.pdf.facades/bookmark/)) {#extractbookmarks_3}

Extracts the children of a bookmark with a title like in specified bookamrk.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | Bookmark | The specified bookamrk. |

### Return Value

Bookmark collection with child bookmarks.

### See Also

* class [Bookmarks](../../../aspose.pdf.facades/bookmarks/)
* class [Bookmark](../../../aspose.pdf.facades/bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

