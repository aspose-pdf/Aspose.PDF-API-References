---
title: "Clase System::Data::Common::DbCommand"
linktitle: "DbCommand"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Data::Common::DbCommand. Comando de base de datos. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y utilice ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.data.common/dbcommand/
---
## DbCommand class


Comando de base de datos. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice ese puntero para pasarlo a funciones como argumento.

```cpp
class DbCommand : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [ExecuteNonQuery](./executenonquery/)() | Ejecuta un comando que no es de consulta. |
| virtual [ExecuteReader](./executereader/)() | Ejecuta el comando de consulta. |
| virtual [get_CommandText](./get_commandtext/)() const | Información RTTI. |
| virtual [get_Connection](./get_connection/)() const | Obtiene la conexión a la base de datos asociada al comando. |
| virtual [set_CommandText](./set_commandtext/)(String) const | Establece el texto del comando DB. |
| virtual [set_Connection](./set_connection/)(SharedPtr\<System::Data::Common::DbConnection\>) | Obtiene la conexión a la base de datos asociada al comando. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
