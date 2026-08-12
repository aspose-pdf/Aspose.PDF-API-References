---
title: "System::IO::Directory::Delete метод"
linktitle: "Удалить"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::Directory::Delete метод. Удаляет указанный файл или каталог. Не генерирует исключений в C++."
type: docs
weight: 200
url: /ru/cpp/system.io/directory/delete/
---
## Directory::Delete method


Удаляет указанный файл или каталог. Не генерирует исключений.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к каталогу или файлу, который необходимо удалить |
| рекурсивный | bool | Если **path** указывает на непустой каталог, то **recursive** определяет, следует ли удалять всё содержимое каталога рекурсивно; если каталог, указанный в **path**, не пуст и **recursive** равно 'false', операция завершается с ошибкой |

## См. также

* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
