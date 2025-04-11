---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor メソッド。すべてのページのブックマークを作成します
type: docs
weight: 30
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

すべてのページのブックマークを作成します。

```csharp
public void CreateBookmarks()
```

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

ドキュメントに指定されたブックマークを作成します。このメソッドは、ネストされたブックマーク階層を形成するために使用できます。

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bookmark | Bookmark | ブックマークがドキュメントに追加されます。 |

## 例

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

### 関連項目

* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

指定された色とスタイル（太字、斜体）で、すべてのページのブックマークを作成します。

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | Color | タイトルの色。 |
| boldFlag | Boolean | 太字属性のフラグ。 |
| italicFlag | Boolean | 斜体属性のフラグ。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)