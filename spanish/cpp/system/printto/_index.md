---
title: "System::PrintTo método"
linktitle: "PrintTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::PrintTo método. Escribe el valor representado por el objeto especificado en el flujo de salida especificado en C++."
type: docs
weight: 36100
url: /es/cpp/system/printto/
---
## System::PrintTo(const Decimal\&, ::std::ostream *) method


Escribe el valor representado por el objeto especificado en el flujo de salida especificado.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | const Decimal\& | El objeto [Decimal](../decimal/) a imprimir en el flujo |
| os | ::std::ostream * | El flujo al que imprimir el objeto especificado |

## Ver también

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Details_Exception\&, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## Ver también

* Class [ExceptionWrapper](../exceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Guid\&, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## Ver también

* Class [Guid](../guid/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Nullable\<T\>\&, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## Ver también

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const System::Object\&, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const System::String\&, std::ostream *) method


Imprime una cadena al ostream. Usado mayormente para depuración.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const System::String\& | para imprimir. |
| os | std::ostream * | ostream objetivo. |

## Ver también

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Ver también

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(DateTime, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## Ver también

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(DateTimeOffset, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## Ver también

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(TimeSpan, std::ostream *) method


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## Ver también

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
