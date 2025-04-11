---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Создает документ NUp из двух входных PDF потоков в outputStream
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Создает документ N-Up из firstInputFile в outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf файла. |
| outputFile | String | Путь и имя выходного pdf файла. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Создает документ N-Up из входного потока и сохраняет результат в выходной поток.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной pdf поток. |
| outputStream | Stream | Выходной pdf поток. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Создает документ N-Up из первого входного потока в выходной поток.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной pdf поток. |
| outputStream | Stream | Выходной pdf поток. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Создает документ N-Up из двух входных PDF файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла и другая из второго входного файла. Две страницы располагаются горизонтально.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | первый входной файл. |
| secondInputFile | String | второй входной файл. |
| outputFile | String | Путь и имя выходного pdf файла. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Создает документ N-Up из двух входных PDF потоков в outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | первый входной поток. |
| secondInputStream | Stream | второй входной поток. |
| outputStream | Stream | Выходной pdf поток. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Создает документ N-Up из нескольких входных PDF файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией страниц из входных файлов с одинаковым номером страницы. Многостраничные документы располагаются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Входные Pdf файлы. |
| outputFile | String | Путь и имя выходного pdf файла. |
| isSidewise | Boolean | Способ укладки, true для горизонтальной и false для вертикальной. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Создает документ N-Up из нескольких входных PDF потоков в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц из входных потоков с одинаковым номером страницы. Многостраничные документы располагаются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStreams | Stream[] | Входные Pdf потоки. |
| outputStream | Stream | Выходной pdf поток. |
| isSidewise | Boolean | Способ укладки, true для горизонтальной и false для вертикальной. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Создает документ N-Up из входного файла в outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf файла. |
| outputFile | String | Путь и имя выходного pdf файла. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Создает документ N-Up из firstInputFile в outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf файла. |
| outputFile | String | Путь и имя выходного pdf файла. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Создает документ N-Up из входного потока и сохраняет результат в выходной поток.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной pdf поток. |
| outputStream | Stream | Выходной pdf поток. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Создает документ N-Up из первого входного потока в выходной поток.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной pdf поток. |
| outputStream | Stream | Выходной pdf поток. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Создает документ N-Up из двух входных PDF файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла и другая из второго входного файла. Две страницы располагаются горизонтально.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | первый входной файл. |
| secondInputFile | String | второй входной файл. |
| outputFile | String | Путь и имя выходного pdf файла. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)