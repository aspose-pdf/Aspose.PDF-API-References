---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Извлекает страницы из входных файлов и сохраняет как новый Pdf файл
type: docs
weight: 410
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Извлекает страницы из входного файла, сохраняет как новый Pdf файл.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному Pdf файлу. |
| startPage | Int32 | Номер начальной страницы. |
| endPage | Int32 | Номер конечной страницы. |
| outputFile | String | Путь к выходному Pdf файлу. |

### Возвращаемое значение

True при успешном выполнении, или false.

## Примечания

Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Извлекает страницы, указанные массивом номеров, сохраняет как новый PDF файл.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Извлекает страницы, указанные массивом номеров, сохраняет как новый Pdf файл.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного файла. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputStream | Stream | Поток выходного файла. |

### Возвращаемое значение

True при успешном выполнении, или false.

## Примечания

Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| pageNumber | Int32[] | Массив номеров страниц, которые будут извлечены. |
| response | HttpResponse | Объект HttpResponse, в который будет сохранен результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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
| response | HttpResponse | Объект HttpResponse, в который будет сохранен результат. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)