---
title: "System::IO::STDIOStreamPositionPreference enum"
linktitle: "STDIOStreamPositionPreference"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::STDIOStreamPositionPreference enum. Определяет, какая позиция в потоке предпочтительна в качестве общей позиции чтения и записи, когда std::basic_iostream и его наследники будут иметь разные позиции чтения и записи во время создания обёртки в C++."
type: docs
weight: 3600
url: /ru/cpp/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference enum


Определяет, какая позиция в потоке предпочтительна в качестве общей позиции чтения и записи, когда std::basic_iostream и его наследники имеют разные позиции чтения и записи в момент создания обёртки.

```cpp
enum class STDIOStreamPositionPreference
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Ноль | 0 | Позиция ноль будет установлена как позиция чтения и записи. |
| ReadPosition | 1 | Позиция gptr будет установлена как позиция чтения и записи. |
| WritePosition | 2 | Позиция pptr будет установлена как позиция чтения и записи. |

## См. также

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
