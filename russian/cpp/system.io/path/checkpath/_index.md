---
title: "Метод System::IO::Path::CheckPath"
linktitle: "CheckPath"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::Path::CheckPath. Определяет, является ли указанный путь допустимым, проверяя наличие недопустимых символов. Исключение выбрасывается, если путь содержит недопустимые символы в C++."
type: docs
weight: 200
url: /ru/cpp/system.io/path/checkpath/
---
## Path::CheckPath method


Определяет, является ли указанный путь допустимым, проверяя наличие недопустимых символов. Исключение выбрасывается, если путь содержит недопустимые символы.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=true)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь для проверки |
| msg | const String\& | Сообщение, передаваемое конструктору объекта исключения |
| allow_empty | bool | Указывает, следует ли считать пустую или нулевую строку корректным путём (true) или нет (false); если этот параметр имеет значение false и **path** пуст, бросается ArgumentException; если этот параметр имеет значение false и **path** равен null, бросается ArgumentNullException. |

## См. также

* Class [String](../../../system/string/)
* Class [Path](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
