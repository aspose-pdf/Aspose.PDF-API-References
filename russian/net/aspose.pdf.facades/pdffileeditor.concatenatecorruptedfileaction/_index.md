---
title: PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF для справочника API .NET
description: Действие выполняемое при обнаружении поврежденного файла в процессе объединения.
type: docs
weight: 2480
url: /ru/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Действие, выполняемое при обнаружении поврежденного файла в процессе объединения.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| StopWithError | `0` | Если был обнаружен поврежденный файл, остановить процесс объединения и вернуть ошибку. |
| ConcatenateIgnoringCorrupted | `1` | Если был обнаружен поврежденный файл, то не останавливать объединение и не обрабатывать поврежденный файл. Список поврежденных файлов доступен в свойстве Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Когда в исходном документе встречается поврежденный объект, процесс не останавливается, и игнорируется только поврежденный объект. |

### Смотрите также

* class [PdfFileEditor](../pdffileeditor)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
