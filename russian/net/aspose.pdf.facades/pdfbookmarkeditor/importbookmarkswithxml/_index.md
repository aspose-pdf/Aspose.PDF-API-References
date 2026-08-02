---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfBookmarkEditor. Импортирует закладки в документ из XML‑файла"
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Импортирует закладки в document из файла XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | String | XML‑файл, содержащий список закладок. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### См. также

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Импортирует закладки в document из файла XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток с данными закладок. |

### См. также

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


