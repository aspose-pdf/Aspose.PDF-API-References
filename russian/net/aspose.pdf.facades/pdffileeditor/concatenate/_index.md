---
title: Concatenate
second_title: Aspose.PDF для справочника API .NET
description: Объединяет два файла.
type: docs
weight: 290
url: /ru/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_5}

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

Истинно, если операция выполнена успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
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
| outputStream | Stream | Поток, в котором будет храниться файл результатов. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

Истинно, если операция выполнена успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
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

Истинно, если объединение прошло успешно.

### Смотрите также

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_7}

Объединяет файлы в один файл.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Массив файлов для объединения. |
| outputFile | String | Имя выходного файла. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
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
| outputStream | Stream | Поток, в котором будет храниться файл результатов. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_6}

Объединяет два документа Pdf в новый документ Pdf со страницами попеременно и заполняет пустые места пустыми страницами. например:document1 имеет 5 страниц:p1, p2, p3, p4, p5. document2 имеет 3 страницы:p1', p2', p3'. Слияние двух документов Pdf создаст результирующий документ со страницами:p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | Первый файл. |
| secInputFile | String | Второй файл. |
| blankPageFile | String | PDF-файл с пустой страницей. |
| outputFile | String | Файл результатов. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Объединяет два документа Pdf в новый документ Pdf со страницами попеременно и заполняет пустые места пустыми страницами. например:document1 имеет 5 страниц:p1, p2, p3, p4, p5. document2 имеет 3 страницы:p1', p2', p3'. Слияние двух документов Pdf создаст результирующий документ со страницами:p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | Первый поток Pdf. |
| secInputStream | Stream | Второй поток Pdf. |
| blankPageStream | Stream | Поток Pdf с пустой страницей |
| outputStream | Stream | Выходной поток Pdf. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(string[], HttpResponse) {#concatenate_8}

Объединяет файлы и сохраняет результат в объекте HttpResposnse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Массив файлов для объединения. |
| response | HttpResponse | Объект ответа. |

### Возвращаемое значение

true, если объединение прошло успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Объединяет файлы и сохраняет результат в объект HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream[] | Массив потоков, содержащий файлы для конкатенации. |
| response | HttpResponse | Объект ответа/ |

### Возвращаемое значение

true, если операция выполнена успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
