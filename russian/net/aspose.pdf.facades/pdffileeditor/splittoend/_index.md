---
title: "PdfFileEditor.SplitToEnd"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Делит от указанного места и сохраняет заднюю часть как новый файл."
type: docs
weight: 360
url: /ru/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Разделяет от указанного места и сохраняет заднюю часть как новый поток файла.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного Pdf‑файла. |
| место | Int32 | Позиция разреза. |
| outputStream | Stream | Выходной поток Pdf‑файла. |

### Возвращаемое значение

True при успехе, иначе false.

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

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Разделяет от места и сохраняет заднюю часть как новый файл.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Исходный Pdf‑файл. |
| место | Int32 | Позиция разреза. |
| outputFile | String | Путь к выходному Pdf‑файлу. |

### Возвращаемое значение

True при успехе, иначе false.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Разделяет от указанного места и сохраняет заднюю часть как новый поток файла.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного Pdf‑файла. |
| место | Int32 | Позиция разреза. |
| outputStream | Stream | Выходной поток Pdf‑файла. |

### Возвращаемое значение

True при успехе, иначе false.

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

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


