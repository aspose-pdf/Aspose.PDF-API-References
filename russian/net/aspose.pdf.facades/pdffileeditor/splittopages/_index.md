---
title: "PdfFileEditor.SplitToPages"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Разделяет файл PDF на одностраничные документы."
type: docs
weight: 370
url: /ru/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Разделяет PDF‑файл на одностраничные документы.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя входного PDF файла. |

### Возвращаемое значение

Выходные потоки PDF, каждый поток буферизует одностраничный документ PDF.

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Разделяет Pdf‑файл на одностраничные документы.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток Pdf. |

### Возвращаемое значение

Массив потоков памяти, содержащих страницы документа.

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Разделяет Pdf‑файл на одностраничные документы и сохраняет его в указанный путь. Путь задаётся именем поля template.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя входного файла. |
| fileNameTemplate | String | Шаблон итогового имени файла. Должен содержать %NUM%, который заменяется номером страницы. Например, если указано c:/dir/page%NUM%.pdf, итоговые файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т.д. |

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Разделяет Pdf‑файл на одностраничные документы и сохраняет его в указанный путь. Путь задаётся именем поля template.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| fileNameTemplate | String | Шаблон итогового имени файла. Должен содержать %NUM%, который заменяется номером страницы. Например, если указано c:/dir/page%NUM%.pdf, итоговые файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т.д. |

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


