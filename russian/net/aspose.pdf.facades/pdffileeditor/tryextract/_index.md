---
title: TryExtract
second_title: Aspose.PDF для справочника API .NET
description: Извлекает страницы из входного файла сохраняет как новый файл Pdf.
type: docs
weight: 440
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_2}

Извлекает страницы из входного файла, сохраняет как новый файл Pdf.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь к файлу Pdf. |
| startPage | Int32 | Номер начальной страницы. |
| endPage | Int32 | Номер конечной страницы. |
| outputFile | String | Путь к выходному файлу Pdf. |

### Возвращаемое значение

Истина для успеха или ложь.

### Примечания

Метод TryExtract аналогичен методу Extract, за исключением того, что метод TryExtract не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_3}

Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Введите путь к файлу. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryExtract аналогичен методу Extract, за исключением того, что метод TryExtract не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного файла. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputStream | Stream | Выходной файловый поток. |

### Возвращаемое значение

Истина для успеха или ложь.

### Примечания

Метод TryExtract аналогичен методу Extract, за исключением того, что метод TryExtract не генерирует исключение, если операция не удалась.

### Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| pageNumber | Int32[] | Массив номеров страниц, которые будут извлечены. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryExtract аналогичен методу Extract, за исключением того, что метод TryExtract не генерирует исключение, если операция не удалась.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageNumber | Int32[] | Массив номеров страниц, которые будут извлечены. |
| response | HttpResponse | Объект HttpResponse, в котором будет храниться результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае ложно.

### Примечания

Метод TryExtract аналогичен методу Extract, за исключением того, что метод TryExtract не генерирует исключение, если операция не удалась.

### Смотрите также

* class [PdfFileEditor](../../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdffileeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
