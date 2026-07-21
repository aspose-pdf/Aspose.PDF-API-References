---
title: "Clase System::Net::Http::Headers::ObjectCollection"
linktitle: "ObjectCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::ObjectCollection. Representa la colección de los objetos en C++."
type: docs
weight: 1600
url: /es/cpp/system.net.http.headers/objectcollection/
---
## ObjectCollection class


Representa la colección de los objetos. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename T>class ObjectCollection : public System::Collections::ObjectModel::Collection<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de objeto. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [ObjectCollection](./objectcollection/)() | Información RTTI. |
| [ObjectCollection](./objectcollection/)(Action\<T\>) | Construye una nueva instancia. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Establece el n‑ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |

## Ver también

* Class [Collection](../../system.collections.objectmodel/collection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
