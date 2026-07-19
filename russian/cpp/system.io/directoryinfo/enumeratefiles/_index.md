---
title: "Метод System::IO::DirectoryInfo::EnumerateFiles"
linktitle: "EnumerateFiles"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::DirectoryInfo::EnumerateFiles. Возвращает перечисляемую коллекцию, содержащую все файлы, находящиеся в каталоге, представляемом текущим объектом, в C++."
type: docs
weight: 600
url: /ru/cpp/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() method


Возвращает перечисляемую коллекцию, содержащую все файлы, расположенные в каталоге, представленном текущим объектом.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&) method


Ищет файлы, соответствующие указанным критериям поиска, в каталоге, представленном текущим объектом.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени файлов для поиска |

### ReturnValue

Перечисляемая коллекция разделяемых указателей на объекты [FileInfo](../../fileinfo/), представляющих найденные файлы, имена которых соответствуют **searchPattern**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) method


Ищет файлы, соответствующие указанным критериям поиска, либо в каталоге, представленном текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представленный текущим объектом.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени файлов для поиска |
| searchOption | SearchOption | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всем дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### ReturnValue

Перечисляемая коллекция разделяемых указателей на объекты [FileInfo](../../fileinfo/), представляющих найденные файлы, имена которых соответствуют **searchPattern**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
