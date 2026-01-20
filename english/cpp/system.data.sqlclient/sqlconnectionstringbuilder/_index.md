---
title: System::Data::SqlClient::SqlConnectionStringBuilder class
linktitle: SqlConnectionStringBuilder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::SqlClient::SqlConnectionStringBuilder class. SQL-based connection builder. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.data.sqlclient/sqlconnectionstringbuilder/
---
## SqlConnectionStringBuilder class


SQL-based connection builder. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SqlConnectionStringBuilder : public System::Data::Common::DbConnectionStringBuilder
```

## Methods

| Method | Description |
| --- | --- |
| [get_DataSource](./get_datasource/)() const | Gets data source (e. g. hostname and port). |
| [get_Encrypt](./get_encrypt/)() const | Checks whether encription is enabled on line. |
| [get_InitialCatalog](./get_initialcatalog/)() const | Gets name of database associated with connection. |
| [get_NetworkLibrary](./get_networklibrary/)() const | Gets used network library name. |
| [get_Password](./get_password/)() const | Gets password used to connect to database. |
| [get_TrustServerCertificate](./get_trustservercertificate/)() const | Checks whether connection is protected using trust server certificate. |
| [get_UserID](./get_userid/)() const | Gets user id used for connection. |
| [idx_get](./idx_get/)(String) override | RTTI information. |
| [idx_set](./idx_set/)(String, Object::ptr) override | Sets keyed object. |
| [set_DataSource](./set_datasource/)(const String\&) | Gets data source (e. g. hostname and port). |
| [set_Encrypt](./set_encrypt/)(bool) | Toggles encryption on or off. |
| [set_InitialCatalog](./set_initialcatalog/)(const String\&) | Sets name of database associated with connection. |
| [set_NetworkLibrary](./set_networklibrary/)(const String\&) | Selects network library to use. |
| [set_Password](./set_password/)(const String\&) | Sets password to be used to connect to database. |
| [set_TrustServerCertificate](./set_trustservercertificate/)(bool) | Determines whether connection is protected using trust server certificate. |
| [set_UserID](./set_userid/)(const String\&) | Sets user id to use for connection. |
## See Also

* Class [DbConnectionStringBuilder](../../system.data.common/dbconnectionstringbuilder/)
* Namespace [System::Data::SqlClient](../)
* Library [Aspose.PDF for C++](../../)
