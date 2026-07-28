---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Справочник API Aspose.PDF для Java"
description: "Действие, выполняемое при обнаружении повреждённого файла в процессе конкатенации."
type: docs
weight: 420
url: /ru/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

Действие, выполняемое при обнаружении повреждённого файла в процессе конкатенации.

## Поля

| Поле | Описание |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | Если обнаружен повреждённый файл, то не останавливать конкатенацию и не обрабатывать повреждённый файл. Список повреждённых файлов доступен в свойстве Failures. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | Когда в исходном документе встречается повреждённый объект, процесс не будет остановлен, а повреждённый объект будет просто игнорироваться. |
| [StopWithError](#StopWithError) | Если обнаружен повреждённый файл, то остановить процесс конкатенации и вернуть ошибку. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

Если обнаружен повреждённый файл, то не останавливать конкатенацию и не обрабатывать повреждённый файл. Список повреждённых файлов доступен в свойстве Failures.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

Когда в исходном документе встречается повреждённый объект, процесс не будет остановлен, а повреждённый объект будет просто игнорироваться.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

Если обнаружен повреждённый файл, то остановить процесс конкатенации и вернуть ошибку.
