---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Вставляет страницы из другого файла в входной Pdf файл
type: docs
weight: 420
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Вставляет страницы из другого файла в входной Pdf файл.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной Pdf файл. |
| insertLocation | Int32 | Позиция вставки в входном файле. |
| portFile | String | Страницы из Pdf файла. |
| pageNumber | Int32[] | Номер страницы из portFile. |
| outputFile | String | Выходной Pdf файл. |

### Возвращаемое значение

True при успешном выполнении, или false.

## Примечания

Метод TryInsert похож на метод Insert, за исключением того, что метод TryInsert не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Вставляет страницы из другого файла в входной Pdf файл.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток Pdf файла. |
| insertLocation | Int32 | Позиция вставки в входном файле. |
| portStream | Stream | Поток Pdf файла для страниц. |
| pageNumber | Int32[] | Номер страницы из portFile. |
| outputStream | Stream | Выходной поток. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryInsert похож на метод Insert, за исключением того, что метод TryInsert не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Вставляет содержимое файла в исходный файл и сохраняет результат в объекте HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Имя исходного файла. |
| insertLocation | Int32 | Номер страницы, куда будет вставлен второй файл. |
| portFile | String | Путь к файлу, который будет вставлен. |
| pageNumber | Int32[] | Массив номеров страниц в исходном файле, которые будут вставлены. |
| response | HttpResponse | Объект ответа, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryInsert похож на метод Insert, за исключением того, что метод TryInsert не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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
| portStream | Stream | Документ, который будет вставлен. |
| pageNumber | Int32[] | Массив номеров страниц во втором документе, которые будут вставлены. |
| response | HttpResponse | Объект ответа, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryInsert похож на метод Insert, за исключением того, что метод TryInsert не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)