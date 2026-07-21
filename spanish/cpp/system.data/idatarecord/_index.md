---
title: "Clase System::Data::IDataRecord"
linktitle: "IDataRecord"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Data::IDataRecord. Interfaz para un registro con columnas. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1300
url: /es/cpp/system.data/idatarecord/
---
## IDataRecord class


Interfaz para un registro con columnas. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class IDataRecord : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_FieldCount](./get_fieldcount/)() | Información RTTI. |
| virtual [GetName](./getname/)(const int32_t) | Obtiene el nombre del campo en la posición especificada. |
| virtual [idx_get](./idx_get/)(const int32_t) | Obtiene el valor en el índice especificado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Data](../)
* Library [Aspose.PDF for C++](../../)
