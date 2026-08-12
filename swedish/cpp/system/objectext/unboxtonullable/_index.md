---
title: "System::ObjectExt::UnboxToNullable metod"
linktitle: "UnboxToNullable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::UnboxToNullable metod. Avpaketerar objekt till nullable‑typ i C++."
type: docs
weight: 1700
url: /sv/cpp/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable method


Packar upp objekt till nullable-typ.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=true)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Destinationstyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) att avpaketera. |
| säker | bool | Om true, returnera nullptr vid fel, annars kasta InvalidCastException. |

### ReturnValue

Avpaketerat nullable‑värde (kan vara null).

## Se även

* Class [Nullable](../../nullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
