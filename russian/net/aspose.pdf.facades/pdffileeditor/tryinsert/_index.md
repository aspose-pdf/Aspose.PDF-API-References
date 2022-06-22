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
| inputFile | String | Входной файл Pdf. |
| insertLocation | Int32 | Вставить позицию во входной файл. |
| portFile | String | Страницы из файла Pdf. |
| pageNumber | Int32[] | Номер страницы портируемого в portFile. |
| outputFile | String | Выходной файл Pdf. |

### Возвращаемое значение

Истина для успеха или ложь.

### Примечания

Метод TryInsert аналогичен методу Insert, за исключением того, что метод TryInsert не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, 2, 6, outStream);
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
| inputStream | Stream | Входной поток файла Pdf. |
| insertLocation | Int32 | Вставить позицию во входной файл. |
| portStream | Stream | Поток файла Pdf для страниц. |
| pageNumber | Int32[] | Номер страницы портируемого в portFile. |
| outputStream | Stream | Выходной поток. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryInsert аналогичен методу Insert, за исключением того, что метод TryInsert не генерирует исключение, если операция не удалась.

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

Вставляет содержимое файла в исходный файл и сохраняет результат в объект HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryInsert аналогичен методу Insert, за исключением того, что метод TryInsert не генерирует исключение, если операция не удалась.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Вставляет документ в другой документ и сохраняет результат в объект ответа.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryInsert аналогичен методу Insert, за исключением того, что метод TryInsert не генерирует исключение, если операция не удалась.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
