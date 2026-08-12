---
title: "System::IO::DirectoryInfo::EnumerateDirectories метод"
linktitle: "EnumerateDirectories"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::DirectoryInfo::EnumerateDirectories. Возвращает перечисляемую коллекцию, содержащую все каталоги, расположенные в каталоге, представляемом текущим объектом, в C++."
type: docs
weight: 500
url: /ru/cpp/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() method


Возвращает перечисляемую коллекцию, содержащую все каталоги, расположенные в каталоге, представленном текущим объектом.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&) method


Ищет каталоги, соответствующие указанным критериям поиска, в каталоге, представленном текущим объектом.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени каталогов для поиска |

### ReturnValue

Перечисляемая коллекция разделяемых указателей на объекты [DirectoryInfo](../), представляющие найденные каталоги, имена которых соответствуют **searchPattern**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) method


Ищет каталоги, соответствующие указанным критериям поиска, либо в каталоге, представленном текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представленный текущим объектом.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени каталогов для поиска |
| searchOption | SearchOption | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всем дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### ReturnValue

Перечисляемая коллекция разделяемых указателей на объекты [DirectoryInfo](../), представляющие найденные каталоги, имена которых соответствуют **searchPattern**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
