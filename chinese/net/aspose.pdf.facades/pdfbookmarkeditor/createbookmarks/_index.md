---
title: CreateBookmarks
second_title: Aspose.PDF for .NET API 参考
description: 为所有页面创建书签
type: docs
weight: 30
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

为所有页面创建书签。

```csharp
public void CreateBookmarks()
```

### 例子

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* 部件 [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

在文档中创建指定的书签。该方法可用于形成嵌套书签层次结构。

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bookmark | Bookmark | 书签将添加到文档中。 |

### 例子

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

### 也可以看看

* class [Bookmark](../../bookmark)
* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* 部件 [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

为具有指定颜色和样式（粗体、斜体）的所有页面创建书签。

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | Color | 标题的颜色。 |
| boldFlag | Boolean | 大胆归因的旗帜。 |
| italicFlag | Boolean | 斜体归属标志。 |

### 例子

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
