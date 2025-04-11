---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 方法。为指定页面创建书签
type: docs
weight: 20
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

为指定页面创建书签。

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bookmarkName | String | 指定的书签名称。 |
| pageNumber | Int32 | 指定的目标页面。 |

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

为指定页面创建书签。

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bookmarkName | String[] | 书签标题数组。 |
| pageNumber | Int32[] | 书签目标页面数组。 |

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)