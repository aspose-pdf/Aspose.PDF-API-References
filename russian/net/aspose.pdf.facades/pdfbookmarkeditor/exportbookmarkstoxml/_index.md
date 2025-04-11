---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfBookmarkEditor. Экспортирует закладки в XML файл
type: docs
weight: 50
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Экспортирует закладки в XML файл.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | String | Выходной XML файл. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### См. также

* класс [PdfBookmarkEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Экспортирует закладки в XML поток.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Выходной поток, в который будут сохранены данные. |

### См. также

* класс [PdfBookmarkEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)