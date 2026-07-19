---
title: "Класс System::IO::Path"
linktitle: "Path"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::IO::Path. Предоставляет методы для работы с путями. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом в C++."
type: docs
weight: 1900
url: /ru/cpp/system.io/path/
---
## Path class


Предоставляет методы для работы с путями. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
class Path
```

## Методы

| Метод | Описание |
| --- | --- |
| static [ChangeExtension](./changeextension/)(const String\&, const String\&) | Изменяет расширение в указанном пути к файлу. |
| static [CheckPath](./checkpath/)(const String\&, const String\&, bool) | Определяет, является ли указанный путь допустимым, проверяя наличие недопустимых символов. Исключение выбрасывается, если путь содержит недопустимые символы. |
| static [Combine](./combine/)(const ArrayPtr\<String\>\&) | Объединяет указанные сегменты пути в единый путь, при необходимости вставляя символы разделителя каталогов между сегментами. |
| static [Combine](./combine/)(const String\&, const String\&) | Объединяет два указанных сегмента пути в единый путь, при необходимости вставляя символ разделителя каталогов между сегментами. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&) | Объединяет три указанных сегмента пути в единый путь, при необходимости вставляя символы разделителя каталогов между сегментами. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&, const String\&) | Объединяет четыре указанных сегмента пути в единый путь, при необходимости вставляя символы разделителя каталогов между сегментами. |
| static [GetDirectoryName](./getdirectoryname/)(const String\&) | Возвращает имя каталога, на который ссылается указанный путь. |
| static [GetExtension](./getextension/)(const String\&) | Возвращает расширение файла, на который ссылается указанный путь. |
| static [GetFileName](./getfilename/)(const String\&) | Возвращает имя файла, на который указывает указанный путь. |
| static [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const String\&) | Возвращает имя без расширения файла, на который указывает указанный путь. |
| static [GetFullPath](./getfullpath/)(const String\&) | Преобразует указанный путь в абсолютный путь. |
| static [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Возвращает массив, содержащий символы, недопустимые в именах файлов. |
| static [GetInvalidPathChars](./getinvalidpathchars/)() | Возвращает массив, содержащий символы, недопустимые в именах путей. |
| static [GetPathRoot](./getpathroot/)(const String\&) | Возвращает корневой каталог указанного пути. |
| static [GetRandomFileName](./getrandomfilename/)() | Возвращает случайно сгенерированное имя файла. |
| static [GetTempFileName_](./gettempfilename_/)() | Создает новый файл с уникальным именем и возвращает полный путь к нему. |
| static [GetTempFileNameSafe](./gettempfilenamesafe/)() | Создает новый файл с уникальным именем и возвращает полный путь к нему. Является синонимом метода [GetTempFileName_()](./gettempfilename_/). |
| static [GetTempPath](./gettemppath/)() | Возвращает путь к временной директории текущего пользователя. |
| static [HasExtension](./hasextension/)(const String\&) | Определяет, указывает ли указанный путь на файл с расширением. |
| static [IsPathRooted](./ispathrooted/)(const String\&) | Определяет, содержит ли указанный путь корень. |
| static [NormalizePath](./normalizepath/)(const String\&) | Нормализует указанный путь. |
| static [ToBoost](./toboost/)(const String\&) | Возвращает экземпляр класса boost::filesystem::path, представляющего указанный путь. |
| static [ToString](./tostring/)(const boost::filesystem::path\&) | Возвращает строковое представление указанного объекта пути Boost. |
## Поля

| Поле | Описание |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Альтернативный символ, используемый для разделения уровней каталогов в пути. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Символ, используемый для разделения уровней каталогов в пути. |
| static [PathSeparator](./pathseparator/) | Символ-разделитель, используемый для разделения строк путей в переменных окружения. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Символ-разделитель тома. |
## Примечания



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Сгенерировать случайное имя файла.
  auto filename = Path::GetRandomFileName();

  // Вывести информацию о имени файла.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## См. также

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
