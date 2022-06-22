---
title: TryMakeBooklet
second_title: Aspose.PDF для справочника API .NET
description: Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse.
type: docs
weight: 460
url: /ru/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, PageSize, int[], int[], HttpResponse) {#trymakebooklet_6}

Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageSize | PageSize | Желаемый размер страницы. |
| leftPages | Int32[] | Массив номеров страниц для размещения слева. |
| rightPages | Int32[] | Массив номеров страниц для размещения справа. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Сделать буклет из файла PDF и сохранить его в HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входных документов. |
| pageSize | PageSize | Желаемый размер страницы. |
| leftPages | Int32[] | Массив номеров страниц, которые будут помещены слева. |
| rightPages | Int32[] | Массив номеров страниц, которые будут заменены справа. |
| response | HttpResponse | Объект HttpResponse. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageSize | PageSize | Желаемый размер страницы в выходном файле. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

Истинно, если операция выполнена успешно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Создает буклет из исходного файла и сохраняет результат в HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входных документов. |
| pageSize | PageSize | Желаемый размер страницы в выходном файле. |
| response | HttpResponse | Respose объект, в котором будут сохранены результаты. |

### Возвращаемое значение

true, если буклет построен успешно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Делает буклет из входного файла в выходной файл.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь и имя файла PDF. |
| outputFile | String | Выходной путь и имя файла PDF. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet_2}

Создает буклет из InputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток pdf. |
| outputStream | Stream | выходной поток PDF. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_9}

Делает буклет из входного файла в выходной файл.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь и имя файла PDF. |
| outputFile | String | Выходной путь и имя файла PDF. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |

### Возвращаемое значение

Истинно, если операция выполнена успешно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_3}

Делает буклет из входного потока и сохраняет результат в выходной поток.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток PDF. |
| outputStream | Stream | выходной поток PDF. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_11}

Создает настраиваемый буклет из файла firstInputFile в файл output.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Путь и имя выходного pdf-файла. |
| leftPages | Int32[] | Левые страницы буклета. |
| rightPages | Int32[] | Правые страницы буклета. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_5}

Создает настраиваемый буклет из firstInputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | выходной поток PDF. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правильные страницы. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_10}

Создает настраиваемый буклет из файла firstInputFile в файл output.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Путь и имя выходного pdf-файла. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правильные страницы. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_4}

Создает буклет из firstInputStream в outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | выходной поток PDF. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правильные страницы. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryMakeBooklet подобен методу MakeBooklet, за исключением того, что метод TryMakeBooklet не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
