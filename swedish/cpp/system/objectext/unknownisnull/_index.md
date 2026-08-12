---
title: "System::ObjectExt::UnknownIsNull metod"
linktitle: "UnknownIsNull"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::UnknownIsNull metod. Kontrollerar om ett objekt av okänd typ är nullptr. Överlagring för icke‑skalära typer i C++."
type: docs
weight: 1800
url: /sv/cpp/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) method


Kontrollerar om okänt typobjekt är nullptr. Överlagring för icke-skalära typer.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../object/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | [Object](../../object/) att kontrollera. |

### ReturnValue

Sant om 'obj == nullptr' är sant, annars falskt.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::UnknownIsNull(T) method


Kontrollerar om okänt typobjekt är nullptr. Överlagring för skalära typer.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../object/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | [Object](../../object/) att kontrollera. |

### ReturnValue

Returnerar alltid falskt.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
