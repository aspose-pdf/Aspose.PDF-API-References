---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor メソッド。指定されたページのブックマークを作成します。
type: docs
weight: 20
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

指定されたページのブックマークを作成します。

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bookmarkName | String | 指定されたブックマーク名。 |
| pageNumber | Int32 | 指定された目的地ページ。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfBookmarkEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

指定されたページのブックマークを作成します。

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bookmarkName | String[] | ブックマークタイトルの配列。 |
| pageNumber | Int32[] | ブックマークの目的地ページの配列。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfBookmarkEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)