---
title: "System::Net::EndPoint clase"
linktitle: "EndPoint"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::EndPoint. La clase abstracta contiene una dirección de red. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.net/endpoint/
---
## EndPoint class


La clase abstracta contiene una dirección de red. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class EndPoint : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Create](./create/)(System::SharedPtr\<SocketAddress\>) | Cree una nueva instancia de la clase [EndPoint](./) usando la dirección de socket especificada. |
| virtual [get_AddressFamily](./get_addressfamily/)() | Información RTTI. |
| virtual [GetImpl](./getimpl/)() const | Devuelve un puntero a la implementación. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ImplPtr](./implptr/) | Un puntero a la implementación. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
