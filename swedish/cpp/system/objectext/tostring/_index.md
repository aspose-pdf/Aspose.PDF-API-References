---
title: "System::ObjectExt::ToString‑metod"
linktitle: "ToString"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::ToString‑metod. Ersättning för C# ToString‑metoden för att fungera på vilken C++‑typ som helst i C++."
type: docs
weight: 1400
url: /sv/cpp/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const Nullable\<T\>\&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Nullable](../../nullable/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const Nullable\<T\>\& | [Nullable](../../nullable/) objekt att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Enum](../../enum/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) värde att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Smartpekare typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) värde att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Strukturtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Strukturvärde att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Skalärtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\&& | Skalärt värde att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Skalärtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\&& | Skalärt värde att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Smartpekare typ eller [ExceptionWrapper](../../exceptionwrapper/). |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\& | Smartpekare eller [ExceptionWrapper](../../exceptionwrapper/) att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Skalärtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\& | Skalärt värde att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Strukturtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\& | Strukturvärde att konvertera till sträng. |

### ReturnValue

[String](../../string/) representation of **obj**.

## Se även

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
