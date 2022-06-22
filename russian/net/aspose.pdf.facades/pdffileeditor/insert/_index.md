---
title: Insert
second_title: Aspose.PDF для справочника API .NET
description: Вставляет страницы из другого файла в файл Pdf в позицию.
type: docs
weight: 320
url: /ru/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_3}

Вставляет страницы из другого файла в файл Pdf в позицию.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл Pdf. |
| insertLocation | Int32 | Позиция во входном файле. |
| portFile | String | Pdf-файл переноса. |
| startPage | Int32 | Начальная позиция в portFile. |
| endPage | Int32 | Конечная позиция в portFile. |
| outputFile | String | Выходной файл Pdf. |

### Возвращаемое значение

Истина для успеха или ложь.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Вставляет страницы из другого файла во входной файл Pdf.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток файла Pdf. |
| insertLocation | Int32 | Вставить позицию во входной файл. |
| portStream | Stream | Поток файла Pdf для страниц. |
| startPage | Int32 | С какой страницы начинать. |
| endPage | Int32 | На какой странице закончить. |
| outputStream | Stream | Выходной поток. |

### Возвращаемое значение

Истина для успеха или ложь.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_4}

Вставляет страницы из другого файла во входной файл Pdf.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл Pdf. |
| insertLocation | Int32 | Вставить позицию во входной файл. |
| portFile | String | Страницы из файла Pdf. |
| pageNumber | Int32[] | Номер страницы портируемого в portFile. |
| outputFile | String | Выходной файл Pdf. |

### Возвращаемое значение

Истина для успеха или ложь.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Вставляет страницы из другого файла во входной файл Pdf.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток файла Pdf. |
| insertLocation | Int32 | Вставить позицию во входной файл. |
| portStream | Stream | Поток файла Pdf для страниц. |
| pageNumber | Int32[] | Номер страницы портируемого в portFile. |
| outputStream | Stream | Выходной поток. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], HttpResponse) {#insert_5}

Вставляет содержимое файла в исходный файл и сохраняет результат в объект HttpResponse.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя исходного файла. |
| insertLocation | Int32 | Номер страницы, куда будет вставлен второй файл. |
| portFile | String | Путь к файлу, который будет вставлен. |
| pageNumber | Int32[] | Массив номеров страниц исходного файла, который будет вставлен. |
| response | HttpResponse | Объект ответа, в котором будет сохранен результат. |

### Возвращаемое значение

правда вставки прошла успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], HttpResponse) {#insert_2}

Вставляет документ в другой документ и сохраняет результат в объект ответа.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток с исходным документом |
| insertLocation | Int32 | Место, где другие документ будет вставлен. |
| portStream | Stream | Документ для вставки. |
| pageNumber | Int32[] | Массив номеров страниц во втором документе, который будет вставлен. |
| response | HttpResponse | Объект ответа, в котором будет сохранен результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
