---
title: TryConcatenate
second_title: Aspose.PDF для справочника API .NET
description: Объединяет два файла.
type: docs
weight: 420
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_4}

Объединяет два файла.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | Первый файл для объединения. |
| secInputFile | String | Второй файл для объединения. |
| outputFile | String | Выходной файл. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryConcatenate аналогичен методу Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Объединяет документы.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | Document[] | Массив исходных документов. |
| dest | Document | Документ назначения. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryConcatenate подобен методу Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_6}

Объединяет файлы в один файл.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Массив файлов для объединения. |
| outputFile | String | Имя выходного файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryConcatenate подобен методу Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Объединяет файлы

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream[] | Массив потоков для объединения. |
| outputStream | Stream | Поток, в котором будет храниться файл результатов. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryConcatenate подобен методу Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_5}

Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: документ1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf даст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница .

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | Первый файл. |
| secInputFile | String | Второй файл. |
| blankPageFile | String | PDF-файл с пустой страницей. |
| outputFile | String | Файл результата. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryConcatenate аналогичен методу Concatenate , за исключением того, что метод TryConcatenate не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: документ1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf даст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница .

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | Первый Pdf-поток. |
| secInputStream | Stream | Второй поток PDF. |
| blankPageStream | Stream | Поток Pdf с пустой страницей. |
| outputStream | Stream | Выходной поток PDF. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryConcatenate аналогичен методу Concatenate , за исключением того, что метод TryConcatenate не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Объединяет файлы и сохраняет результат в объекте HttpResposnse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Массив файлов для объединения. |
| response | HttpResponse | Объект ответа. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryConcatenate аналогичен методу Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Объединяет файлы и сохраняет результат в объекте HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream[] | Массив потоков, содержащий файлы для объединения. |
| response | HttpResponse | Объект ответа/ |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryConcatenate аналогичен методу Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
