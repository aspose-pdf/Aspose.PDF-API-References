---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Разделяет файл Pdf на несколько документов. Документы могут быть одностраничными или многопстраничными
type: docs
weight: 350
url: /ru/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Разделяет файл Pdf на несколько документов. Документы могут быть одностраничными или многопстраничными.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной PDF файл. |
| numberOfPage | Int32[][] | Массив, который содержит массив двойных элементов, представляющих начальные и конечные страницы документа. |

### Возвращаемое значение

Выходные PDF потоки, каждый поток буферизует PDF документ.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Разделяет файл Pdf на несколько документов. Документы могут быть одностраничными или многопстраничными.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной PDF поток. |
| numberOfPage | Int32[][] | Начальная и конечная страницы каждого документа. |

### Возвращаемое значение

Выходные PDF потоки, каждый поток буферизует PDF документ.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)