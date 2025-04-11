---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileEditor. Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл
type: docs
weight: 270
url: /ru/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Удаляет страницы, указанные массивом номеров, из входного файла, сохраняет как новый Pdf файл.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

True, если операция была успешной.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Удаляет страницы, указанные массивом номеров, из входного файла, сохраняет как новый Pdf файл.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток входного файла. |
| pageNumber | Int32[] | Индекс страницы из входного файла. |
| outputStream | Stream | Поток выходного файла. |

### Возвращаемое значение

True для успеха, или false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)