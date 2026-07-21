---
title: "System::Data::Common::DbDataReader clase"
linktitle: "DbDataReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Data::Common::DbDataReader clase. API para recibir datos de la base de datos. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.data.common/dbdatareader/
---
## DbDataReader class


API para recibir datos de la base de datos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class DbDataReader : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Close](./close/)() | Cierra el canal de recuperación de datos. |
| virtual [idx_get](./idx_get/)(String) | Obtiene el elemento con nombre. |
| virtual [idx_get](./idx_get/)(int) | Obtiene el elemento por índice. |
| virtual [Read](./read/)() | Lee el siguiente registro de la base de datos. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Información RTTI. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
