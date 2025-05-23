---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metodu. Tüm sayfalar için yer imleri oluşturur
type: docs
weight: 30
url: /tr/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Tüm sayfalar için yer imleri oluşturur.

```csharp
public void CreateBookmarks()
```

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Belirtilen yer imini belgede oluşturur. Bu yöntem, iç içe yer imleri hiyerarşisi oluşturmak için kullanılabilir.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bookmark | Bookmark | Yer imi belgeye eklenecektir. |

## Örnekler

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

### Ayrıca Bakınız

* sınıf [Bookmark](../../bookmark/)
* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Belirtilen renk ve stil (kalın, italik) ile tüm sayfalar için yer imleri oluşturur.

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | Color | Başlığın rengi. |
| boldFlag | Boolean | Kalın atıf bayrağı. |
| italicFlag | Boolean | İtalik atıf bayrağı. |

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)