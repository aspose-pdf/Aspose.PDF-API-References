---
title: "Clase System::Data::SqlClient::SqlConnectionStringBuilder"
linktitle: "SqlConnectionStringBuilder"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Data::SqlClient::SqlConnectionStringBuilder. Constructor de conexión basado en SQL. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.data.sqlclient/sqlconnectionstringbuilder/
---
## SqlConnectionStringBuilder class


Constructor de conexión basado en SQL. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class SqlConnectionStringBuilder : public System::Data::Common::DbConnectionStringBuilder
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_DataSource](./get_datasource/)() const | Obtiene la fuente de datos (p. ej. nombre de host y puerto). |
| [get_Encrypt](./get_encrypt/)() const | Comprueba si la encriptación está habilitada en la línea. |
| [get_InitialCatalog](./get_initialcatalog/)() const | Obtiene el nombre de la base de datos asociada a la conexión. |
| [get_NetworkLibrary](./get_networklibrary/)() const | Obtiene el nombre de la biblioteca de red utilizada. |
| [get_Password](./get_password/)() const | Obtiene la contraseña utilizada para conectar a la base de datos. |
| [get_TrustServerCertificate](./get_trustservercertificate/)() const | Comprueba si la conexión está protegida usando el certificado de confianza del servidor. |
| [get_UserID](./get_userid/)() const | Obtiene el ID de usuario utilizado para la conexión. |
| [idx_get](./idx_get/)(String) override | Información RTTI. |
| [idx_set](./idx_set/)(String, Object::ptr) override | Establece el objeto con clave. |
| [set_DataSource](./set_datasource/)(const String\&) | Obtiene la fuente de datos (p. ej. nombre de host y puerto). |
| [set_Encrypt](./set_encrypt/)(bool) | Alterna la encriptación activada o desactivada. |
| [set_InitialCatalog](./set_initialcatalog/)(const String\&) | Establece el nombre de la base de datos asociada a la conexión. |
| [set_NetworkLibrary](./set_networklibrary/)(const String\&) | Selecciona la biblioteca de red a usar. |
| [set_Password](./set_password/)(const String\&) | Establece la contraseña que se usará para conectar a la base de datos. |
| [set_TrustServerCertificate](./set_trustservercertificate/)(bool) | Determina si la conexión está protegida usando el certificado de confianza del servidor. |
| [set_UserID](./set_userid/)(const String\&) | Establece el ID de usuario a usar para la conexión. |
## Ver también

* Class [DbConnectionStringBuilder](../../system.data.common/dbconnectionstringbuilder/)
* Namespace [System::Data::SqlClient](../)
* Library [Aspose.PDF for C++](../../)
