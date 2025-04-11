---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Создает буклет из входного файла в выходной файл
type: docs
weight: 300
url: /ru/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Создает буклет из входного файла в выходной файл.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf файла. |
| outputFile | String | Путь и имя выходного pdf файла. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Создает буклет из InputStream в outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной pdf поток. |
| outputStream | Stream | выходной pdf поток. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Создает буклет из inputFile в outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь и имя входного pdf файла. |
| outputFile | String | Путь и имя выходного pdf файла. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Создает буклет из входного потока и сохраняет результат в выходной поток.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной PDF поток. |
| outputStream | Stream | выходной pdf поток. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Создает настраиваемый буклет из firstInputFile в outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Путь и имя выходного pdf файла. |
| leftPages | Int32[] | Левые страницы буклета. |
| rightPages | Int32[] | Правые страницы буклета. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Создает настраиваемый буклет из firstInputStream в outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | выходной pdf поток. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Создает настраиваемый буклет из firstInputFile в outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной файл. |
| outputFile | String | Путь и имя выходного pdf файла. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Создает буклет из firstInputStream в outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| outputStream | Stream | выходной pdf поток. |
| pageSize | PageSize | Размер страницы выходного pdf файла. |
| leftPages | Int32[] | Левые страницы. |
| rightPages | Int32[] | Правые страницы. |

### Возвращаемое значение

boolean - True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Создает буклет из исходного файла и сохраняет результат в объекты HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageSize | PageSize | Желаемый размер страницы. |
| leftPages | Int32[] | Массив номеров страниц, которые будут размещены слева. |
| rightPages | Int32[] | Массив номеров страниц, которые будут размещены справа. |
| response | HttpResponse | Объект HttpResponse, в котором будет сохранен результат. |

### Возвращаемое значение

True, если операция была успешной.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Создает буклет из PDF файла и сохраняет его в HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток документа. |
| pageSize | PageSize | Желаемый размер страницы. |
| leftPages | Int32[] | Массив номеров страниц, которые будут размещены слева. |
| rightPages | Int32[] | Массив номеров страниц, которые будут размещены справа. |
| response | HttpResponse | Объект HttpResponse. |

### Возвращаемое значение

True, если операция была успешной.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Создает буклет из исходного файла и сохраняет результат в объекты HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageSize | PageSize | Желаемый размер страницы в выходном файле. |
| response | HttpResponse | Объект HttpResponse, в котором будет сохранен результат. |

### Возвращаемое значение

True, если операция была успешной.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Создает буклет из исходного файла и сохраняет результат в HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток документа. |
| pageSize | PageSize | Желаемый размер страницы в выходном файле. |
| response | HttpResponse | Объект Respose, в котором будет сохранен результат. |

### Возвращаемое значение

true, если буклет был успешно создан.

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)