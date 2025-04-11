---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Вставляет страницы из другого файла в Pdf файл в указанное место
type: docs
weight: 290
url: /ru/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Вставляет страницы из другого файла в Pdf файл в указанное место.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной Pdf файл. |
| insertLocation | Int32 | Позиция во входном файле. |
| portFile | String | Портируемый Pdf файл. |
| startPage | Int32 | Начальная позиция в portFile. |
| endPage | Int32 | Конечная позиция в portFile. |
| outputFile | String | Выходной Pdf файл. |

### Возвращаемое значение

True при успехе, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Вставляет страницы из другого файла во входной Pdf файл.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток Pdf файла. |
| insertLocation | Int32 | Позиция вставки во входном файле. |
| portStream | Stream | Поток Pdf файла для страниц. |
| startPage | Int32 | С какой страницы начинать. |
| endPage | Int32 | На какой странице заканчивать. |
| outputStream | Stream | Выходной поток. |

### Возвращаемое значение

True при успехе, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Вставляет страницы из другого файла во входной Pdf файл.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной Pdf файл. |
| insertLocation | Int32 | Позиция вставки во входном файле. |
| portFile | String | Страницы из Pdf файла. |
| pageNumber | Int32[] | Номер страницы, портируемой в portFile. |
| outputFile | String | Выходной Pdf файл. |

### Возвращаемое значение

True при успехе, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Вставляет страницы из другого файла во входной Pdf файл.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток Pdf файла. |
| insertLocation | Int32 | Позиция вставки во входном файле. |
| portStream | Stream | Поток Pdf файла для страниц. |
| pageNumber | Int32[] | Номер страницы, портируемой в portFile. |
| outputStream | Stream | Выходной поток. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)