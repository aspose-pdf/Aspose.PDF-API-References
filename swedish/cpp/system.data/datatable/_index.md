---
title: "System::Data::DataTable klass"
linktitle: "DataTable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Data::DataTable klass. Data strukturerad i rader och kolumner. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.data/datatable/
---
## DataTable class


[Data](../) structured in rows and columns. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DataTable : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Columns](./get_columns/)() | Hämtar kolumner som finns i tabellen. |
| [get_DataSet](./get_dataset/)() | Hämtar den dataset-tabell som den tillhör. |
| [get_Rows](./get_rows/)() | RTTI-information. |
| [get_TableName](./get_tablename/)() | Hämtar tabellnamnet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Data](../)
* Library [Aspose.PDF for C++](../../)
