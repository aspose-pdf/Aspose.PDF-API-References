---
title: Append
second_title: Aspose.PDF для справочника API .NET
description: Добавляет страницы выбранные из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage.
type: docs
weight: 280
url: /ru/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток PDF. |
| portStreams | Stream[] | Документы, из которых нужно скопировать страницы. |
| startPage | Int32 | Страница начинается в документах portStreams. |
| endPage | Int32 | Страница заканчивается в документах portStreams. |
| outputStream | Stream | Выходной поток PDF. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

Добавляет страницы, выбранные из документов portFiles. Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл PDF. |
| portFiles | String[] | Документы, из которых нужно скопировать страницы. |
| startPage | Int32 | Страница начинается в документах portFiles. |
| endPage | Int32 | Страница заканчивается в документах portFiles. |
| outputFile | String | Выходной PDF-документ. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конце firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл PDF. |
| portFile | String | Страницы из файла PDF. |
| startPage | Int32 | Страница начинается в portFile. |
| endPage | Int32 | Страница заканчивается в portFile. |
| outputFile | String | Выходной PDF-документ. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конце firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной файл Поток. |
| portStream | Stream | Страницы из файла Pdf Stream. |
| startPage | Int32 | Страница начинается в порту File Stream. |
| endPage | Int32 | Страница заканчивается в portFile Stream. |
| outputStream | Stream | Выходной файл Pdf Stream. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

Добавляет документы в исходный документ и сохраняет результат в объекте ответа.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток, содержащий исходный документ. |
| portStreams | Stream[] | Массив потоков с добавляемыми документами. |
| startPage | Int32 | Стартовая страница добавленной страницы. |
| endPage | Int32 | Конечная страница добавленных страниц. |
| response | HttpResponse | Объект ответа, в котором будет сохранен документ. |

### Возвращаемое значение

true, если операция прошла успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

Добавляет документы в исходный документ и сохраняет результат в объекте HttpResponse.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя файла, содержащего исходный документ. |
| portFiles | String[] | Массив имен файлов, содержащих присоединенные документы. |
| startPage | Int32 | Стартовая страница добавленных страниц. |
| endPage | Int32 | Конечная страница добавленных страниц. |
| response | HttpResponse | Объект ответа, в котором будет сохранен документ. |

### Возвращаемое значение

true, если операция прошла успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
