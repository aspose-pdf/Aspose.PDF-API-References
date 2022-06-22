---
title: MakeNUp
second_title: Aspose.PDF для справочника API .NET
description: Создает документ N-Up из firstInputFile в outputFile.
type: docs
weight: 340
url: /ru/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(string, string, int, int) {#makenup_8}

Создает документ N-Up из firstInputFile в outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь и имя файла PDF. |
| outputFile | String | Выходной путь и имя файла PDF. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

boolean - Истинно в случае успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Создает N-Up документ из входного потока и сохраняет результат в выходной поток.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток pdf. |
| outputStream | Stream | Вывод pdf-потока. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

boolean - Истинно в случае успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Создает документ N-Up из первого входного потока в выходной поток.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток pdf. |
| outputStream | Stream | Вывод pdf-потока. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Создает документ N-Up из двух входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла , а другая из второго входного файла. Две страницы сложены горизонтально.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | первый входной файл. |
| secondInputFile | String | второй входной файл. |
| outputFile | String | Выходной путь и имя файла PDF. |

### Возвращаемое значение

boolean - Истинно в случае успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Создает документ N-Up из двух входных потоков PDF в outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | первый входной поток. |
| secondInputStream | Stream | второй входной поток. |
| outputStream | Stream | Вывод pdf-потока. |

### Возвращаемое значение

boolean - Истинно в случае успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_11}

Создает документ N-Up из нескольких входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией со страницами во входных файлах с тем же номером страницы. Несколько страниц складываются горизонтально , если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Входные файлы Pdf. |
| outputFile | String | Путь и имя выходного pdf-файла. |
| isSidewise | Boolean | Нагроможденный путь, истинный для горизонтали и flase для вертикали. |

### Возвращаемое значение

boolean - Истинно в случае успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_5}

Создает документ N-Up из нескольких входных потоков PDF в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые объединяются со страницами во входных потоках с тем же номером страницы. Многостраничные страницы складываются горизонтально , если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Параметр | Описание |
| --- | --- |
| inputStreams | Входные потоки Pdf. |
| outputStream | Вывод pdf-потока.  Сложенный путь, true для горизонтального и flase для вертикального |

### Возвращаемое значение

boolean — True в случае успеха или false.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_9}

Создает N-Up документ из входного файла в outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь и имя файла PDF. |
| outputFile | String | Выходной путь и имя файла PDF. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |

### Возвращаемое значение

boolean - Истинно в случае успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, PageSize, HttpResponse) {#makenup}

Создает документ N-up и сохраняет результат в объекте HttpResponse.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы в файле результатов. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, PageSize, HttpResponse) {#makenup_6}

Создает документ N-up и сохраняет результат в объекте HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы в файле результатов. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, HttpResponse) {#makenup_7}

Создает документ N-up и сохраняет результат в HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя исходного файла. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, HttpResponse) {#makenup_1}

Создает документ N-up и сохраняет результат в HttpResponse.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного документа. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |
| response | HttpResponse | HttpResponse, где будет сохранен результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
