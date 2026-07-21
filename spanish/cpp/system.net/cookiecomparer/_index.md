---
title: "Clase System::Net::CookieComparer"
linktitle: "CookieComparer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::CookieComparer. Se utiliza para comparar las instancias de la clase Cookie. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.net/cookiecomparer/
---
## CookieComparer class


Se utiliza para comparar las instancias de la clase [Cookie](../cookie/). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class CookieComparer : public System::Collections::Generic::IComparer<System::SharedPtr<System::Net::Cookie>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Compare](./compare/)(args_type, args_type) const override | Compara los objetos especificados. |
| static [get_Instance](./get_instance/)() | Información RTTI. |
## Ver también

* Class [IComparer](../../system.collections.generic/icomparer/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
