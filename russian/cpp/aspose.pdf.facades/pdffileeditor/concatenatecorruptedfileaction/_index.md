---
title: "Aspose::Pdf::Facades::PdfFileEditor::ConcatenateCorruptedFileAction enum"
linktitle: "ConcatenateCorruptedFileAction"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::ConcatenateCorruptedFileAction enum. Действие, выполняемое при встрече повреждённого файла в процессе конкатенации в C++."
type: docs
weight: 7200
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/concatenatecorruptedfileaction/
---
## ConcatenateCorruptedFileAction enum


Действие, выполняемое при обнаружении повреждённого файла в процессе объединения.

```cpp
enum class ConcatenateCorruptedFileAction
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| StopWithError | 0 | Если был обнаружен повреждённый файл, то процесс конкатенации останавливается и возвращается ошибка. |
| ConcatenateIgnoringCorrupted | 1 | Если был обнаружен повреждённый файл, то процесс конкатенации не останавливается и повреждённый файл не обрабатывается. Список повреждённых файлов доступен в свойстве Failures. |
| ConcatenateIgnoringCorruptedObjects | 2 | Когда в исходном документе встречается повреждённый объект, процесс не останавливается, и повреждённый объект просто игнорируется. |

## См. также

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
