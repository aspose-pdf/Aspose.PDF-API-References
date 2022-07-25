---
title: TryMakeNUp
second_title: Aspose.PDF для справочника API .NET
description: Создает документ N-up и сохраняет результат в объекте HttpResponse.
type: docs
weight: 470
url: /ru/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, int, int, PageSize, HttpResponse) {#trymakenup_6}

Создает документ N-up и сохраняет результат в объекте HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| x | Int32 | Число столбцов. |
| y | Int32 | Количество рядов. |
| pageSize | PageSize | Размер страницы в файле результатов. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Создает документ N-up и сохраняет результат в объекте HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| x | Int32 | Число столбцов. |
| y | Int32 | Количество рядов. |
| pageSize | PageSize | Размер страницы в файле результатов. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Создает документ N-up и сохраняет результат в HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя исходного файла. |
| x | Int32 | Число столбцов. |
| y | Int32 | Количество рядов. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Создает документ N-up и сохраняет результат в HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного документа. |
| x | Int32 | Число столбцов. |
| y | Int32 | Количество рядов. |
| response | HttpResponse | HttpResponse, где будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Создает документ N-Up из firstInputFile в outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь и имя файла PDF. |
| outputFile | String | Выходной путь и имя файла PDF. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

true, если операция завершилась успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup_2}

Создает документ N-Up из входного потока и сохраняет результат в выходной поток.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток PDF. |
| outputStream | Stream | Выходной поток PDF. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_3}

Создает документ N-Up из первого входного потока в выходной поток.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток PDF. |
| outputStream | Stream | Выходной поток PDF. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_10}

Создает документ N-Up из двух входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла , а другая из второго входного файла. Две страницы сложены горизонтально.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | первый входной файл. |
| secondInputFile | String | второй входной файл. |
| outputFile | String | Выходной путь и имя файла PDF. |

### Возвращаемое значение

true, если операция завершилась успешно; в противном случае ложно

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_4}

Создает документ N-Up из двух входных потоков PDF в outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | первый входной поток. |
| secondInputStream | Stream | второй входной поток. |
| outputStream | Stream | Выходной поток PDF. |

### Возвращаемое значение

true, если операция завершилась успешно; в противном случае ложно

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_11}

Создает документ N-Up из нескольких входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией со страницами во входных файлах с тем же номером страницы. Несколько страниц складываются горизонтально , если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Входные PDF-файлы. |
| outputFile | String | Выходной путь и имя файла PDF. |
| isSidewise | Boolean | Нагроможденный путь, верный для горизонтали и ложный для вертикали. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_5}

Создает документ N-Up из нескольких входных потоков PDF в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые объединяются со страницами во входных потоках с тем же номером страницы. Многостраничные страницы складываются горизонтально , если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStreams | Stream[] | Входные потоки Pdf. |
| outputStream | Stream | Выходной pdf-поток. |
| isSidewise | Boolean | Нагроможденный путь, верный для горизонтали и ложный для вертикали. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_9}

Создает документ N-Up из входного файла в outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь и имя файла PDF. |
| outputFile | String | Выходной путь и имя файла PDF. |
| x | Int32 | Количество столбцов. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeNUp аналогичен методу MakeNUp, за исключением того, что метод TryMakeNUp не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
