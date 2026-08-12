---
title: "Clase System::IO::TextWriter"
linktitle: "TextWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::TextWriter. Clase base para clases que representan escritores que escriben secuencias de caracteres en diferentes destinos. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2700
url: /es/cpp/system.io/textwriter/
---
## TextWriter class


Clase base para clases que representan escritores que escriben secuencias de caracteres en diferentes destinos. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class TextWriter : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Close](./close/)() | Cierra el flujo y libera los recursos adquiridos. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| virtual [Flush](./flush/)() | Vuelca el contenido del búfer al flujo subyacente. |
| virtual [get_Encoding](./get_encoding/)() | Devuelve la codificación actualmente utilizada. |
| virtual [get_FormatProvider](./get_formatprovider/)() const | Devuelve el objeto [IFormatProvider](../../system/iformatprovider/) actualmente utilizado. |
| [get_FormatProvider](./get_formatprovider/)() | Devuelve el objeto [IFormatProvider](../../system/iformatprovider/) actualmente utilizado. |
| virtual [get_NewLine](./get_newline/)() const | Devuelve una cadena terminadora de línea. |
| [get_NewLine](./get_newline/)() | Devuelve una cadena terminadora de línea. |
| virtual [set_NewLine](./set_newline/)(const System::String\&) | Establece una cadena terminadora de línea. |
| virtual [Write](./write/)(const SharedPtr\<Object\>\&) | Escribe la representación en cadena del objeto especificado en el flujo. |
| virtual [Write](./write/)(bool) | Escribe la representación en cadena del valor booleano especificado en el flujo. |
| virtual [Write](./write/)(char_t) | Escribe el carácter especificado en el flujo. |
| virtual [Write](./write/)(Decimal) | Escribe la representación en cadena del objeto [Decimal](../../system/decimal/) especificado en el flujo. |
| virtual [Write](./write/)(double) | Escribe la representación en cadena del valor de punto flotante de doble precisión especificado en el flujo. |
| virtual [Write](./write/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado en el flujo. |
| virtual [Write](./write/)(int64_t) | Escribe la representación en cadena del valor entero de 64 bits especificado en el flujo. |
| virtual [Write](./write/)(float) | Escribe la representación en cadena del valor de punto flotante de precisión simple especificado en el flujo. |
| virtual [Write](./write/)(const String\&) | Escribe la cadena especificada en el flujo. |
| virtual [Write](./write/)(uint32_t) | Escribe la representación en cadena del valor entero sin signo de 32 bits especificado en el flujo. |
| virtual [Write](./write/)(uint64_t) | Escribe la representación en cadena del valor entero sin signo de 64 bits especificado en el flujo. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&) | Escribe todos los caracteres del arreglo especificado al flujo. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado al flujo. |
| virtual [Write](./write/)(const char_t *) | Escribe la c‑cadena especificada al flujo. |
| virtual [Write](./write/)(const TypeInfo\&) | Escribe la representación en cadena del objeto [TypeInfo](../../system/typeinfo/) especificado al flujo. |
| [Write](./write/)(const String\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato especificado al flujo. |
| virtual [WriteLine](./writeline/)() | Escribe los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) | Escribe la representación en cadena del objeto especificado seguida de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(bool) | Escribe la representación en cadena del valor booleano especificado seguida de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(char_t) | Escribe el carácter especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(Decimal) | Escribe la representación en cadena del objeto [Decimal](../../system/decimal/) especificado seguida de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(double) | Escribe la representación en cadena del valor de punto flotante de doble precisión especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(int64_t) | Escribe la representación en cadena del valor entero de 64 bits especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(float) | Escribe la representación en cadena del valor de punto flotante de precisión simple especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(const String\&) | Escribe la cadena especificada seguida de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(uint32_t) | Escribe la representación en cadena del valor entero sin signo de 32 bits especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(uint64_t) | Escribe la representación en cadena del valor entero sin signo de 64 bits especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) | Escribe todos los caracteres del arreglo especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(const char_t *) | Escribe la c‑cadena especificada seguida de los caracteres de terminación de línea al flujo. |
| virtual [WriteLine](./writeline/)(const TypeInfo\&) | Escribe la representación en cadena del objeto [TypeInfo](../../system/typeinfo/) especificado seguido de los caracteres de terminación de línea al flujo. |
| [WriteLine](./writeline/)(const String\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato especificado seguido de los caracteres de terminación de línea al flujo. |
| virtual [~TextWriter](./~textwriter/)() | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a esta clase. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
