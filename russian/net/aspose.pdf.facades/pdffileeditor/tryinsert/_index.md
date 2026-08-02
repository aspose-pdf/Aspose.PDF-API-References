---
title: "PdfFileEditor.TryInsert"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Вставляет страницы из другого файла во входной Pdf‑файл."
type: docs
weight: 420
url: /ru/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Вставляет страницы из другого файла во входный Pdf файл.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Входной Pdf файл. |
| insertLocation | Int32 | Позиция вставки во входном файле. |
| portFile | String | Страницы из Pdf‑файла. |
| pageNumber | Int32[] | Номер страницы, перенесённой в portFile. |
| outputFile | String | Выходной Pdf файл. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Метод TryInsert похож на метод Insert, за исключением того, что метод TryInsert не генерирует исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Вставляет страницы из другого файла во входный Pdf файл.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток Pdf файла. |
| insertLocation | Int32 | Позиция вставки во входном файле. |
| portStream | Stream | Поток Pdf‑файла для страниц. |
| pageNumber | Int32[] | Номер страницы, перенесённой в portFile. |
| outputStream | Stream | Выходной поток. |

### Возвращаемое значение

true, если операция завершилась успешно; иначе false.

## Примечания

Метод TryInsert похож на метод Insert, за исключением того, что метод TryInsert не генерирует исключение, если операция не удалась.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


