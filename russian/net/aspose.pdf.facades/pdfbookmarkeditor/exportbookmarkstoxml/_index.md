---
title: "PdfBookmarkEditor.ExportBookmarksToXML"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfBookmarkEditor метод. Экспортирует закладки в XML‑файл"
type: docs
weight: 50
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Экспортирует закладки в файл XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | String | Выходной XML‑файл. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### См. также

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Экспортирует закладки в поток XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток вывода, в котором будут храниться данные. |

### См. также

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


