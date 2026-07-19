---
title: "System::IO::File::WriteAllLines method"
linktitle: "WriteAllLines"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::WriteAllLines method. Создаёт новый текстовый файл или перезаписывает существующий и записывает все строки из указанного массива строк в него, каждая строка на новой строке, используя указанную кодировку в C++."
type: docs
weight: 3600
url: /ru/cpp/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) method


Создает новый текстовый файл или перезаписывает существующий и записывает все строки из указанного массива строк в него, каждую строку на новой строке, используя указанную кодировку.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Файл для создания или перезаписи |
| contents | const ArrayPtr\<String\>\& | Массив строк |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method


Создает новый текстовый файл или перезаписывает существующий и записывает все строки из указанной перечислимой коллекции строк в него, каждую строку на новой строке, используя указанную кодировку.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Файл для создания или перезаписи |
| contents | const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | Перечисляемая коллекция строк |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
