---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Enum PdfFileEditorConcatenateCorruptedFileAction от Aspose.Pdf.Facades. Действие, выполняемое при встрече поврежденного файла в процессе конкатенации
type: docs
weight: 4470
url: /ru/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## Перечисление PdfFileEditor.ConcatenateCorruptedFileAction

Действие, выполняемое при встрече поврежденного файла в процессе конкатенации.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| StopWithError | `0` | Если был встречен поврежденный файл, то остановить процесс конкатенации и вернуть ошибку. |
| ConcatenateIgnoringCorrupted | `1` | Если был встречен поврежденный файл, то не останавливать конкатенацию и не обрабатывать поврежденный файл. Список поврежденных файлов доступен в свойстве Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Когда в исходном документе встречается поврежденный объект, процесс не останавливается, и только поврежденный объект игнорируется. |

### См. также

* класс [PdfFileEditor](../pdffileeditor/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)