---
title: "System::IO::DirectoryInfo::GetFiles метод"
linktitle: "GetFiles"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::DirectoryInfo::GetFiles. Возвращает массив, содержащий разделяемые указатели на объекты FileInfo, представляющие все каталоги, расположенные в каталоге, представляемом текущим объектом, в C++."
type: docs
weight: 1300
url: /ru/cpp/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() method


Возвращает массив, содержащий разделяемые указатели на объекты [FileInfo](../../fileinfo/), представляющие все каталоги, расположенные в каталоге, представляемом текущим объектом.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFiles(const String\&) method


Ищет файлы, соответствующие указанным критериям поиска, в каталоге, представленном текущим объектом.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени файлов для поиска |

### ReturnValue

Массив разделяемых указателей на объекты [FileInfo](../../fileinfo/), представляющие найденные файлы, имена которых соответствуют **searchPattern**

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFiles(const String\&, SearchOption) method


Ищет файлы, соответствующие указанным критериям поиска, либо в каталоге, представленном текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представленный текущим объектом.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const String\& | Шаблон имени файлов для поиска |
| searchOption | SearchOption | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всем дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### ReturnValue

Массив разделяемых указателей на объекты [FileInfo](../../fileinfo/), представляющие найденные файлы, имена которых соответствуют **searchPattern**

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
