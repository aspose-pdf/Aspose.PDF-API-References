---
title: "System::Threading::WaitHandle klass"
linktitle: "WaitHandle"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::WaitHandle klass. Väntningsprimitive basklass. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1700
url: /sv/cpp/system.threading/waithandle/
---
## WaitHandle class


Väntningsprimitive basklass. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class WaitHandle : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Close](./close/)() | Frigör alla resurser som är associerade med handtaget. |
| [get_Handle](./get_handle/)() | Hämtar handtaget. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | RTTI-information. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Väntar på att alla handtag ska avfyras. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Väntar på att alla handtag ska avfyras. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | Väntar på att något av handtagen ska avfyras. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Väntar på att något av handtagen ska avfyras. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Väntar på att något av handtagen ska avfyras. |
| virtual [WaitOne](./waitone/)() | Väntar på att handtaget ska avfyras under obegränsad tid. |
| virtual [WaitOne](./waitone/)(int) | Väntar på att handtaget ska avfyras. |
| virtual [WaitOne](./waitone/)(TimeSpan) | Väntar på att handtaget ska avfyras. |
| virtual [WaitOne](./waitone/)(int, bool) | Väntar på att handtaget ska avfyras. |
| virtual [~WaitHandle](./~waithandle/)() | Destruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [WaitTimeout](./waittimeout/) | Speciellt värde som ska returneras av funktionen annars returneras index för signaliserat objekt i arrayen, om tidsgränsen överskrids och inget signalerar. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
