---
title: "PdfFileEditor.SplitToBulks"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfFileEditor метод. Разделяет файл PDF на несколько документов. Документы могут быть одностраничными или многостраничными."
type: docs
weight: 350
url: /ru/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Разделяет Pdf‑файл на несколько документов. Документы могут быть одностраничными или многостраничными.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл PDF. |
| numberOfPage | Int32[][] | Массив, содержащий массив элементов double, представляющих начальные и конечные страницы документа. |

### Возвращаемое значение

Выходные потоки PDF, каждый поток буферизует документ PDF.

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Разделяет Pdf‑файл на несколько документов. Документы могут быть одностраничными или многостраничными.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток PDF. |
| numberOfPage | Int32[][] | Начальная и конечная страницы каждого документа. |

### Возвращаемое значение

Выходные потоки PDF, каждый поток буферизует документ PDF.

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


