---
title: TryInsert
second_title: Aspose.PDF для справочника API .NET
description: Вставляет страницы из другого файла во входной файл Pdf.
type: docs
weight: 450
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_2}

Вставляет страницы из другого файла во входной файл Pdf.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл PDF. |
| insertLocation | Int32 | Вставить позицию во входной файл. |
| portFile | String | Страницы из файла PDF. |
| pageNumber | Int32[] | Номер страницы портированного файла portFile. |
| outputFile | String | Выходной PDF-файл. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примечания

Метод TryInsert аналогичен методу Insert, за исключением того, что метод TryInsert не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Вставляет страницы из другого файла во входной файл Pdf.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток файла PDF. |
| insertLocation | Int32 | Вставить позицию во входной файл. |
| portStream | Stream | Поток файла Pdf для страниц. |
| pageNumber | Int32[] | Номер страницы портированного файла portFile. |
| outputStream | Stream | Выходной поток. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryInsert аналогичен методу Insert, за исключением того, что метод TryInsert не генерирует исключение в случае сбоя операции.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Вставляет содержимое файла в исходный файл и сохраняет результат в объекте HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя исходного файла. |
| insertLocation | Int32 | Номер страницы, на которую будет вставлен второй файл. |
| portFile | String | Путь к файлу, который будет вставлен. |
| pageNumber | Int32[] | Массив номеров страниц в исходном файле, который будет вставлен. |
| response | HttpResponse | Объект ответа, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryInsert аналогичен методу Insert, за исключением того, что метод TryInsert не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Вставляет документ в другой документ и сохраняет результат в объекте ответа.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток с исходным документом |
| insertLocation | Int32 | Место, куда будет вставлен другой документ. |
| portStream | Stream | Документ для вставки. |
| pageNumber | Int32[] | Массив номеров страниц во втором документе, который будет вставлен. |
| response | HttpResponse | Объект ответа, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryInsert аналогичен методу Insert, за исключением того, что метод TryInsert не генерирует исключение в случае сбоя операции.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
