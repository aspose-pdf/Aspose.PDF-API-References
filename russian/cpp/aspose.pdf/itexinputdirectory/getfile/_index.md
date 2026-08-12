---
title: "Метод Aspose::Pdf::ITeXInputDirectory::GetFile"
linktitle: "GetFile"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::ITeXInputDirectory::GetFile. Возвращает поток для чтения или записи в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/itexinputdirectory/getfile/
---
## ITeXInputDirectory::GetFile method


Возвращает поток для чтения или записи.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Pdf::ITeXInputDirectory::GetFile(System::String fileName, System::String &fullName, bool searchSubdirectories=false)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | System::String | Имя файла. |
| fullName | System::String\& | Полное имя файла. |
| searchSubdirectories | bool | Указывает, следует ли искать файл в подпапках. |

### ReturnValue

Поток.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ITeXInputDirectory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
