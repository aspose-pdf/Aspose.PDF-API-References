---
title: "System::IO::Directory::EnumerateFiles метод"
linktitle: "EnumerateFiles"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::Directory::EnumerateFiles метод. Ищет файлы, соответствующие указанным критериям поиска, либо в заданном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог, в C++."
type: docs
weight: 400
url: /ru/cpp/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles method


Ищет файлы, соответствующие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Полный или относительный путь к каталогу для поиска |
| searchPattern | const String\& | Шаблон имени файлов для поиска |
| searchOption | SearchOption | Указывает, следует ли выполнять поиск только в указанном каталоге или во всём дереве каталогов, корнем которого является указанный каталог |

### ReturnValue

Перечисляемая коллекция полных путей найденных файлов, имена которых соответствуют **searchPattern**

## См. также

* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
