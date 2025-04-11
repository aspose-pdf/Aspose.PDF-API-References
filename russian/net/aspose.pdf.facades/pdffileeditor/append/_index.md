---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Добавляет страницы, которые выбраны из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage
type: docs
weight: 250
url: /ru/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Добавляет страницы, которые выбраны из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной Pdf поток. |
| portStreams | Stream[] | Документы, из которых копируются страницы. |
| startPage | Int32 | Страница начинается в документах portStreams. |
| endPage | Int32 | Страница заканчивается в документах portStreams. |
| outputStream | Stream | Выходной Pdf поток. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Добавляет страницы, которые выбраны из документов portFiles. Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной Pdf файл. |
| portFiles | String[] | Документы, из которых копируются страницы. |
| startPage | Int32 | Страница начинается в документах portFiles. |
| endPage | Int32 | Страница заканчивается в документах portFiles. |
| outputFile | String | Выходной Pdf документ. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Добавляет страницы, которые выбраны из portFile в диапазоне от startPage до endPage, в portFile в конце firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной Pdf файл. |
| portFile | String | Страницы из Pdf файла. |
| startPage | Int32 | Страница начинается в portFile. |
| endPage | Int32 | Страница заканчивается в portFile. |
| outputFile | String | Выходной Pdf документ. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Добавляет страницы, которые выбраны из portStream в диапазоне от startPage до endPage, в portStream в конце firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной файл Stream. |
| portStream | Stream | Страницы из Pdf файла Stream. |
| startPage | Int32 | Страница начинается в portFile Stream. |
| endPage | Int32 | Страница заканчивается в portFile Stream. |
| outputStream | Stream | Выходной Pdf файл Stream. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)