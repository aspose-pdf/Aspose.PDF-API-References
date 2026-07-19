---
title: "класс System::IO::Directory"
linktitle: "Каталог"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::IO::Directory. Содержит методы для работы с каталогами. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом в C++."
type: docs
weight: 1100
url: /ru/cpp/system.io/directory/
---
## Directory class


Содержит методы для работы с каталогами. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
class Directory
```

## Методы

| Метод | Описание |
| --- | --- |
| static [CreateDirectory_](./createdirectory_/)(const String\&) | Создаёт все каталоги в указанном пути, если они не существуют. |
| static [Delete](./delete/)(const String\&, bool) | Удаляет указанный файл или каталог. Не генерирует исключений. |
| static [EnumerateDirectories](./enumeratedirectories/)(const String\&, const String\&, SearchOption) | Ищет каталоги, соответствующие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог. |
| static [EnumerateFiles](./enumeratefiles/)(const String\&, const String\&, SearchOption) | Ищет файлы, соответствующие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог. |
| static [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const String\&, const String\&, SearchOption) | Ищет файлы и каталоги, которые удовлетворяют указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корневым в указанном каталоге. |
| static [Exists](./exists/)(const String\&) | Определяет, указывает ли указанный путь на существующий каталог. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Возвращает время создания указанной сущности в локальном времени. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Возвращает время создания указанной сущности в формате UTC. |
| static [GetCurrentDirectory](./getcurrentdirectory/)() | Возвращает полное имя (включая путь) текущего каталога. |
| static [GetDirectories](./getdirectories/)(const String\&, const String\&, SearchOption) | Ищет каталоги, соответствующие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог. |
| static [GetDirectoryRoot](./getdirectoryroot/)(const String\&) | Возвращает корневой каталог указанного пути. |
| static [GetFiles](./getfiles/)(const String\&, const String\&, SearchOption) | Ищет файлы, соответствующие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог. |
| static [GetFileSystemEntries](./getfilesystementries/)(const String\&, const String\&, SearchOption) | Ищет файлы и каталоги, которые удовлетворяют указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корневым в указанном каталоге. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Возвращает время последнего доступа к указанной сущности в локальном времени. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Возвращает время последнего доступа к указанной сущности в формате UTC. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Возвращает время последней записи указанной сущности в локальном времени. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Возвращает время последней записи указанной сущности в формате UTC. |
| static [GetLogicalDrives](./getlogicaldrives/)() | НЕ РЕАЛИЗОВАНО. |
| static [GetParent](./getparent/)(const String\&) | Возвращает умный указатель на объект [DirectoryInfo](../directoryinfo/), представляющий родительский каталог указанной сущности. |
| static [Move](./move/)(const String\&, const String\&) | Перемещает указанную сущность в новое место. Если перемещаемая сущность является каталогом, она перемещается со всем её содержимым. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | Устанавливает время создания указанной сущности как локальное время. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | Устанавливает время создания указанной сущности как время UTC. |
| static [SetCurrentDirectory](./setcurrentdirectory/)(const String\&) | Устанавливает текущий каталог. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | Устанавливает время последнего доступа к указанной сущности как локальное время. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | Устанавливает время последнего доступа к указанной сущности как время UTC. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Устанавливает время последней записи указанной сущности в локальном времени. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Устанавливает время последней записи указанной сущности в формате UTC. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Псевдоним для умного указателя на объект IEnumerable, перечисляющий набор объектов [String](../../system/string/). |
## Примечания



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Создаёт строки, содержащие пути к каталогам.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Проверяет, существуют ли каталоги.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Выводит информацию о временном каталоге.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Directory 'C:\' exists.
Directory 'C:\Some directory' doesn't exist.
Directory 'C:\Users\lanor\AppData\Local\Temp\' exists.
Creation Time: 27.08.2021 14:21:42
Last Access Time: 07.10.2021 12:16:41
Last Write Time: 07.10.2021 12:16:41
*/
```

## См. также

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
