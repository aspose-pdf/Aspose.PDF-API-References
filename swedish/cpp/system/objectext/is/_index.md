---
title: "System::ObjectExt::Is metod"
linktitle: "Is"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::Is metod. Implementerar ''is''-operatorns översättning. Specialisering för strängliteral i C++."
type: docs
weight: 1100
url: /sv/cpp/system/objectext/is/
---
## ObjectExt::Is(const char16_t *) method


Implementerar översättning av 'is'-operatorn. Specialisering för strängliteral.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const ExceptionWrapper\<U\>\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för undantagsomslagstyper.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const ExceptionWrapper\<U\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Nullable\<U\>\&) method


Implementerar 'is'-operatorns översättning. Specialisering för [Nullable](../../nullable/) typ.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Nullable\<U\>\& | [Nullable](../../nullable/) typ. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Object\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för värdetyper.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Object\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för icke-konverterbara typer.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Returnerar alltid falskt eftersom typerna är icke-konvertibla.

## Se även

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för nullable-typer.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för boxbara typer med definierad ==-operator.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för boxbara typer utan definierad ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för pekartyper.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för enum-typer.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |
| U | Typ av det pekade objektet. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<V\>\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för värdetyper som är boxade till gränssnitt.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |
| V | Typ av det pekade objektet. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<V\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [Object](../../object/)
* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const T\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för boxbara (värde)typer, vilket exakt är vad de är.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) för att testa 'is'-operatorn. Ignorerad. |

### ReturnValue

Alltid sant

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const U\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för pekartyper optimerade för 'final'-klasser.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |
| U | Testad typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const U\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för pekartyper.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |
| U | Testad typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const WeakPtr\<U\>\&) method


Implementerar översättning av 'is'-operatorn. Specialisering för enum-typer kontra svaga pekare.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |
| U | Typ av det pekade objektet. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const WeakPtr\<U\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [WeakPtr](../../weakptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(int32_t) method


Implementerar översättning av 'is'-operatorn. Specialisering för heltalsliteral.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målt typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int32_t | heltalsliteral. |

### ReturnValue

Sant om 'is' returnerar sant, falskt annars.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
