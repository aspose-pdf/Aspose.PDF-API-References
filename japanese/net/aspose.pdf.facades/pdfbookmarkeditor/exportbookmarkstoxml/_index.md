---
title: "PdfBookmarkEditor.ExportBookmarksToXML"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfBookmarkEditor メソッド。ブックマークを XML ファイルにエクスポートします"
type: docs
weight: 50
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

ブックマークを XML ファイルにエクスポートします。

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| xmlFile | String | 出力 XML ファイルです。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

ブックマークを XML ストリームにエクスポートします。

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | データが保存される出力ストリームです。 |

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


