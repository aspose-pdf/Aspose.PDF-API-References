---
title: "System::ObjectExt::UnknownToObject‑metod"
linktitle: "UnknownToObject"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::UnknownToObject‑metod. Konverterar okänd typ till Object, och hanterar både smartpekartyp och värdetyp‑situationer i C++."
type: docs
weight: 1900
url: /sv/cpp/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(const T\&) method


Konverterar okänd typ till [Object](../../object/), och hanterar både smartpekartyp‑ och värdetyp‑situationer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ att konvertera till [Object](../../object/). |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) att konvertera. |

### ReturnValue

Smartpekare till [Object](../../object/) som antingen är en konverterad pekare eller ett inramat värde.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::UnknownToObject(T) method


Konverterar okänd typ till [Object](../../object/), och hanterar både smartpekartyp‑ och värdetyp‑situationer.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ att konvertera till [Object](../../object/). |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | [Object](../../object/) att konvertera. |

### ReturnValue

Smartpekare till [Object](../../object/) som antingen är en konverterad pekare eller ett inramat värde.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
