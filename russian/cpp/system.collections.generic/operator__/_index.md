---
title: "метод System::Collections::Generic::operator<<"
linktitle: "operator<<"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Collections::Generic::operator<<. Вставляет данные в поток с использованием кодировки UTF-8 в C++."
type: docs
weight: 5400
url: /ru/cpp/system.collections.generic/operator__/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) method


Вставьте данные в поток, используя кодировку UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


| Параметр | Описание |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | std::ostream\& | Выходной поток для вставки данных. |
| pair | const KeyValuePair\<TKey, TValue\>\& | [Data](../../system.data/) для вставки. |

### ReturnValue

**stream**.

## См. также

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) method


Вставьте данные в поток.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


| Параметр | Описание |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | std::wostream\& | Выходной поток для вставки данных. |
| pair | const KeyValuePair\<TKey, TValue\>\& | [Data](../../system.data/) для вставки. |

### ReturnValue

**stream**.

## См. также

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
