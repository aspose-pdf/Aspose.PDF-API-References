---
title: "PdfFileEditor.Append"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage."
type: docs
weight: 250
url: /ru/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Добавляет страницы, выбранные из массива документов в portStreams. Итоговый документ включает firstInputFile и страницы всех документов portStreams в диапазоне от startPage до endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Добавляет страницы, выбранные из документов portFiles. Итоговый документ включает firstInputFile и страницы всех документов portFiles в диапазоне от startPage до endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
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

True, если операция завершилась успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конец firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной Pdf файл. |
| portFile | String | Страницы из файла Pdf. |
| startPage | Int32 | Страница начинается в portFile. |
| endPage | Int32 | Страница заканчивается в portFile. |
| outputFile | String | Выходной документ Pdf. |

### Возвращаемое значение

True, если операция завершилась успешно.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конец firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток файла. |
| portStream | Stream | Страницы из потока Pdf‑файла. |
| startPage | Int32 | Страница начинается в потоке portFile. |
| endPage | Int32 | Страница заканчивается в потоке portFile. |
| outputStream | Stream | Выходной поток Pdf‑файла. |

### Возвращаемое значение

True при успехе, иначе false.

## Примеры

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


