---
title: "Метод Aspose::Pdf::TeXMemoryOutputDirectory::GetFile"
linktitle: "GetFile"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::TeXMemoryOutputDirectory::GetFile. Возвращает поток для чтения в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf/texmemoryoutputdirectory/getfile/
---
## TeXMemoryOutputDirectory::GetFile method


Возвращает поток для чтения.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::TeXMemoryOutputDirectory::GetFile(System::String fileName, System::String &fullName, bool searchSubdirectories=false) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | System::String | Имя файла. |
| fullName | System::String\& | Полное имя файла. |
| searchSubdirectories | bool | Указывает, следует ли искать файл в подпапках. В этой реализации не оказывает влияния. |

### ReturnValue

Поток.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [TeXMemoryOutputDirectory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
