---
title: "Clase System::Data::DataRow"
linktitle: "DataRow"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Data::DataRow. Fila en el conjunto de datos. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.data/datarow/
---
## DataRow class


Fila en el conjunto de datos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class DataRow : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Table](./get_table/)() | Obtiene la tabla a la que pertenece la fila. |
| [GetChildRows](./getchildrows/)(const System::SharedPtr\<System::Data::DataRelation\>\&) | Obtiene las filas que se consideran hijas a través de la relación especificada. |
| [idx_get](./idx_get/)(const int32_t) | Información RTTI. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Data](../)
* Library [Aspose.PDF for C++](../../)
