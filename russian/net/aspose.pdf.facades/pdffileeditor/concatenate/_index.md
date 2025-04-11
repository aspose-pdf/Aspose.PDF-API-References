---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Объединяет два файла
type: docs
weight: 260
url: /ru/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

Объединяет два файла.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | Первый файл для объединения. |
| secInputFile | String | Второй файл для объединения. |
| outputFile | String | Выходной файл. |

### Возвращаемое значение

True, если операция прошла успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Объединяет два файла.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | Поток первого файла. |
| secInputStream | Stream | Поток второго файла. |
| outputStream | Stream | Поток, в который будет сохранен результирующий файл. |

### Возвращаемое значение

True, если операция прошла успешно.

True, если операция прошла успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Объединяет документы.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | Document[] | Массив исходных документов. |
| dest | Document | Целевой документ. |

### Возвращаемое значение

True, если объединение прошло успешно.

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

Объединяет файлы в один файл.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Массив файлов для объединения. |
| outputFile | String | Имя выходного файла. |

### Возвращаемое значение

True, если операция прошла успешно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Объединяет файлы

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream[] | Массив потоков для объединения. |
| outputStream | Stream | Поток, в который будет сохранен результирующий файл. |

### Возвращаемое значение

True, если операция прошла успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

Объединяет два документа Pdf в новый документ Pdf с чередующимися страницами и заполняет пустые места пустыми страницами. Например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf приведет к созданию результирующего документа со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | Первый файл. |
| secInputFile | String | Второй файл. |
| blankPageFile | String | PDF файл с пустой страницей. |
| outputFile | String | Результирующий файл. |

### Возвращаемое значение

True, если операция прошла успешно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Объединяет два документа Pdf в новый документ Pdf с чередующимися страницами и заполняет пустые места пустыми страницами. Например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf приведет к созданию результирующего документа со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | Первый Pdf поток. |
| secInputStream | Stream | Второй Pdf поток. |
| blankPageStream | Stream | Pdf поток с пустой страницей. |
| outputStream | Stream | Выходной Pdf поток. |

### Возвращаемое значение

True, если операция прошла успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)


## Concatenate(string[], HttpResponse) {#concatenate_8}

Объединяет файлы и сохраняет результат в объекте HttpResponse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Массив файлов для объединения. |
| response | HttpResponse | Объект ответа. |

### Возвращаемое значение

true, если объединение прошло успешно.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Объединяет файлы и сохраняет результат в объекте HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream[] | Массив потоков, содержащих файлы для объединения. |
| response | HttpResponse | Объект ответа. |

### Возвращаемое значение

true, если операция прошла успешно.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)