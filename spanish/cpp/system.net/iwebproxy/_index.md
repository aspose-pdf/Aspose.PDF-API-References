---
title: "System::Net::IWebProxy class"
linktitle: "IWebProxy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::IWebProxy. Esta interfaz se utiliza para la implementación del acceso a proxy de la clase WebRequest. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2700
url: /es/cpp/system.net/iwebproxy/
---
## IWebProxy class


Esta interfaz se utiliza para la implementación del acceso a proxy de la clase [WebRequest](../webrequest/). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class IWebProxy : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_Credentials](./get_credentials/)() | Información RTTI. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Devuelve el URI del proxy. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Devuelve un valor que indica si el proxy no debe usarse para el host especificado. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Establece credenciales para la autenticación en el servidor proxy. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
