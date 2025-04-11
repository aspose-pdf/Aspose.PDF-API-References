---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Создает NUp документ из firstInputFile в outputFile
type: docs
weight: 440
url: /ru/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Создает N-up документ и сохраняет результат в объект HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы в результирующем файле. |
| response | HttpResponse | Объект HttpResponse, в который будет сохранен результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Создает N-up документ и сохраняет результат в объект HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы в результирующем файле. |
| response | HttpResponse | Объект HttpResponse, в который будет сохранен результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Создает N-up документ и сохраняет результат в HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя исходного файла. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| response | HttpResponse | Объект HttpResponse, в который будет сохранен результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Создает N-up документ и сохраняет результат в HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного документа. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| response | HttpResponse | HttpResponse, в который будет сохранен результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Создает N-Up документ из firstInputFile в outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf файла. |
| outputFile | String | Путь и имя выходного pdf файла. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Создает N-Up документ из входного потока и сохраняет результат в выходной поток.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной pdf поток. |
| outputStream | Stream | Выходной pdf поток. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Создает N-Up документ из первого входного потока в выходной поток.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной pdf поток. |
| outputStream | Stream | Выходной pdf поток. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Создает N-Up документ из двух входных PDF файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла и другая из второго входного файла. Две страницы располагаются горизонтально.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | первый входной файл. |
| secondInputFile | String | второй входной файл. |
| outputFile | String | Путь и имя выходного pdf файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Создает N-Up документ из двух входных PDF потоков в outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | первый входной поток. |
| secondInputStream | Stream | второй входной поток. |
| outputStream | Stream | Выходной pdf поток. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Создает N-Up документ из нескольких входных PDF файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией страниц из входных файлов с одинаковым номером страницы. Многостраничные документы располагаются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Входные Pdf файлы. |
| outputFile | String | Путь и имя выходного pdf файла. |
| isSidewise | Boolean | Способ укладки, true для горизонтальной и false для вертикальной. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Создает N-Up документ из нескольких входных PDF потоков в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц из входных потоков с одинаковым номером страницы. Многостраничные документы располагаются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStreams | Stream[] | Входные Pdf потоки. |
| outputStream | Stream | Выходной pdf поток. |
| isSidewise | Boolean | Способ укладки, true для горизонтальной и false для вертикальной. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Создает N-Up документ из входного файла в outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf файла. |
| outputFile | String | Путь и имя выходного pdf файла. |
| x | Int32 | Количество колонок. |
| y | Int32 | Количество строк. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не вызывает исключение, если операция завершается неудачно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)