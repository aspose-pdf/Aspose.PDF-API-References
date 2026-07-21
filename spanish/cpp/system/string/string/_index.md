---
title: "Constructor System::String::String"
linktitle: "String"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::String::String. Constructor predeterminado. Crea un objeto cadena que se considera nulo en C++."
type: docs
weight: 100
url: /es/cpp/system/string/string/
---
## String::String() constructor


Constructor predeterminado. Crea un objeto de cadena que se considera nulo.

```cpp
System::String::String()
```

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(codeporting_icu::UnicodeString\&&) constructor


Constructor de movimiento.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString para envolver en [String](../). |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&) constructor


Convierte todo el arreglo de caracteres a cadena.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | [Array](../../array/) para convertir a cadena. |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&, int, int) constructor


Convierte un subrango del arreglo de caracteres a cadena. Si los parámetros están fuera de los límites del arreglo, se construye una cadena vacía.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | Arreglo de caracteres. |
| desplazamiento | int | Índice de inicio del subarreglo. |
| len | int | Longitud del subarreglo. |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char *, int) constructor


Construye una cadena a partir de un puntero a cadena de caracteres y una longitud explícita.

```cpp
System::String::String(const char *str, int length)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char * | [String](../) puntero a los datos UTF8, puede ser literal o arreglo. |
| longitud | int | Longitud explícita de la cadena |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t *, int) constructor


Construye una cadena a partir de un puntero a cadena de caracteres y una longitud explícita.

```cpp
System::String::String(const char16_t *str, int length)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char16_t * | [String](../) puntero, puede ser literal o arreglo. |
| longitud | int | Longitud explícita de la cadena |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t *, int, int) constructor


Construye una cadena a partir de un puntero a cadena de caracteres desde la posición inicial usando la longitud.

```cpp
System::String::String(const char16_t *str, int start, int length)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char16_t * | [String](../) puntero, puede ser literal o arreglo. |
| inicio | int | Posición inicial. |
| length | int | Longitud de [String](../). |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const char16_t, int) constructor


Constructor de relleno.

```cpp
System::String::String(const char16_t ch, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ch | const char16_t | Carácter de relleno. |
| count | int | Longitud objetivo. |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const codeporting_icu::UnicodeString\&) constructor


Envuelve UnicodeString en [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString para envolver en [String](../). |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const ReadOnlySpan\<char16_t\>\&) constructor


Inicializa una nueva instancia de la clase [System.String](../) con los caracteres Unicode indicados en el span de solo lectura especificado.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const ReadOnlySpan\<char16_t\>\& | Un span de solo lectura de caracteres Unicode. |

## Ver también

* Class [ReadOnlySpan](../../readonlyspan/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::string\&) constructor


Crea [String](../) a partir de una cadena std::string presentada en formato UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| utf8str | const std::string\& | Cadena std::string para convertir en [String](../). |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::u16string\&) constructor


Crea [String](../) a partir de una cadena utf16.

```cpp
System::String::String(const std::u16string &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const std::u16string\& | Cadena Utf16 para convertir en [String](../). |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::u32string\&) constructor


Crea [String](../) a partir de una cadena std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| u32str | const std::u32string\& | Cadena std::u32string para convertir en [String](../). |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const std::wstring\&) constructor


Crea [String](../) a partir de una widestring.

```cpp
System::String::String(const std::wstring &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const std::wstring\& | Widestring para convertir en [String](../). |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const String\&) constructor


Constructor de copia.

```cpp
System::String::String(const String &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | [String](../) para copiar. |

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) constructor


Construye una cadena a partir de un puntero a cadena de caracteres. Trata la cadena apuntada como terminada en nulo en UTF‑8 y calcula la longitud de la cadena objetivo basándose en el carácter nulo.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const T\& | Puntero a cadena de caracteres. |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) constructor


Construye una cadena a partir de un puntero a cadena de caracteres. Trata la cadena apuntada como terminada en nulo y calcula la longitud de la cadena objetivo basándose en el carácter nulo.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const T\& | Puntero a cadena de caracteres. |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) constructor


Construye una cadena a partir de un puntero a cadena de caracteres anchos. Trata la cadena apuntada como terminada en nulo y calcula la longitud de la cadena objetivo basándose en el carácter nulo. La conversión desde wchar_t es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const T\& | Puntero a cadena de caracteres. |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructor


Constructor nullptr. Declarado como plantilla para resolver prioridades con otros constructores plantilla.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```


| Parámetro | Descripción |
| --- | --- |
| T | Debe ser nullptr_t |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const T\& | nullptr |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const wchar_t *, int) constructor


Construye una cadena a partir de un puntero a cadena de caracteres anchos y una longitud explícita. La conversión desde wchar_t es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas.

```cpp
System::String::String(const wchar_t *str, int length)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const wchar_t * | [String](../) puntero, puede ser literal o arreglo. |
| longitud | int | Longitud explícita de la cadena |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(const wchar_t, int) constructor


Constructor de relleno. La conversión desde wchar_t es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas.

```cpp
System::String::String(const wchar_t ch, int count=1)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ch | const wchar_t | Carácter de relleno. |
| count | int | Longitud objetivo. |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(String\&&) constructor


Constructor de movimiento.

```cpp
System::String::String(String &&str) noexcept
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | String\&& | [String](../) para mover datos desde. |

## Ver también

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) constructor


Construye una cadena a partir de un literal de cadena. Considera el literal como una cadena terminada en nulo en UTF‑8 y calcula la longitud de la cadena objetivo según el tamaño del literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T\& | [String](../) puntero literal. |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) constructor


Construye una cadena a partir de un literal de cadena. Considera el literal como una cadena terminada en nulo y calcula la longitud de la cadena objetivo en función del tamaño del literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T\& | [String](../) puntero literal. |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) constructor


Construye una cadena a partir de un literal widestring. Considera el literal como una cadena terminada en nulo y calcula la longitud de la cadena objetivo según el tamaño del literal. La conversión desde wchar_t es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T\& | [String](../) puntero literal. |

## Ver también

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
