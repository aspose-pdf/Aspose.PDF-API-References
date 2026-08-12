---
title: "Перечисление System::Reflection::BindingFlags"
linktitle: "BindingFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление System::Reflection::BindingFlags. Определяет режимы поиска членов и типов и привязки в C++."
type: docs
weight: 1100
url: /ru/cpp/system.reflection/bindingflags/
---
## BindingFlags enum


Определяет режимы поиска членов и типов и их привязки.

```cpp
enum class BindingFlags
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | 0 | Нет специальных параметров. |
| IgnoreCase | 1 | Игнорировать регистр имени при поиске элемента. |
| DeclaredOnly | 2 | Искать только члены, объявленные в типе, а не в базовых типах. |
| Instance | 4 | Просматривать члены экземпляра. |
| Static | 8 | Просматривать статические члены. |
| Public | 16 | Просматривать публичные члены. |
| NonPublic | 32 | Просматривать непубличные члены. |
| FlattenHierarchy | 64 | Просматривать публичные и защищённые статические члены базового типа. |
| InvokeMethod | 256 | Вызывает метод. |
| CreateInstance | 512 | Создаёт экземпляр отражённого типа. |
| GetField | 1024 | Получает значение поля. |
| SetField | 2048 | Устанавливает значение поля. |
| GetProperty | 4096 | Получает значение свойства. |
| SetProperty | 8192 | Устанавливает значение свойства. |
| PutDispProperty | 16384 | Устанавливает COM‑свойство. |
| PutRefDispProperty | 32768 | Устанавливает COM‑свойство‑ссылку. |
| ExactBinding | 65536 | Привязка типа должна быть точной, без каких-либо изменений типа. |
| SuppressChangeType | 131072 | Не поддерживается. |
| OptionalParamBinding | 262144 | Выбирает перегрузку на основе количества аргументов. |
| IgnoreReturn | 16777216 | Игнорирует возвращаемое значение COM‑interop. |

## См. также

* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
