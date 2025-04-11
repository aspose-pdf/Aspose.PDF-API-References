---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Извлекает страницы из входных файлов и сохраняет как новый файл Pdf
type: docs
weight: 280
url: /ru/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Извлекает страницы из входного файла, сохраняет как новый файл Pdf.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу Pdf. |
| startPage | Int32 | Номер начальной страницы. |
| endPage | Int32 | Номер конечной страницы. |
| outputFile | String | Путь к выходному файлу Pdf. |

### Возвращаемое значение

True при успешном выполнении, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Извлекает страницы, указанные массивом номеров, сохраняет как новый файл PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Извлекает страницы из входного файла, сохраняет как новый файл Pdf.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного файла. |
| startPage | Int32 | Номер начальной страницы. |
| endPage | Int32 | Номер конечной страницы. |
| outputStream | Stream | Поток выходного файла Pdf. |

### Возвращаемое значение

True при успешном выполнении, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Извлекает страницы, указанные массивом номеров, сохраняет как новый файл Pdf.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного файла. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputStream | Stream | Поток выходного файла. |

### Возвращаемое значение

True при успешном выполнении, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)