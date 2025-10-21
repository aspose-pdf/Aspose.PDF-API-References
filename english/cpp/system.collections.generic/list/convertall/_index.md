---
title: System::Collections::Generic::List::ConvertAll method
linktitle: ConvertAll
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::List::ConvertAll method. Creates a list of elements converted to different type in C++.'
type: docs
weight: 1300
url: /cpp/system.collections.generic/list/convertall/
---
## List::ConvertAll method


Creates a list of elements converted to different type.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


| Parameter | Description |
| --- | --- |
| OutputType | Output list element type. |

| Parameter | Type | Description |
| --- | --- | --- |
| converter | Converter\<T, OutputType\> | [Converter](../../../system/converter/) to use for items conversion. |

### ReturnValue

A newly created list of converted elements.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../)
* Typedef [Converter](../../../system/converter/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
