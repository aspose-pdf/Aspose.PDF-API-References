---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Разделяет Pdf файл с первой страницы на указанное место и сохраняет переднюю часть как новый файл
type: docs
weight: 340
url: /ru/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Разделяет Pdf файл с первой страницы на указанное место и сохраняет переднюю часть как новый файл.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Исходный Pdf файл. |
| location | Int32 | Точка разделения. |
| outputFile | String | Выходной Pdf файл. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Разделяет с начала на указанное место и сохраняет переднюю часть в выходном потоке.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Исходный поток Pdf файла. |
| location | Int32 | Точка разделения. |
| outputStream | Stream | Выходной поток файла. |

### Возвращаемое значение

True для успеха, или false.

## Примечания

Потоки НЕ закрываются после этой операции.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)