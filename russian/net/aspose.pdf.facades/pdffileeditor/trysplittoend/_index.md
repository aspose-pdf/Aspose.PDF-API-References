---
title: "PdfFileEditor.TrySplitToEnd"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileEditor. Делит от указанного места и сохраняет заднюю часть как новый файл."
type: docs
weight: 470
url: /ru/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Разделяет от места и сохраняет заднюю часть как новый файл.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | Исходный Pdf‑файл. |
| место | Int32 | Позиция разреза. |
| outputFile | String | Путь к выходному Pdf‑файлу. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Метод TrySplitToEnd аналогичен методу SplitToEnd, за исключением того, что метод TrySplitToEnd не бросает исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Разделяет от указанного места и сохраняет заднюю часть как новый поток файла.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток исходного Pdf‑файла. |
| место | Int32 | Позиция разреза. |
| outputStream | Stream | Выходной поток Pdf‑файла. |

### Возвращаемое значение

True при успехе, иначе false.

## Примечания

Потоки НЕ закрываются после этой операции, если не указано CloseConcatedStreams. Метод TrySplitToEnd аналогичен методу SplitToEnd, за исключением того, что метод TrySplitToEnd не бросает исключение, если операция завершается неудачей.

## Примеры

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


