---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл
type: docs
weight: 400
url: /ru/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Удаляет страницы, указанные массивом номеров, из входного файла, сохраняет как новый Pdf файл.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryDelete похож на метод Delete, за исключением того, что метод TryDelete не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Удаляет страницы, указанные массивом номеров, из входного файла, сохраняет как новый Pdf файл.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного файла. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputStream | Stream | Поток выходного файла. |

### Возвращаемое значение

True для успеха, или false.

## Примечания

Метод TryDelete похож на метод Delete, за исключением того, что метод TryDelete не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Удаляет указанные страницы из документа и сохраняет результат в объект HttpResponse.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к исходному файлу. |
| pageNumber | Int32[] | Массив номеров страниц, которые должны быть удалены. |
| response | HttpResponse | Объект ответа, в который будет сохранен результирующий документ. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryDelete похож на метод Delete, за исключением того, что метод TryDelete не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Удаляет указанные страницы из документа и сохраняет результат в объект HttpResponse.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного документа. |
| pageNumber | Int32[] | Массив номеров страниц, которые будут удалены. |
| response | HttpResponse | Объект HttpResponse |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TryDelete похож на метод Delete, за исключением того, что метод TryDelete не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)