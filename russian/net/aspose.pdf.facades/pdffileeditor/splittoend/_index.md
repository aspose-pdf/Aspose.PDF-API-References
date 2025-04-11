---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Разделяет с указанного места и сохраняет заднюю часть как новый файл
type: docs
weight: 360
url: /ru/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Разделяет с указанного места и сохраняет заднюю часть как новый файл Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Исходный Pdf файл Stream. |
| location | Int32 | Позиция разделения. |
| outputStream | Stream | Выходной Pdf файл Stream. |

### Возвращаемое значение

True для успеха, или false.

## Примечания

Потоки НЕ закрываются после этой операции, если не указано CloseConcatedStreams.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Разделяет с указанного места и сохраняет заднюю часть как новый файл.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Исходный Pdf файл. |
| location | Int32 | Позиция разделения. |
| outputFile | String | Путь к выходному Pdf файлу. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Разделяет с указанного места и сохраняет заднюю часть как новый файл Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Исходный Pdf файл Stream. |
| location | Int32 | Позиция разделения. |
| outputStream | Stream | Выходной Pdf файл Stream. |

### Возвращаемое значение

True для успеха, или false.

## Примечания

Потоки НЕ закрываются после этой операции, если не указано CloseConcatedStreams.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)