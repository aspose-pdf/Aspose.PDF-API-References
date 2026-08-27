---
title: "PdfBookmarkEditor.CreateBookmarkOfPage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfBookmarkEditor メソッド。指定されたページのブックマークを作成します。"
type: docs
weight: 20
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

指定されたページのブックマークを作成します。

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| bookmarkName | String | 指定されたブックマーク名。 |
| pageNumber | Int32 | 指定された宛先ページ。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

指定されたページのブックマークを作成します。

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| bookmarkName | String[] | ブックマークのタイトル配列。 |
| pageNumber | Int32[] | ブックマークの宛先ページ配列。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


