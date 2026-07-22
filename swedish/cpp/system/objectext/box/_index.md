---
title: "System::ObjectExt::Box metod"
linktitle: "Box"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::Box metod. Boxar strängvärden i C++."
type: docs
weight: 200
url: /sv/cpp/system/objectext/box/
---
## ObjectExt::Box(const String\&) method


Packar strängvärden.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Värde att boxa. |

### ReturnValue

Boxat värde eller null, om källsträngen är null.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Box(const T\&) method


Boxar värdetyper för konvertering till [Object](../../object/). Implementation för enum‑typer.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Enum](../../enum/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) värde att låsa in. |

### ReturnValue

Smart‑pekare till objekt som behåller det boxade värdet.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Box(const T\&) method


Boxar värdetyper för konvertering till [Object](../../object/). Implementation för icke‑enum‑typer.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const T\& | Värde att boxa. |

### ReturnValue

Smart‑pekare till objekt som behåller det boxade värdet.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Box(const T\&) method


Boxar [Nullable](../../nullable/)‑typer för konvertering till [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const T\& | Värde att boxa. |

### ReturnValue

Smart‑pekare till objekt som behåller det boxade värdet.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
