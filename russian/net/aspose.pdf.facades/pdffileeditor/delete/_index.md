---
title: "PdfFileEditor.Delete"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый файл Pdf"
type: docs
weight: 270
url: /ru/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу. |
| pageNumber | Int32[] | Индекс страницы во входном файле. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

True, если операция завершилась успешно.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток файла. |
| pageNumber | Int32[] | Индекс страницы во входном файле. |
| outputStream | Stream | Поток выходного файла. |

### Возвращаемое значение

True при успехе, иначе false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


