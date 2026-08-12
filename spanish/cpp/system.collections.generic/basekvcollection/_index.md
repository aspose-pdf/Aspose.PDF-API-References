---
title: "Clase System::Collections::Generic::BaseKVCollection"
linktitle: "BaseKVCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::BaseKVCollection. Contiene código común para colecciones de claves o valores. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.collections.generic/basekvcollection/
---
## BaseKVCollection class


Contiene código común para colecciones de claves o valores. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename Dict,typename KV>class BaseKVCollection : public System::Collections::Generic::IKVCollection<KV>
```


| Parámetro | Descripción |
| --- | --- |
| Dict | [Dictionary](../dictionary/) tipo. |
| KV | Tipo de clave o valor, según sea la interfaz utilizada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [BaseKVCollection](./basekvcollection/)(const typename Dict::Ptr\&) | Crea la colección. |
| [CopyTo](./copyto/)(ArrayPtr\<KV\>, int) override | Copia datos a los elementos existentes del arreglo. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Permite la compilación, pero en realidad no hace nada ya que esta estructura no posee datos. |

## Ver también

* Class [IKVCollection](../ikvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
