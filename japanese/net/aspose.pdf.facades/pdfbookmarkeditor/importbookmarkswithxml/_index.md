---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfBookmarkEditor メソッド。XML ファイルからドキュメントへブックマークをインポートします"
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

XML ファイルから Document にブックマークをインポートします。

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| xmlFile | String | ブックマーク一覧を含む XML ファイルです。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

XML ファイルから Document にブックマークをインポートします。

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ブックマークデータを含むストリームです。 |

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


