---
title: "Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip метод"
linktitle: "Strip"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip метод. Удаляет Java Script из документа в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.facades/pdfjavascriptstripper/strip/
---
## PdfJavaScriptStripper::Strip(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Удалить Java Script из документа.

```cpp
bool Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip(const System::SharedPtr<System::IO::Stream> &inStream, const System::SharedPtr<System::IO::Stream> &outStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий документ. |
| outStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет сохранён документ. |

### ReturnValue

true, если JavaScript был успешно удалён.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfJavaScriptStripper](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfJavaScriptStripper::Strip(const System::String\&, const System::String\&) method


Удалить Java Script из документа.

```cpp
bool Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip(const System::String &inputFile, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Файл, содержащий документ. |
| outputFile | const System::String\& | Файл, в котором будет сохранён документ. |

### ReturnValue

true, если JavaScript был успешно удалён.

## См. также

* Class [String](../../../system/string/)
* Class [PdfJavaScriptStripper](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
