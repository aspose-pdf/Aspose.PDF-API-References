---
title: "System::IO::DirectoryInfo::GetFileSystemInfos метод"
linktitle: "GetFileSystemInfos"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::DirectoryInfo::GetFileSystemInfos. Возвращает массив, содержащий разделяемые указатели на объекты FileSystemInfo, представляющие все файлы и каталоги, расположенные в каталоге, представляемом текущим объектом, в C++."
type: docs
weight: 1400
url: /ru/cpp/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method


Возвращает массив, содержащий разделяемые указатели на объекты [FileSystemInfo](../../filesysteminfo/), представляющие все файлы и каталоги, расположенные в каталоге, представляемом текущим объектом.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFileSystemInfos(const String\&) method


Ищет файлы и каталоги, соответствующие указанным критериям поиска, в каталоге, представленном текущим объектом.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени файлов и каталогов для поиска |

### ReturnValue

Массив разделяемых указателей на объекты [FileSystemInfo](../../filesysteminfo/), представляющие найденные файлы и каталоги, имена которых соответствуют **searchPattern**

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) method


Ищет файлы и каталоги, соответствующие указанным критериям поиска, либо в каталоге, представленном текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представленный текущим объектом.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени файлов и каталогов для поиска |
| searchOption | SearchOption | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всем дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### ReturnValue

Массив разделяемых указателей на объекты [FileSystemInfo](../../filesysteminfo/), представляющие найденные файлы и каталоги, имена которых соответствуют **searchPattern**

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
