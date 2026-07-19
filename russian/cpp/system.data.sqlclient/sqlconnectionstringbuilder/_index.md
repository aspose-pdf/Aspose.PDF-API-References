---
title: "System::Data::SqlClient::SqlConnectionStringBuilder класс"
linktitle: "SqlConnectionStringBuilder"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Data::SqlClient::SqlConnectionStringBuilder класс. Конструктор соединения на основе SQL. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.data.sqlclient/sqlconnectionstringbuilder/
---
## SqlConnectionStringBuilder class


Конструктор соединения на основе SQL. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SqlConnectionStringBuilder : public System::Data::Common::DbConnectionStringBuilder
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_DataSource](./get_datasource/)() const | Получает источник данных (например, имя хоста и порт). |
| [get_Encrypt](./get_encrypt/)() const | Проверяет, включено ли шифрование в строке. |
| [get_InitialCatalog](./get_initialcatalog/)() const | Получает имя базы данных, связанной с соединением. |
| [get_NetworkLibrary](./get_networklibrary/)() const | Получает имя используемой сетевой библиотеки. |
| [get_Password](./get_password/)() const | Получает пароль, используемый для подключения к базе данных. |
| [get_TrustServerCertificate](./get_trustservercertificate/)() const | Проверяет, защищено ли соединение с помощью доверенного сертификата сервера. |
| [get_UserID](./get_userid/)() const | Получает идентификатор пользователя, используемый для соединения. |
| [idx_get](./idx_get/)(String) override | Информация RTTI. |
| [idx_set](./idx_set/)(String, Object::ptr) override | Устанавливает объект с ключом. |
| [set_DataSource](./set_datasource/)(const String\&) | Получает источник данных (например, имя хоста и порт). |
| [set_Encrypt](./set_encrypt/)(bool) | Включает или отключает шифрование. |
| [set_InitialCatalog](./set_initialcatalog/)(const String\&) | Устанавливает имя базы данных, связанной с соединением. |
| [set_NetworkLibrary](./set_networklibrary/)(const String\&) | Выбирает сетевую библиотеку для использования. |
| [set_Password](./set_password/)(const String\&) | Устанавливает пароль, используемый для подключения к базе данных. |
| [set_TrustServerCertificate](./set_trustservercertificate/)(bool) | Определяет, защищено ли соединение с использованием доверенного сертификата сервера. |
| [set_UserID](./set_userid/)(const String\&) | Устанавливает идентификатор пользователя для соединения. |
## См. также

* Class [DbConnectionStringBuilder](../../system.data.common/dbconnectionstringbuilder/)
* Namespace [System::Data::SqlClient](../)
* Library [Aspose.PDF for C++](../../)
