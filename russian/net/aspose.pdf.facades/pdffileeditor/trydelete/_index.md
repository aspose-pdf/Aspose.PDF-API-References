---
title: "PdfFileEditor.TryDelete"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый файл Pdf"
type: docs
weight: 400
url: /ru/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу. |
| pageNumber | Int32[] | Индекс страницы во входном файле. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryDelete похож на метод Delete, за исключением того, что метод TryDelete не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток файла. |
| pageNumber | Int32[] | Индекс страницы во входном файле. |
| outputStream | Stream | Поток выходного файла. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Метод TryDelete похож на метод Delete, за исключением того, что метод TryDelete не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


