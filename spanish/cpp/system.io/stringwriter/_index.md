---
title: "Clase System::IO::StringWriter"
linktitle: "StringWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::StringWriter. Implementa un TextWriter que escribe información en una cadena. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2500
url: /es/cpp/system.io/stringwriter/
---
## StringWriter class


Implementa un [TextWriter](../textwriter/) que escribe información en una cadena. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | Devuelve la codificación actualmente utilizada. |
| virtual [GetStringBuilder](./getstringbuilder/)() | Devuelve el StringBuilder actualmente usado. |
| [StringWriter](./stringwriter/)(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) | Construye una nueva instancia de [StringWriter](./) usando el StringBuilder especificado y [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)(const System::SharedPtr\<Text::StringBuilder\>\&) | Construye una nueva instancia de [StringWriter](./) usando el StringBuilder especificado y [IFormatProvider](../../system/iformatprovider/) de la cultura actual. |
| [StringWriter](./stringwriter/)(const IFormatProviderPtr\&) | Construye una nueva instancia de [StringWriter](./) usando el [IFormatProvider](../../system/iformatprovider/) especificado. |
| [StringWriter](./stringwriter/)() | Construye una nueva instancia de [StringWriter](./) usando [IFormatProvider](../../system/iformatprovider/) de la cultura actual. |
| [ToString](./tostring/)() const override | Devuelve la cadena subyacente. |
| [Write](./write/)(char_t) override | Escribe el carácter especificado en el flujo. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de caracteres del arreglo de caracteres especificado al flujo. |
| [Write](./write/)(const String\&) override | Escribe la cadena especificada en el flujo. |
## Ver también

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
