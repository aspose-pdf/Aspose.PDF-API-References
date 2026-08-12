---
title: "System::IO::StreamWriter::Write método"
linktitle: "Write"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::StreamWriter::Write método. Escribe el carácter especificado al flujo en C++."
type: docs
weight: 1000
url: /es/cpp/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) method


Escribe el carácter especificado en el flujo.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | char_t | El carácter a escribir |

## Ver también

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const ArrayPtr\<char_t\>\&) method


Escribe todos los caracteres del arreglo especificado al flujo.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<char_t\>\& | La matriz que contiene los caracteres a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado al flujo.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<char_t\>\& | La matriz que contiene los caracteres a escribir |
| índice | int32_t | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de caracteres en el subrango a escribir; -1 indica que el subrango termina donde termina la matriz **buffer** |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const char_t *) method


Escribe la c‑cadena especificada al flujo.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const char_t * | La c-string a escribir |

## Ver también

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const SharedPtr\<Object\>\&) method


Escribe la representación en cadena del objeto especificado en el flujo.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SharedPtr\<Object\>\& | El objeto a escribir |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const String\&) method


Escribe la cadena especificada en el flujo.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const String\& | La cadena a escribir |

## Ver también

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const System::SharedPtr\<T\>\&) method


Escribe la representación en cadena del objeto especificado en el flujo.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const System::SharedPtr\<T\>\& | El objeto a escribir |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
