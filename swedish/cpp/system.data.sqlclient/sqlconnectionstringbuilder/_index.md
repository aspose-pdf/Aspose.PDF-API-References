---
title: "System::Data::SqlClient::SqlConnectionStringBuilder klass"
linktitle: "SqlConnectionStringBuilder"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Data::SqlClient::SqlConnectionStringBuilder klass. SQL‑baserad anslutningsbyggare. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.data.sqlclient/sqlconnectionstringbuilder/
---
## SqlConnectionStringBuilder class


SQL‑baserad anslutningsbyggare. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SqlConnectionStringBuilder : public System::Data::Common::DbConnectionStringBuilder
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_DataSource](./get_datasource/)() const | Hämtar datakälla (t.ex. värdnamn och port). |
| [get_Encrypt](./get_encrypt/)() const | Kontrollerar om kryptering är aktiverad på raden. |
| [get_InitialCatalog](./get_initialcatalog/)() const | Hämtar namn på databasen som är associerad med anslutningen. |
| [get_NetworkLibrary](./get_networklibrary/)() const | Hämtar namnet på det använda nätverksbiblioteket. |
| [get_Password](./get_password/)() const | Hämtar lösenordet som används för att ansluta till databasen. |
| [get_TrustServerCertificate](./get_trustservercertificate/)() const | Kontrollerar om anslutningen är skyddad med ett betrott servercertifikat. |
| [get_UserID](./get_userid/)() const | Hämtar användar‑ID som används för anslutningen. |
| [idx_get](./idx_get/)(String) override | RTTI-information. |
| [idx_set](./idx_set/)(String, Object::ptr) override | Ställer in nyckelobjekt. |
| [set_DataSource](./set_datasource/)(const String\&) | Hämtar datakälla (t.ex. värdnamn och port). |
| [set_Encrypt](./set_encrypt/)(bool) | Slår på eller av kryptering. |
| [set_InitialCatalog](./set_initialcatalog/)(const String\&) | Ställer in namn på databasen som är associerad med anslutningen. |
| [set_NetworkLibrary](./set_networklibrary/)(const String\&) | Väljer nätverksbibliotek att använda. |
| [set_Password](./set_password/)(const String\&) | Ställer in lösenord som ska användas för att ansluta till databasen. |
| [set_TrustServerCertificate](./set_trustservercertificate/)(bool) | Bestämmer om anslutningen är skyddad med ett betrott servercertifikat. |
| [set_UserID](./set_userid/)(const String\&) | Ställer in användar-ID att använda för anslutning. |
## Se även

* Class [DbConnectionStringBuilder](../../system.data.common/dbconnectionstringbuilder/)
* Namespace [System::Data::SqlClient](../)
* Library [Aspose.PDF for C++](../../)
