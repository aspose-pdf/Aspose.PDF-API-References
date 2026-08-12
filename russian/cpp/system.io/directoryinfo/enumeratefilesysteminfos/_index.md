---
title: "System::IO::DirectoryInfo::EnumerateFileSystemInfos метод"
linktitle: "EnumerateFileSystemInfos"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::DirectoryInfo::EnumerateFileSystemInfos method. Возвращает перечисляемую коллекцию, содержащую все файлы и каталоги, расположенные в каталоге, представляемом текущим объектом, в C++."
type: docs
weight: 700
url: /ru/cpp/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() method


Возвращает перечисляемую коллекцию, содержащую все файлы и каталоги, расположенные в каталоге, представленном текущим объектом.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&) method


Ищет файлы и каталоги, соответствующие указанным критериям поиска, в каталоге, представленном текущим объектом.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени файлов и каталогов для поиска |

### ReturnValue

Перечисляемая коллекция умных указателей на объекты [FileSystemInfo](../../filesysteminfo/), представляющие найденные файлы и каталоги, имена которых соответствуют **searchPattern**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) method


Ищет файлы и каталоги, соответствующие указанным критериям поиска, либо в каталоге, представленном текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представленный текущим объектом.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени файлов и каталогов для поиска |
| searchOption | SearchOption | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всем дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### ReturnValue

Перечисляемая коллекция умных указателей на объекты [FileSystemInfo](../../filesysteminfo/), представляющие найденные файлы и каталоги, имена которых соответствуют **searchPattern**

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
