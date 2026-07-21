---
title: "System::Net::Http::Headers::TransferCodingWithQualityHeaderValue clase"
linktitle: "TransferCodingWithQualityHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::TransferCodingWithQualityHeaderValue clase. Representa un valor con una calidad adicional del encabezado ''Accept-Encoding''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2500
url: /es/cpp/system.net.http.headers/transfercodingwithqualityheadervalue/
---
## TransferCodingWithQualityHeaderValue class


Representa un valor con una calidad adicional del encabezado 'Accept-Encoding'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class TransferCodingWithQualityHeaderValue : public System::Net::Http::Headers::TransferCodingHeaderValue
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Quality](./get_quality/)() | Información RTTI. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada en una instancia de la clase [TransferCodingWithQualityHeaderValue](./). |
| [set_Quality](./set_quality/)(Nullable\<double\>) | Establece el valor de calidad del encabezado 'Accept-Encoding'. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)() | Construye una nueva instancia. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)(String) | Construye una nueva instancia. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)(String, double) | Construye una nueva instancia. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<TransferCodingWithQualityHeaderValue\>\&) | Intenta convertir una cadena pasada en una instancia de la clase [TransferCodingWithQualityHeaderValue](./). |
## Ver también

* Class [TransferCodingHeaderValue](../transfercodingheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
