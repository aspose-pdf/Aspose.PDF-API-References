---
title: "Clase System::String"
linktitle: "String"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::String. Clase de cadena utilizada en toda la biblioteca. Es un sustituto de System.String de C# al traducir código. Por razones de optimización, no se considera una subclase de Object. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 6100
url: /es/cpp/system/string/
---
## String class


[String](./) class used across the library. Is a substitute for C# [System.String](./) when translating code. For optimization reasons, isn't considered an [Object](../object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class String
```

## Métodos

| Método | Descripción |
| --- | --- |
| [begin](./begin/)() const | Devuelve un puntero al comienzo del búfer real de la cadena. Nunca reasigna nada. No garantiza que el búfer esté terminado en nulo. |
| [Clone](./clone/)() const | Crea una copia de la cadena actual. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, bool) | Less-equal-greater-compara dos subcadenas. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) | Less-equal-greater-compara dos subcadenas. |
| static [Compare](./compare/)(const String\&, const String\&, System::StringComparison) | Less-equal-greater-compara dos cadenas. |
| static [Compare](./compare/)(const String\&, int, const String\&, int, int, System::StringComparison) | Less-equal-greater-compara dos cadenas. |
| static [Compare](./compare/)(const String\&, const String\&, bool) | Less-equal-greater-compara dos cadenas. |
| static [Compare](./compare/)(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) | Less-equal-greater-compara dos cadenas. |
| static [CompareOrdinal](./compareordinal/)(const String\&, const String\&) | Less-equal-greater-compara dos cadenas usando el modo ordinal. |
| static [CompareOrdinal](./compareordinal/)(const String\&, int, const String\&, int, int) | Less-equal-greater-compara dos cadenas usando el modo ordinal. |
| [CompareTo](./compareto/)(const String\&) const | Compara dos cadenas en estilo 'less-equals-more'. Usa la cultura actual. |
| static [Concat](./concat/)(const ArrayPtr\<String\>\&) | Concatena cadenas. |
| static [Concat](./concat/)(const String\&, const String\&) | Concatena cadenas. |
| static [Concat](./concat/)(const String\&, const String\&, const String\&) | Concatena cadenas. |
| static [Concat](./concat/)(const String\&, const String\&, const String\&, const String\&) | Concatena cadenas. |
| [Contains](./contains/)(const String\&) const | Comprueba si str es una subcadena de la cadena actual. |
| [Contains](./contains/)(char16_t) const | Comprueba si la cadena contiene el carácter dado. |
| static [Copy](./copy/)(const String\&) | Crea una copia de la cadena. |
| [CopyTo](./copyto/)(int, const ArrayPtr\<char_t\>\&, int, int) const | Copia los caracteres de la cadena en elementos de un arreglo existente. No se realiza redimensionamiento. |
| [end](./end/)() const | Devuelve un puntero al final del búfer real de la cadena. Nunca reasigna nada. No garantiza que el búfer esté terminado en nulo. |
| [EndsWith](./endswith/)(const String\&) const | Comprueba si la cadena termina con la subcadena especificada. |
| [EndsWith](./endswith/)(const String\&, System::StringComparison) const | Comprueba si la cadena termina con la subcadena especificada. |
| [EndsWith](./endswith/)(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Comprueba si la cadena termina con la subcadena especificada. |
| [Equals](./equals/)(const String\&, System::StringComparison) const | [String](./) comparación de igualdad. Se admiten varios modos proporcionados por la enumeración [StringComparison](../stringcomparison/). |
| [Equals](./equals/)(const String\&) const | [String](./) comparación de igualdad. Usa el modo de comparación [System::StringComparison::Ordinal](../stringcomparison/). |
| static [Equals](./equals/)(const String\&, const String\&) | Equal-compara dos cadenas usando el modo de comparación Ordial. |
| static [Equals](./equals/)(const String\&, const String\&, System::StringComparison) | Equal-compara dos cadenas. |
| [FastToAscii](./fasttoascii/)(char, int) const | Intenta convertir un [String](./) a una cadena ASCII. |
| static [Format](./format/)(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) | Formatea la cadena al estilo C#. |
| static [Format](./format/)(std::nullptr_t, const String\&, const Args\&...) | Formatea la cadena al estilo C#. |
| static [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formatea la cadena al estilo C#. |
| static [Format](./format/)(const String\&, const Args\&...) | Formatea la cadena al estilo C#. |
| static [Format](./format/)(const String\&, const System::ArrayPtr\<T\>\&) | Formatea la cadena al estilo C#. |
| static [FromAscii](./fromascii/)(const char *) | Crea [String](./) a partir de una cadena ASCII. |
| static [FromAscii](./fromascii/)(const char *, int) | Crea [String](./) a partir de una cadena ASCII. |
| static [FromAscii](./fromascii/)(const std::string\&) | Crea [String](./) a partir de una cadena ASCII. |
| static [FromUtf16](./fromutf16/)(const std::u16string\&) | Crea [String](./) a partir de una cadena utf16. |
| static [FromUtf32](./fromutf32/)(const uint32_t *, int32_t) | Crea [String](./) a partir de una cadena utf32. |
| static [FromUtf8](./fromutf8/)(const char *) | Crea [String](./) a partir de una cadena utf8. |
| static [FromUtf8](./fromutf8/)(const char *, int) | Crea [String](./) a partir de una cadena utf8. |
| static [FromUtf8](./fromutf8/)(const uint8_t *) | Crea [String](./) a partir de una cadena utf8. |
| static [FromUtf8](./fromutf8/)(const std::string\&) | Crea [String](./) a partir de una cadena utf8. |
| static [FromWCS](./fromwcs/)(const std::wstring\&) | Crea [String](./) a partir de widestring. |
| [get_Length](./get_length/)() const | Obtiene la longitud de la cadena. |
| [GetHashCode](./gethashcode/)() const | Genera hash de la cadena contenida. Implementado en ICU, no coincide con los hashes en C#. |
| [IndexOf](./indexof/)(const String\&, System::StringComparison) const | Búsqueda hacia adelante de subcadena. |
| [IndexOf](./indexof/)(char_t, int) const | Búsqueda hacia adelante de carácter. |
| [IndexOf](./indexof/)(char_t, int, int) const | Búsqueda hacia adelante de carácter en subcadena. |
| [IndexOf](./indexof/)(const String\&, int) const | Búsqueda hacia adelante de subcadena. |
| [IndexOf](./indexof/)(const String\&, int, System::StringComparison) const | Búsqueda hacia adelante de subcadena. |
| [IndexOf](./indexof/)(const String\&, int, int, System::StringComparison) const | Búsqueda hacia adelante de subcadena. |
| [IndexOf](./indexof/)(const String\&, int, int) const | Búsqueda hacia adelante de subcadena. |
| [IndexOfAny](./indexofany/)(char_t, int) const | Búsqueda hacia adelante de carácter. |
| [IndexOfAny](./indexofany/)(const String\&, int) const | Por consiguiente busca todos los caracteres de str en esto. Si se encuentra el primer carácter, se devuelve su posición; de lo contrario busca el segundo y así sucesivamente. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&) const | Busca cualquiera de los caracteres pasados en toda la cadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&, int32_t) const | Busca cualquiera de los caracteres pasados en la subcadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo. |
| [IndexOfAny](./indexofany/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const | Busca cualquiera de los caracteres pasados en la subcadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo. |
| [Insert](./insert/)(int, const String\&) const | Inserta una subcadena en la posición especificada. |
| [Is](./is/)(const System::TypeInfo\&) const | Comprueba si el objeto string es del tipo especificado por [TypeInfo](../typeinfo/) pasado. |
| [IsAsciiString](./isasciistring/)() const | Indica si un [String](./) contiene solo símbolos ASCII. |
| [IsEmpty](./isempty/)() const | Comprueba si la cadena es no nula y está vacía. |
| [IsNormalized](./isnormalized/)(System::Text::NormalizationForm) const | Comprueba si la cadena Unicode está normalizada usando la forma de normalización especificada. |
| [IsNull](./isnull/)() const | Comprueba si la cadena se considera nula. [String](./) es nula solo si se construye mediante el constructor [String()](./string/), se mueve, copia o asigna desde una cadena nula o se llamó al método [reset()](./reset/). |
| [IsNullOrEmpty](./isnullorempty/)() const | Comprueba si la cadena está vacía o se considera nula. |
| static [IsNullOrEmpty](./isnullorempty/)(const String\&) | Comprueba si la cadena pasada es nula o está vacía. |
| static [IsNullOrWhiteSpace](./isnullorwhitespace/)(const String\&) | Indica si una cadena especificada es nula, está vacía o consta solo de caracteres de espacio en blanco. |
| static [Join](./join/)(const String\&, const ArrayPtr\<String\>\&, int, int) | Une el arreglo usando una cadena como separador. |
| static [Join](./join/)(const String\&, const System::Details::ArrayView\<String\>\&, int, int) | Une el arreglo usando una cadena como separador. |
| static [Join](./join/)(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) | Une el arreglo usando una cadena como separador. |
| static [Join](./join/)(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) | Une el arreglo usando una cadena como separador. |
| [LastIndexOf](./lastindexof/)(const String\&, int) const | Búsqueda hacia atrás de subcadena. |
| [LastIndexOf](./lastindexof/)(const String\&, System::StringComparison) const | Búsqueda hacia atrás de subcadena. |
| [LastIndexOf](./lastindexof/)(const String\&, int, System::StringComparison) const | Búsqueda hacia atrás de subcadena. |
| [LastIndexOf](./lastindexof/)(const String\&, int, int, StringComparison) const | Búsqueda hacia atrás de subcadena. |
| [LastIndexOf](./lastindexof/)(char_t) const | Búsqueda hacia atrás de carácter. |
| [LastIndexOf](./lastindexof/)(char_t, int32_t) const | Búsqueda hacia atrás de carácter. |
| [LastIndexOf](./lastindexof/)(char_t, int32_t, int32_t) const | Búsqueda hacia atrás de carácter. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&) const | Busca cualquiera de los caracteres pasados en toda la cadena hacia atrás. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&, int32_t) const | Busca cualquiera de los caracteres pasados en la subcadena hacia atrás. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada. |
| [LastIndexOfAny](./lastindexofany/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const | Busca cualquiera de los caracteres pasados en la subcadena hacia atrás. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada. |
| [Normalize](./normalize/)(System::Text::NormalizationForm) const | Normaliza la cadena Unicode usando la forma de normalización especificada. |
| [operator ReadOnlySpan< char16_t >](./operatorreadonlyspan_char16_t_/)() const | Convierte la cadena a un span de solo lectura. |
| [operator!=](./operator!=/)(const String\&) const | Operador de comparación de desigualdad. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Comprueba si la cadena no es nula. Aplica la misma lógica que la llamada a [IsNull()](./isnull/). |
| [operator+](./operator+/)(const String\&) const | Operador de concatenación de [String](./). |
| [operator+](./operator+/)(const T\&) const | Concatenación de [String](./) con literal de cadena o puntero a cadena de caracteres. |
| [operator+](./operator+/)(char_t) const | Añade un carácter al final de la cadena. |
| [operator+](./operator+/)(int) const | Agrega la representación en cadena del valor entero al final de la cadena. |
| [operator+](./operator+/)(uint32_t) const | Agrega la representación en cadena del valor entero sin signo al final de la cadena. |
| [operator+](./operator+/)(double) const | Agrega la representación en cadena del valor de punto flotante al final de la cadena. |
| [operator+](./operator+/)(int64_t) const | Agrega la representación en cadena del valor entero al final de la cadena. |
| [operator+](./operator+/)(const T\&) const | Agrega la representación en cadena del objeto de tipo referencia al final de la cadena. |
| [operator+](./operator+/)(const T\&) const | Agrega la representación en cadena del objeto de tipo referencia al final de la cadena. |
| [operator+](./operator+/)(T) const | Agrega la representación en cadena del valor booleano al final de la cadena. |
| [operator+=](./operator+=/)(char_t) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(const String\&) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(double) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(uint8_t) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(int16_t) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(uint16_t) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(int32_t) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(uint32_t) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(int64_t) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(uint64_t) | Operador de asignación de concatenación. |
| [operator+=](./operator+=/)(T) | Operador de asignación de concatenación. |
| [operator<](./operator_/)(const String\&) const | Compara ordenadamente cadenas. |
| [operator=](./operator=/)(const String\&) | Operador de asignación. |
| [operator=](./operator=/)(String\&&) | Operador de asignación por movimiento. |
| [operator==](./operator==/)(const String\&) const | Operador de comparación de igualdad. |
| [operator==](./operator==/)(std::nullptr_t) const | Comprueba si la cadena es nula. Aplica la misma lógica que la llamada [IsNull()](./isnull/). |
| [operator>](./operator_/)(const String\&) const | Compara ordenadamente cadenas. |
| [operator[]](./operator[]/)(int) const | Obtiene el carácter en la posición especificada. |
| [PadLeft](./padleft/)(int, char_t) const | Agrega relleno a la izquierda de la cadena original. |
| [PadRight](./padright/)(int, char_t) const | Agrega relleno a la derecha de la cadena original. |
| [rbegin](./rbegin/)() const | Devuelve un iterador inverso al último carácter (si lo hay) del búfer de cadena real. |
| [Remove](./remove/)(int32_t, int32_t) const | Extrae todo excepto la subcadena de la cadena actual. |
| [rend](./rend/)() const | Devuelve un iterador inverso al carácter anterior al primero (si lo hay) del búfer de cadena real. |
| [Replace](./replace/)(char_t, char_t) const | Reemplaza todas las apariciones del carácter en la cadena. |
| [Replace](./replace/)(const String\&, const String\&) const | Reemplaza todas las apariciones de la búsqueda en esta cadena. |
| [reset](./reset/)() | Establece la cadena a nula. Es análogo a 'string_variable_name = null' en C#. |
| [SetCharAt](./setcharat/)(int, char_t) | Establece el carácter en la posición especificada. |
| [Split](./split/)(char_t, StringSplitOptions) const | Divide la cadena por carácter. |
| [Split](./split/)(char_t, int32_t, StringSplitOptions) const | Divide la cadena por carácter. |
| [Split](./split/)(char_t, char_t, StringSplitOptions) const | Divide la cadena por uno de dos caracteres. |
| [Split](./split/)(const ArrayPtr\<char_t\>\&, StringSplitOptions) const | Divide la cadena por uno de los caracteres especificados. |
| [Split](./split/)(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const | Divide la cadena por uno de los caracteres especificados. |
| [Split](./split/)(const String\&, StringSplitOptions) const | Divide la cadena por subcadena. |
| [Split](./split/)(const String\&, int, StringSplitOptions) const | Divide la cadena por subcadena. |
| [Split](./split/)(const ArrayPtr\<String\>\&, StringSplitOptions) const | Divide la cadena por subcadena. |
| [Split](./split/)(const ArrayPtr\<String\>\&, int, StringSplitOptions) const | Divide la cadena por subcadena. Actualmente, solo admite una matriz de separadores de cero o un elemento. |
| [StartsWith](./startswith/)(const String\&) const | Comprueba si la cadena comienza con la subcadena especificada. |
| [StartsWith](./startswith/)(const String\&, System::StringComparison) const | Comprueba si la cadena comienza con la subcadena especificada. |
| [StartsWith](./startswith/)(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Comprueba si la cadena comienza con la subcadena especificada. |
| [String](./string/)() | Constructor predeterminado. Crea un objeto de cadena que se considera nulo. |
| [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) | Construye una cadena a partir de un literal de cadena. Considera el literal como una cadena terminada en nulo y calcula la longitud de la cadena objetivo en función del tamaño del literal. |
| [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) | Construye una cadena a partir de un puntero a cadena de caracteres. Trata la cadena apuntada como terminada en nulo y calcula la longitud de la cadena objetivo basándose en el carácter nulo. |
| explicit [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) | Construye una cadena a partir de un literal de cadena. Considera el literal como una cadena terminada en nulo en UTF‑8 y calcula la longitud de la cadena objetivo según el tamaño del literal. |
| explicit [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) | Construye una cadena a partir de un puntero a cadena de caracteres. Trata la cadena apuntada como terminada en nulo en UTF‑8 y calcula la longitud de la cadena objetivo basándose en el carácter nulo. |
| [String](./string/)(const char16_t *, int) | Construye una cadena a partir de un puntero a cadena de caracteres y una longitud explícita. |
| [String](./string/)(const ReadOnlySpan\<char16_t\>\&) | Inicializa una nueva instancia de la clase [System.String](./) con los caracteres Unicode indicados en el span de solo lectura especificado. |
| [String](./string/)(const char *, int) | Construye una cadena a partir de un puntero a cadena de caracteres y una longitud explícita. |
| [String](./string/)(const char16_t *, int, int) | Construye una cadena a partir de un puntero a cadena de caracteres desde la posición inicial usando la longitud. |
| explicit [String](./string/)(const char16_t, int) | Constructor de relleno. |
| [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Constructor nullptr. Declarado como plantilla para resolver prioridades con otros constructores plantilla. |
| explicit [String](./string/)(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) | Construye una cadena a partir de un literal widestring. Considera el literal como una cadena terminada en nulo y calcula la longitud de la cadena objetivo según el tamaño del literal. La conversión desde wchar_t es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas. |
| explicit [String](./string/)(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) | Construye una cadena a partir de un puntero a cadena de caracteres anchos. Trata la cadena apuntada como terminada en nulo y calcula la longitud de la cadena objetivo basándose en el carácter nulo. La conversión desde wchar_t es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas. |
| explicit [String](./string/)(const wchar_t *, int) | Construye una cadena a partir de un puntero a cadena de caracteres anchos y una longitud explícita. La conversión desde wchar_t es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas. |
| explicit [String](./string/)(const wchar_t, int) | Constructor de relleno. La conversión desde wchar_t es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas. |
| [String](./string/)(const String\&) | Constructor de copia. |
| [String](./string/)(String\&&) | Constructor de movimiento. |
| [String](./string/)(const ArrayPtr\<char16_t\>\&) | Convierte todo el arreglo de caracteres a cadena. |
| [String](./string/)(const ArrayPtr\<char16_t\>\&, int, int) | Convierte un subrango del arreglo de caracteres a cadena. Si los parámetros están fuera de los límites del arreglo, se construye una cadena vacía. |
| explicit [String](./string/)(const codeporting_icu::UnicodeString\&) | Envuelve UnicodeString en [String](./). |
| explicit [String](./string/)(codeporting_icu::UnicodeString\&&) | Constructor de movimiento. |
| explicit [String](./string/)(const std::wstring\&) | Crea [String](./) a partir de widestring. |
| explicit [String](./string/)(const std::u16string\&) | Crea [String](./) a partir de una cadena utf16. |
| explicit [String](./string/)(const std::string\&) | Crea [String](./) a partir de una cadena std::string presentada en formato UTF‑8. |
| explicit [String](./string/)(const std::u32string\&) | Crea [String](./) a partir de una cadena std::u32string. |
| [Substring](./substring/)(int32_t) const | Extrae una subcadena. |
| [Substring](./substring/)(int32_t, int32_t) const | Extrae una subcadena. |
| [ToAsciiString](./toasciistring/)() const | Convierte la cadena a std::string. Utiliza codificación ASCII. |
| [ToByteArray](./tobytearray/)(int32_t, int32_t, bool) const | Convierte la cadena o subcadena a un arreglo de bytes. |
| [ToCharArray](./tochararray/)(int32_t, int32_t) const | Convierte la cadena o subcadena a un arreglo de caracteres. |
| [ToLower](./tolower/)() const | Convierte todos los caracteres de la cadena a minúsculas. |
| [ToLower](./tolower/)(const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Convierte todos los caracteres de la cadena a minúsculas usando una cultura específica. |
| [ToLowerInvariant](./tolowerinvariant/)() const | Convierte todos los caracteres de la cadena a minúsculas usando la cultura invariante. |
| [ToString](./tostring/)() const | Wrapper para manejar la clase [String](./) en contextos donde se llama a [ToString()](./tostring/) sobre objetos de tipo valor. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Wrapper para manejar la clase [String](./) en contextos donde se llama a [ToString()](./tostring/) sobre objetos de tipo valor. |
| [ToU16Str](./tou16str/)() const | Convierte la cadena a std::u16string. |
| [ToU32Str](./tou32str/)() const | Convierte la cadena a std::u32string. |
| [ToUpper](./toupper/)() const | Convierte todos los caracteres de la cadena a mayúsculas. |
| [ToUpper](./toupper/)(const SharedPtr\<System::Globalization::CultureInfo\>\&) const | Convierte todos los caracteres de la cadena a mayúsculas usando una cultura específica. |
| [ToUpperInvariant](./toupperinvariant/)() const | Convierte todos los caracteres de la cadena a mayúsculas usando la cultura invariante. |
| [ToUtf8String](./toutf8string/)() const | Convierte la cadena a std::string. Utiliza codificación UTF-8. |
| [ToWCS](./towcs/)() const | Convierte la cadena a std::wstring. |
| [Trim](./trim/)() const | Elimina todos los caracteres de espacio en blanco tanto del inicio como del final de la cadena. |
| [Trim](./trim/)(char_t) const | Elimina todas las ocurrencias del carácter pasado tanto del inicio como del final de la cadena. |
| [Trim](./trim/)(const String\&) const | Elimina todas las ocurrencias de los caracteres pasados tanto del inicio como del final de la cadena. |
| [Trim](./trim/)(const ArrayPtr\<char_t\>\&) const | Elimina todas las ocurrencias de los caracteres pasados tanto del inicio como del final de la cadena. |
| [TrimEnd](./trimend/)() const | Elimina todos los caracteres de espacio en blanco del final de la cadena. |
| [TrimEnd](./trimend/)(char_t) const | Elimina todas las ocurrencias del carácter pasado del final de la cadena. |
| [TrimEnd](./trimend/)(const String\&) const | Elimina todas las ocurrencias de los caracteres pasados del final de la cadena. |
| [TrimEnd](./trimend/)(const ArrayPtr\<char_t\>\&) const | Elimina todas las ocurrencias de los caracteres pasados del final de la cadena. |
| [TrimStart](./trimstart/)() const | Elimina todos los caracteres de espacio en blanco del inicio de la cadena. |
| [TrimStart](./trimstart/)(char_t) const | Elimina todas las ocurrencias del carácter pasado del inicio de la cadena. |
| [TrimStart](./trimstart/)(const String\&) const | Elimina todas las ocurrencias de los caracteres pasados del inicio de la cadena. |
| [TrimStart](./trimstart/)(const ArrayPtr\<char_t\>\&) const | Elimina todas las ocurrencias de los caracteres pasados del inicio de la cadena. |
| [u_str](./u_str/)() const | Devuelve un búfer nulo terminado al estilo ICU. Puede volver a asignar la cadena. |
| [~String](./~string/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Cadena vacía. |
| static [Null](./null/) | Cadena nula. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
## Observaciones



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Construye una cadena a partir del arreglo de caracteres y la imprime.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Construye una cadena a partir del arreglo de bytes y la imprime.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Recorta la cadena siguiente y imprímela.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Imprime el número de palabras en el .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
This code example produces the following output:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
