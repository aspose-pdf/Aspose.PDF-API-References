---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Добавляет страницы, которые выбраны из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage
type: docs
weight: 380
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Добавляет страницы, которые выбраны из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

True при успешном выполнении, или false.

## Примечания

Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Добавляет страницы, которые выбраны из документов portFiles. Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

true, если операция завершилась успешно; в противном случае false.

## Примечания

Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Добавляет документы в исходный документ и сохраняет результат в объекте ответа.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток, содержащий исходный документ. |
| portStreams | Stream[] | Массив потоков с документами, которые будут добавлены. |
| startPage | Int32 | Начальная страница добавляемой страницы. |
| endPage | Int32 | Конечная страница добавленных страниц. |
| response | HttpResponse | Объект ответа, в котором будет сохранен документ. |

### Возвращаемое значение

true, если операция завершилась успешно; в противном случае false.

## Примечания

Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Добавляет документы в исходный документ и сохраняет результат в объекте HttpResponse.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя файла, содержащего исходный документ. |
| portFiles | String[] | Массив имен файлов, содержащих добавленные документы. |
| startPage | Int32 | Начальная страница добавленных страниц. |
| endPage | Int32 | Конечная страница добавленных страниц. |
| response | HttpResponse | Объект ответа, в котором будет сохранен документ. |

### Возвращаемое значение

true, если операция завершилась успешно; в противном случае false.

## Примечания

Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)