---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Разделяет с указанного места и сохраняет заднюю часть как новый файл
type: docs
weight: 470
url: /ru/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Разделяет с указанного места и сохраняет заднюю часть как новый файл.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Исходный Pdf файл. |
| location | Int32 | Позиция разделения. |
| outputFile | String | Путь к выходному Pdf файлу. |

### Возвращаемое значение

True при успехе, или false.

## Примечания

Метод TrySplitToEnd похож на метод SplitToEnd, за исключением того, что метод TrySplitToEnd не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Разделяет с указанного места и сохраняет заднюю часть как новый файл Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Исходный Pdf файл Stream. |
| location | Int32 | Позиция разделения. |
| outputStream | Stream | Выходной Pdf файл Stream. |

### Возвращаемое значение

True при успехе, или false.

## Примечания

Потоки НЕ закрываются после этой операции, если не указано CloseConcatedStreams. Метод TrySplitToEnd похож на метод SplitToEnd, за исключением того, что метод TrySplitToEnd не вызывает исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Разделяет с указанного места и сохраняет заднюю часть в объект HttpResponse.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Исходный поток документа. |
| location | Int32 | Точка разделения. |
| response | HttpResponse | Объект HttpResponse. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TrySplitToEnd похож на метод SplitToEnd, за исключением того, что метод TrySplitToEnd не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Разделяет с указанного места и сохраняет заднюю часть в объект HttpResponse.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | имя исходного файла. |
| location | Int32 | Точка разделения. |
| response | HttpResponse | Объекты HttpResponse. |

### Возвращаемое значение

true, если операция завершена успешно; в противном случае false.

## Примечания

Метод TrySplitToEnd похож на метод SplitToEnd, за исключением того, что метод TrySplitToEnd не вызывает исключение, если операция не удалась.

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)