---
title: "System::ObjectType::GetType metod"
linktitle: "GetType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectType::GetType metod. Implementerar typeof()-översättning. Överlagring för primitiva typer i C++."
type: docs
weight: 100
url: /sv/cpp/system/objecttype/gettype/
---
## ObjectType::GetType() method


Implementerar typeof()-översättning. Overload för primitiva typer.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den angivna typen.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Overload för enum‑typer.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den angivna typen.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Overload för strukturer och pekare.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den specificerade strukturen.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Överlagring för [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Nullable](../../nullable/) typ. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den specificerade strukturen.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Overload för MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Beskrivning |
| --- | --- |
| T | MutlicastDelegate-typ. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den specificerade strukturen.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Overload för strukturer och pekare.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver den specificerade strukturen eller pekartyp om det anropas för [SmartPtr](../../smartptr/).

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Overload för uint8_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Se även

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Överlagring för char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Se även

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Överlagring för int32_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Se även

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Överlagring för int64_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Se även

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Överlagring för bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Se även

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implementerar typeof()-översättning. Överlagring för [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Se även

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const String\&) method


Implementerar typeof()-översättning. Overload för string‑typ.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/) struktur som beskriver [String](../../string/)-typen.

## Se även

* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implementerar typeof()-översättning. Overload för smarta pekare.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Pekarobjekt-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) för att hämta [TypeInfo](../../typeinfo/) för. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/)-strukturen som beskriver den slutliga klassen för det överförda objektet.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implementerar typeof()-översättning. Overload för strukturer.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Strukturtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) för att hämta [TypeInfo](../../typeinfo/) för. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/)-strukturen som beskriver den slutliga klassen för det överförda objektet.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implementerar typeof()-översättning. Overload för undantag.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Exception](../../exception/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) för att hämta [TypeInfo](../../typeinfo/) för. |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/)-strukturen som beskriver den slutliga klassen för det överförda objektet.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T) method


Implementerar typeof()-översättning. Overload för primitiva typer.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Primitiv typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T | IGNORED |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/)-strukturen som beskriver typen av det överförda objektet.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T) method


Implementerar typeof()-översättning. Överlagring för [Nullable](../../nullable/)-typer.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Nullable](../../nullable/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T | IGNORED |

### ReturnValue

Konstant referens till [TypeInfo](../../typeinfo/)-strukturen som beskriver typen av det överförda objektet.

## Se även

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
