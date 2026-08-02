---
title: "PdfFileEditor.TryAppend"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage."
type: docs
weight: 380
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Добавляет страницы, выбранные из массива документов в portStreams. Итоговый документ включает firstInputFile и страницы всех документов portStreams в диапазоне от startPage до endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток Pdf. |
| portStreams | Stream[] | Документы, из которых копировать страницы. |
| startPage | Int32 | Страница начинается в документах portStreams. |
| endPage | Int32 | Страница заканчивается в документах portStreams. |
| outputStream | Stream | Выходной поток Pdf. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Добавляет страницы, выбранные из документов portFiles. Итоговый документ включает firstInputFile и страницы всех документов portFiles в диапазоне от startPage до endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной Pdf файл. |
| portFiles | String[] | Документы, из которых копировать страницы. |
| startPage | Int32 | Страница начинается в документах portFiles. |
| endPage | Int32 | Страница заканчивается в документах portFiles. |
| outputFile | String | Выходной документ Pdf. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не генерирует исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


