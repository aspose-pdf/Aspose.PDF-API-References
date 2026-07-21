---
title: "Clase System::UriBuilder"
linktitle: "UriBuilder"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::UriBuilder. Proporciona métodos para construir y modificar identificadores de recursos universales (URIs). Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 7100
url: /es/cpp/system/uribuilder/
---
## UriBuilder class


Proporciona métodos para construir y modificar identificadores de recursos universales (URIs). Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class UriBuilder : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Scheme](./get_scheme/)() const | Devuelve el esquema del URI construido por el objeto actual. |
| [get_Uri](./get_uri/)() const | Devuelve el objeto [Uri](../uri/) construido por el objeto actual. |
| [set_Port](./set_port/)(int) | Establece el número de puerto del URI. |
| [set_Scheme](./set_scheme/)(const String\&) | Establece el esquema del URI construido por el objeto actual al valor especificado. |
| [ToString](./tostring/)() const override | Devuelve la representación en cadena del URI construido por el objeto actual. |
| [UriBuilder](./uribuilder/)(const String\&) | Construye un objeto [UriBuilder](./) que representa el URI especificado. |
| [UriBuilder](./uribuilder/)(const SharedPtr\<Uri\>\&) | Construye un objeto [UriBuilder](./) que representa el URI especificado. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
