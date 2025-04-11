---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor メソッド。XML ファイルからドキュメントにブックマークをインポートします
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

XML ファイルからドキュメントにブックマークをインポートします。

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xmlFile | 文字列 | ブックマークリストを含む XML ファイル。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfBookmarkEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

XML ファイルからドキュメントにブックマークをインポートします。

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | ストリーム | ブックマークデータを含むストリーム。 |

### 参照

* クラス [PdfBookmarkEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)