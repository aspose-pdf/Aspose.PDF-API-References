---
title: "Clase System::Web::Services::WebServiceBindingAttribute"
linktitle: "WebServiceBindingAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Web::Services::WebServiceBindingAttribute. Se utiliza para declarar un enlace que define uno o más métodos del servicio Web XML. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.web.services/webservicebindingattribute/
---
## WebServiceBindingAttribute class


Se utiliza para declarar un enlace que define uno o más métodos del servicio XML [Web](../../system.web/). Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class WebServiceBindingAttribute : public System::Attribute
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ConformsTo](./get_conformsto/)() | Obtiene la especificación WSI. |
| [get_EmitConformanceClaims](./get_emitconformanceclaims/)() | Obtiene un valor que indica si el enlace emite afirmaciones de conformidad. |
| [get_Location](./get_location/)() | Información RTTI. |
| [get_Name](./get_name/)() | Obtiene el nombre del enlace. |
| [get_Namespace](./get_namespace/)() | Obtiene el espacio de nombres asociado al enlace. |
| [set_ConformsTo](./set_conformsto/)(System::SharedPtr\<WsiProfiles\>) | Establece la especificación WSI. |
| [set_EmitConformanceClaims](./set_emitconformanceclaims/)(bool) | Establece un valor que indica si el enlace emite afirmaciones de conformidad. |
| [set_Location](./set_location/)(String) | Establece la ubicación donde se define el enlace. |
| [set_Name](./set_name/)(String) | Establece el nombre del binding. |
| [set_Namespace](./set_namespace/)(String) | Establece el espacio de nombres asociado al binding. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)() | Construye una nueva instancia. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String) | Construye una nueva instancia. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String, String) | Construye una nueva instancia. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String, String, String) | Construye una nueva instancia. |
## Ver también

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services](../)
* Library [Aspose.PDF for C++](../../)
