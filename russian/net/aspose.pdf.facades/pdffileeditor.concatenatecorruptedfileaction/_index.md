---
title: "Перечисление PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Перечисление Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction. Действие, выполняемое при встрече повреждённого файла в процессе конкатенации"
type: docs
weight: 4590
url: /ru/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Действие, выполняемое при встрече повреждённого файла в процессе конкатенации.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| StopWithError | `0` | Если обнаружен повреждённый файл, то остановите процесс конкатенации и верните ошибку. |
| ConcatenateIgnoringCorrupted | `1` | Если обнаружен повреждённый файл, то не останавливайте конкатенацию и не обрабатывайте повреждённый файл. Список повреждённых файлов доступен в свойстве Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Когда в исходном документе встречается повреждённый объект, процесс не будет остановлен, и только повреждённый объект будет игнорироваться. |

### См. также

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


