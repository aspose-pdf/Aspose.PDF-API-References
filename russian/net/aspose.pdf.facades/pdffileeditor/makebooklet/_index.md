---
title: MakeBooklet
second_title: Aspose.PDF для справочника API .NET
description: Делает буклет из входного файла в выходной файл.
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_8}

Делает буклет из входного файла в выходной файл.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь и имя файла PDF. |
| outputFile | String | Выходной путь и имя файла PDF. |

### Возвращаемое значение

boolean - True для успеха или false.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet_2}

Делает буклет из InputStream в outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток PDF. |
| outputStream | Stream | выходной поток PDF. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_9}

Делает буклет из inputFile в outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь и имя файла PDF. |
| outputFile | String | Выходной путь и имя файла PDF. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |

### Возвращаемое значение

Истинно, если операция выполнена успешно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_3}

Делает буклет из входного потока и сохраняет результат в выходной поток.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток PDF. |
| outputStream | Stream | выходной поток PDF. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_11}

Создает настраиваемый буклет из firstInputFile в outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Выходной путь и имя файла PDF. |
| leftPages | Int32[] | Левые страницы буклета. |
| rightPages | Int32[] | Правые страницы буклета. |

### Возвращаемое значение

boolean - True для успеха или false.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_5}

Создает настраиваемый буклет из firstInputStream в outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | выходной pdf-поток. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правильные страницы. |

### Возвращаемое значение

boolean - True для успеха или false.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_10}

Создает настраиваемый буклет из firstInputFile в outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Выходной путь и имя файла PDF. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правильные страницы. |

### Возвращаемое значение

boolean - True для успеха или false.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_4}

Создает буклет из firstInputStream в outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | выходной pdf-поток. |
| pageSize | PageSize | Размер страницы выходного pdf-файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правильные страницы. |

### Возвращаемое значение

boolean - True для успеха или false.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageSize | PageSize | Желаемый размер страницы. |
| leftPages | Int32[] | Массив номеров страниц для размещения слева. |
| rightPages | Int32[] | Массив номеров страниц, которые должны быть размещены справа. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Сделать буклет из файла PDF и сохранить его в HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток документов. |
| pageSize | PageSize | Желаемый размер страницы. |
| leftPages | Int32[] | Массив номеров страниц, которые будут помещены слева. |
| rightPages | Int32[] | Массив номеров страниц, которые будут заменены справа. |
| response | HttpResponse | Объект HttpResponse. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageSize | PageSize | Желаемый размер страницы в выходном файле. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

Истинно, если операция выполнена успешно.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Создает буклет из исходного файла и сохраняет результат в HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток документов. |
| pageSize | PageSize | Желаемый размер страницы в выходном файле. |
| response | HttpResponse | Объект Respose, в котором будут сохранены результаты. |

### Возвращаемое значение

true, если буклет был построен успешно.

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
