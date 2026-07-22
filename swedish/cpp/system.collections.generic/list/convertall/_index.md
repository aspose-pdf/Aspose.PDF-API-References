---
title: "System::Collections::Generic::List::ConvertAll‑metod"
linktitle: "ConvertAll"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::List::ConvertAll‑metod. Skapar en lista med element konverterade till en annan typ i C++."
type: docs
weight: 1300
url: /sv/cpp/system.collections.generic/list/convertall/
---
## List::ConvertAll method


Skapar en lista med element konverterade till en annan typ.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


| Parameter | Beskrivning |
| --- | --- |
| OutputType | Utdata‑listans elementtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| converter | Converter\<T, OutputType\> | [Converter](../../../system/converter/) att använda för konvertering av objekt. |

### ReturnValue

En nyss skapad lista med konverterade element.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../)
* Typedef [Converter](../../../system/converter/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
