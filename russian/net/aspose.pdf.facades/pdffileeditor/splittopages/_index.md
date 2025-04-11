---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Разделяет PDF-файл на документы с одной страницей
type: docs
weight: 370
url: /ru/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Разделяет PDF-файл на документы с одной страницей.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя входного PDF-файла. |

### Возвращаемое значение

Выходные PDF-потоки, каждый поток буферизует документ с одной страницей.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Разделяет Pdf-файл на документы с одной страницей.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток Pdf. |

### Возвращаемое значение

Массив потоков памяти, содержащих страницы документа.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Разделяет Pdf-файл на документы с одной страницей и сохраняет его в указанном пути. Путь указывается с помощью имени шаблона поля.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя входного файла. |
| fileNameTemplate | String | Шаблон имени результирующего файла. Должен содержать %NUM%, который заменяется номером страницы. Например, если указан c:/dir/page%NUM%.pdf, результирующие файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т.д. |

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Разделяет Pdf-файл на документы с одной страницей и сохраняет его в указанном пути. Путь указывается с помощью имени шаблона поля.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| fileNameTemplate | String | Шаблон имени результирующего файла. Должен содержать %NUM%, который заменяется номером страницы. Например, если указан c:/dir/page%NUM%.pdf, результирующие файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т.д. |

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)