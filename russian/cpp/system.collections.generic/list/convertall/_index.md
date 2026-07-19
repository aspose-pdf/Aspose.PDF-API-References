---
title: "Метод System::Collections::Generic::List::ConvertAll"
linktitle: "ConvertAll"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Collections::Generic::List::ConvertAll. Создаёт список элементов, преобразованных в другой тип, в C++."
type: docs
weight: 1300
url: /ru/cpp/system.collections.generic/list/convertall/
---
## List::ConvertAll method


Создаёт список элементов, преобразованных в другой тип.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


| Параметр | Описание |
| --- | --- |
| OutputType | Тип элементов выходного списка. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| converter | Converter\<T, OutputType\> | [Converter](../../../system/converter/) для преобразования элементов. |

### ReturnValue

Новосозданный список преобразованных элементов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../)
* Typedef [Converter](../../../system/converter/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
