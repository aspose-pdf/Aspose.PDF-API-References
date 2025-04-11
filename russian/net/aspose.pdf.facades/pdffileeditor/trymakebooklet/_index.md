---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Создает буклет из входного файла в выходной файл
type: docs
weight: 430
url: /ru/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Создает буклет из исходного файла и сохраняет результат в объекты HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageSize | PageSize | Желаемый размер страницы. |
| leftPages | Int32[] | Массив номеров страниц, которые будут размещены слева. |
| rightPages | Int32[] | Массив номеров страниц, которые будут размещены справа. |
| response | HttpResponse | Объект HttpResponse, в который будет сохранен результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Создает буклет из PDF-файла и сохраняет его в HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток документа. |
| pageSize | PageSize | Желаемый размер страницы. |
| leftPages | Int32[] | Массив номеров страниц, которые будут размещены слева. |
| rightPages | Int32[] | Массив номеров страниц, которые будут размещены справа. |
| response | HttpResponse | Объект HttpResponse. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Создает буклет из исходного файла и сохраняет результат в объекты HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageSize | PageSize | Желаемый размер страницы в выходном файле. |
| response | HttpResponse | Объект HttpResponse, в который будет сохранен результат. |

### Возвращаемое значение

True, если операция завершена успешно.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Создает буклет из исходного файла и сохраняет результат в HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток документа. |
| pageSize | PageSize | Желаемый размер страницы в выходном файле. |
| response | HttpResponse | Объект, в который будет сохранен результат. |

### Возвращаемое значение

true, если буклет был успешно создан.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Создает буклет из входного файла в выходной файл.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного PDF-файла. |
| outputFile | String | Путь и имя выходного PDF-файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Создает буклет из InputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной PDF-поток. |
| outputStream | Stream | Выходной PDF-поток. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Создает буклет из inputFile в outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного PDF-файла. |
| outputFile | String | Путь и имя выходного PDF-файла. |
| pageSize | PageSize | Размер страницы выходного PDF-файла. |

### Возвращаемое значение

True, если операция завершена успешно.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Создает буклет из входного потока и сохраняет результат в выходной поток.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной PDF-поток. |
| outputStream | Stream | Выходной PDF-поток. |
| pageSize | PageSize | Размер страницы выходного PDF-файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Создает индивидуальный буклет из firstInputFile в outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Путь и имя выходного PDF-файла. |
| leftPages | Int32[] | Левые страницы буклета. |
| rightPages | Int32[] | Правые страницы буклета. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Создает индивидуальный буклет из firstInputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | Выходной PDF-поток. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Создает индивидуальный буклет из firstInputFile в outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Путь и имя выходного PDF-файла. |
| pageSize | PageSize | Размер страницы выходного PDF-файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Создает буклет из firstInputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | Выходной PDF-поток. |
| pageSize | PageSize | Размер страницы выходного PDF-файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)