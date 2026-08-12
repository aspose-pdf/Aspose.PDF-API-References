---
title: "System::Array::ConstrainedCopy метод"
linktitle: "ConstrainedCopy"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Array::ConstrainedCopy метод. Копирует диапазон элементов из объекта System.Array, начиная с указанного источника, в C++."
type: docs
weight: 4900
url: /ru/cpp/system/array/constrainedcopy/
---
## Array::ConstrainedCopy method


Копирует диапазон элементов из [System.Array](../), начиная с указанного источника.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве |
| DstType | Тип элементов в целевом массиве |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Исходный массив |
| srcIndex | int64_t | [Index](../../index/) в исходном массиве, обозначающий начало диапазона копируемых элементов |
| dstArray | const ArrayPtr\<DstType\>\& | Целевой массив |
| dstIndex | int64_t | [Index](../../index/) в целевом массиве, указывающий место начала вставки скопированных элементов |
| count | int64_t | Количество элементов для копирования |
## Примечания


ВРЕМЕННАЯ НЕОБРАБАТАННАЯ РЕАЛИЗАЦИЯ БЕЗ КАКИХ-ЛИБО ДОПОЛНЕНИЙ!
## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
