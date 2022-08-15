---
title: Extract
second_title: Aspose.PDF для справочника API .NET
description: Извлекает страницы из входного файла сохраняет как новый файл PDF.
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_3}

Извлекает страницы из входного файла, сохраняет как новый файл PDF.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь к файлу PDF. |
| startPage | Int32 | Номер стартовой страницы. |
| endPage | Int32 | Конечный номер страницы. |
| outputFile | String | Выходной путь к файлу Pdf. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_4}

Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Извлекает страницы из входного файла, сохраняет как новый файл PDF.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной файл Поток. |
| startPage | Int32 | Номер стартовой страницы. |
| endPage | Int32 | Конечный номер страницы. |
| outputStream | Stream | Выходной файл Pdf Stream. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной файл Поток. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputStream | Stream | Выходной файловый поток. |

### Возвращаемое значение

Верно для успеха или ложно.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Extract(Stream, int[], HttpResponse) {#extract_2}

Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| pageNumber | Int32[] | Массив номеров страниц, которые будут извлечены. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

Истинно, если операция прошла успешно.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## Extract(string, int[], HttpResponse) {#extract_5}

Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse.

```csharp
public bool Extract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageNumber | Int32[] | Массив номеров страниц, которые будут извлечены. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

true, если страницы были успешно извлечены.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
