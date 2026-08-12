---
title: "System::Xml::XmlNamespaceManager‑klass"
linktitle: "XmlNamespaceManager"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNamespaceManager‑klass. Löser upp, lägger till och tar bort namnrymder i en samling och tillhandahåller omfångshantering för dessa namnrymder i C++."
type: docs
weight: 2300
url: /sv/cpp/system.xml/xmlnamespacemanager/
---
## XmlNamespaceManager class


Löser upp, lägger till och tar bort namnrymder i en samling och tillhandahåller omfattningshantering för dessa namnrymder.

```cpp
class XmlNamespaceManager : public System::Xml::IXmlNamespaceResolver,
                            public System::Collections::Generic::IEnumerable<String>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [AddNamespace](./addnamespace/)(String, String) | Lägger till den angivna namnrymden i samlingen. |
| virtual [get_DefaultNamespace](./get_defaultnamespace/)() | Returnerar namnrymdens URI för standardnamnrymden. |
| virtual [get_NameTable](./get_nametable/)() | Returnerar [XmlNameTable](../xmlnametable/) som är associerad med detta objekt. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator att använda för att iterera genom namnrymderna i [XmlNamespaceManager](./). |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Returnerar en samling av namnrymdnamn nycklade efter prefix som kan användas för att enumerera namnrymderna som för närvarande är i omfång. |
| virtual [HasNamespace](./hasnamespace/)(String) | Returnerar ett värde som anger om det angivna prefixet har en namnrymd definierad för det aktuella stackade omfånget. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Returnerar namnrymdens URI för det angivna prefixet. |
| [LookupPrefix](./lookupprefix/)(const String\&) override | Hittar prefixet som deklarerats för den angivna namnrymdens URI. |
| virtual [PopScope](./popscope/)() | Tar bort ett namnrymdsomfång från stacken. |
| virtual [PushScope](./pushscope/)() | Lägger till ett namnrymdsomfång på stacken. |
| virtual [RemoveNamespace](./removenamespace/)(String, String) | Tar bort det angivna namnutrymmet för den angivna prefixen. |
| [XmlNamespaceManager](./xmlnamespacemanager/)(const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlNamespaceManager](./) med den specificerade [XmlNameTable](../xmlnametable/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
