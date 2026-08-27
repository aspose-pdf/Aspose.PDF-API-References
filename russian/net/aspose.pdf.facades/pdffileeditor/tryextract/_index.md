---
title: "PdfFileEditor.TryExtract"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Извлекает страницы из входного файла и сохраняет их как новый Pdf файл."
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
| outputFile | String | Путь к выходному Pdf‑файлу. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Извлекает страницы, указанные массивом номеров, и сохраняет как новый PDF файл.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Путь к входному файлу. |
| pageNumber | Int32[] | Индекс страницы во входном файле. |
| outputFile | String | Путь к выходному файлу. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Извлекает страницы, указанные массивом номеров, и сохраняет как новый Pdf файл.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток файла. |
| pageNumber | Int32[] | Индекс страницы во входном файле. |
| outputStream | Stream | Поток выходного файла. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


