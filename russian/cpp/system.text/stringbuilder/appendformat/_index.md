---
title: "System::Text::StringBuilder::AppendFormat метод"
linktitle: "AppendFormat"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::StringBuilder::AppendFormat метод. Добавляет отформатированную строку в builder в C++."
type: docs
weight: 400
url: /ru/cpp/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) method


Добавляет отформатированную строку в построитель.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


| Параметр | Описание |
| --- | --- |
| TArgs | Тип аргументов. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| fp | const SharedPtr\<IFormatProvider\>\& | Поставщик формата; игнорируется. |
| формат | const String\& | Строка формата. |
| args | const TArgs\&... | Аргументы для вставки в позиции форматной строки. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFormatProvider](../../../system/iformatprovider/)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) method


Добавляет отформатированную строку в построитель.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


| Параметр | Описание |
| --- | --- |
| TArgs | Тип аргументов. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| формат | const String\& | Строка формата. |
| args | const TArgs\&... | Аргументы для вставки в позиции форматной строки. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
