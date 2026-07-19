---
title: "Aspose::Pdf::FileParams класс"
linktitle: "FileParams"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::FileParams класс. Определяет словарь параметров встроенного файла, который должен содержать дополнительную информацию, специфичную для файла, в C++."
type: docs
weight: 5400
url: /ru/cpp/aspose.pdf/fileparams/
---
## FileParams class


Определяет словарь параметров встроенного файла, который должен содержать дополнительную информацию, специфичную для файла.

```cpp
class FileParams : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [FileParams](./fileparams/)(const System::SharedPtr\<FileSpecification\>\&) | Конструктор класса [FileParams](./). |
| [get_CheckSum](./get_checksum/)() | 16-байтовая строка, являющаяся контрольной суммой байтов несжатого встроенного файла. Контрольная сумма вычисляется с помощью стандартного алгоритма MD5 к байтам потока встроенного файла. |
| [get_CreationDate](./get_creationdate/)() | Дата и время создания встроенного файла. |
| [get_ModDate](./get_moddate/)() | Дата и время последнего изменения встроенного файла. |
| [get_Size](./get_size/)() | Размер несжатого встроенного файла в байтах. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Дата и время создания встроенного файла. |
| [set_ModDate](./set_moddate/)(System::DateTime) | Дата и время последнего изменения встроенного файла. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
