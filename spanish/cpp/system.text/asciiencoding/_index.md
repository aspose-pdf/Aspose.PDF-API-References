---
title: "System::Text::ASCIIEncoding clase"
linktitle: "ASCIIEncoding"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::ASCIIEncoding clase. Representa la codificación ASCII. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.text/asciiencoding/
---
## ASCIIEncoding class


Representa la codificación ASCII. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ASCIIEncoding](./asciiencoding/)() | Constructor. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Obtiene el recuento máximo de bytes posible para almacenar una cadena con un número de caracteres conocido. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Obtenga la cantidad máxima de caracteres necesarios para decodificar un número especificado de bytes. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Valor predeterminado de la página de códigos. |
## Ver también

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
