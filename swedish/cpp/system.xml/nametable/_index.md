---
title: "System::Xml::NameTable klass"
linktitle: "NameTable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::NameTable klass. Implementerar en enkeltrådad XmlNameTable i C++."
type: docs
weight: 500
url: /sv/cpp/system.xml/nametable/
---
## NameTable class


Implementerar en enkeltrådad [XmlNameTable](../xmlnametable/).

```cpp
class NameTable : public System::Xml::XmlNameTable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const String\&) override | Atomiserar den angivna strängen och lägger till den i [NameTable](./). |
| [Add](./add/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) override | Atomiserar den angivna strängen och lägger till den i [NameTable](./). |
| [Get](./get/)(const String\&) override | Returnerar den atomiserade strängen med det angivna värdet. |
| [Get](./get/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) override | Returnerar den atomiserade strängen som innehåller samma tecken som det angivna teckensintervallet i den givna arrayen. |
| [NameTable](./nametable/)() | Initierar en ny instans av [NameTable](./) klass. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlNameTable](../xmlnametable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
