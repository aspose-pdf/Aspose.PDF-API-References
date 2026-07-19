---
title: "System::IO::File::AppendAllLines метод"
linktitle: "AppendAllLines"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::AppendAllLines метод. Добавляет строки из указанной коллекции строк в указанный файл, используя заданную кодировку, записывая каждую строку в новой строке. Если указанный файл не существует, он создаётся. Файл закрывается после записи всех строк в C++."
type: docs
weight: 100
url: /ru/cpp/system.io/file/appendalllines/
---
## File::AppendAllLines method


Добавляет строки из указанной коллекции строк в указанный файл, используя указанную кодировку, записывая каждую строку в новой строке. Если указанный файл не существует, он будет создан. Файл закрывается после записи всех строк.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу, в который будут добавлены строки |
| contents | const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | Строки для записи в файл |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
