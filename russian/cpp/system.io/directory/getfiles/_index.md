---
title: "System::IO::Directory::GetFiles метод"
linktitle: "GetFiles"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::Directory::GetFiles метод. Выполняет поиск файлов, соответствующих указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог, в C++."
type: docs
weight: 1200
url: /ru/cpp/system.io/directory/getfiles/
---
## Directory::GetFiles method


Ищет файлы, соответствующие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Полный или относительный путь к каталогу для поиска |
| searchPattern | const String\& | Шаблон имени файлов для поиска |
| searchOption | SearchOption | Указывает, следует ли выполнять поиск только в указанном каталоге или во всём дереве каталогов, корнем которого является указанный каталог |

### ReturnValue

Массив полных путей найденных файлов, имена которых соответствуют **searchPattern**

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
