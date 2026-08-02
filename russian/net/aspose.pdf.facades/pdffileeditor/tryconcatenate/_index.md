---
title: "PdfFileEditor.TryConcatenate"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Объединяет два файла."
type: docs
weight: 390
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

Объединяет два файла.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | Первый файл для объединения. |
| secInputFile | String | Второй файл для объединения. |
| outputFile | String | Файл вывода. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Конкатенирует документы.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | Document[] | Массив исходных документов. |
| dest | Document | Документ назначения. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение, если операция завершается неудачей.

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Объединяет файлы в один файл.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | String[] | Массив файлов для объединения. |
| outputFile | String | Имя выходного файла. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Конкатенирует файлы

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream[] | Массив потоков для конкатенации. |
| outputStream | Stream | Поток, в котором будет сохранён результирующий файл. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Объединяет два Pdf документа в новый Pdf документ, чередуя страницы и заполняя пустые места пустыми страницами. Например: document1 содержит 5 страниц: p1, p2, p3, p4, p5. document2 содержит 3 страницы: p1', p2', p3'. Слияние двух Pdf документов создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | String | Первый файл. |
| secInputFile | String | Второй файл. |
| blankPageFile | String | PDF файл с пустой страницей. |
| outputFile | String | Файл результата. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Объединяет два Pdf документа в новый Pdf документ, чередуя страницы и заполняя пустые места пустыми страницами. Например: document1 содержит 5 страниц: p1, p2, p3, p4, p5. document2 содержит 3 страницы: p1', p2', p3'. Слияние двух Pdf документов создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | Stream | Первый Pdf Stream. |
| secInputStream | Stream | Второй Pdf Stream. |
| blankPageStream | Stream | Pdf Stream с пустой страницей. |
| outputStream | Stream | Выходной Pdf Stream. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


