---
title: "System::Web::Services::WebServiceBindingAttribute-klass"
linktitle: "WebServiceBindingAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::WebServiceBindingAttribute klass. Används för att deklarera en bindning som definierar en eller flera metoder för XML Web-tjänsten. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.web.services/webservicebindingattribute/
---
## WebServiceBindingAttribute class


Används för att deklarera en bindning som definierar en eller flera metoder för XML [Web](../../system.web/) tjänsten. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class WebServiceBindingAttribute : public System::Attribute
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ConformsTo](./get_conformsto/)() | Hämtar WSI-specifikationen. |
| [get_EmitConformanceClaims](./get_emitconformanceclaims/)() | Hämtar ett värde som indikerar om bindningen avger efterlevnadsanspråk. |
| [get_Location](./get_location/)() | RTTI-information. |
| [get_Name](./get_name/)() | Hämtar bindningens namn. |
| [get_Namespace](./get_namespace/)() | Hämtar det namnrymden som är associerad med bindningen. |
| [set_ConformsTo](./set_conformsto/)(System::SharedPtr\<WsiProfiles\>) | Ställer in WSI-specifikationen. |
| [set_EmitConformanceClaims](./set_emitconformanceclaims/)(bool) | Ställer in ett värde som indikerar om bindningen avger efterlevnadsanspråk. |
| [set_Location](./set_location/)(String) | Ställer in platsen där bindningen är definierad. |
| [set_Name](./set_name/)(String) | Ställer in bindningens namn. |
| [set_Namespace](./set_namespace/)(String) | Ställer in den namnrymden som är associerad med bindningen. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)() | Skapar en ny instans. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String) | Skapar en ny instans. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String, String) | Skapar en ny instans. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String, String, String) | Skapar en ny instans. |
## Se även

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services](../)
* Library [Aspose.PDF for C++](../../)
